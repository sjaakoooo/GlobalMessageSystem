# 🌍 GlobalMessageSystem
A lightweight cross-server messaging system for Roblox developers.  
Send messages instantly to all servers in your game with admin control and a clean UI.

## 🚀 Features
• Fast and simple  
• Easily customizable  
• You can choose who can use it  
• Easy to import into any game  

## 📌 The Process

I wanted a way to send messages to everyone in my game, but the normal chat wasn’t suitable because I wanted messages to be sent across every server.

I started simple by making a GUI that prints what the player types when they press the send button.

After that, I changed it so instead of printing, it creates a GUI at the top of the screen showing the message with a colored name.

Then I moved on to the server system. I first created a table where I could add admins who are allowed to use the system.

After that, I used MessagingService to send the message to every server.

When each server receives the message, it sends it to all players and updates the GUI.

After a few bug fixes, the system was finished!

## 🛠️ Tech Stack

• Roblox Studio  
• Lua  
• RemoteEvents  
• MessagingService  

## ⬇️ Install the Project

1. Download the `.rbxl` file
2. Open it in Roblox Studio
3. Go to `ServerScriptService > Global > Message > GlobalMessageHandler`
4. Replace the admin UserId with your own UserId
5. Start the game, type a message in the bottom-left corner, and press send

⚠️ Make sure "Enable Studio Access to API Services" is turned on in Game Settings > Security, otherwise MessagingService will not work.

## 📷 Preview
https://github.com/user-attachments/assets/91ae33e8-9398-44a0-9514-1ac59bd8a0fd
