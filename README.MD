# Lumine Proxy

**Lumine Proxy** is a Gophertunnel-based Minecraft Bedrock Edition proxy responsible for handling proxy-side logic in the **Lumine** ecosystem.  
It is part of a multi-repository project including the client, launcher, API, and Discord bot.

---

## Project Structure

The Lumine ecosystem is divided into several components:

- **client** – Wails & Next.js based web application handling Lumine Proxy’s frontend.  
- **proxy** – Gophertunnel-based proxy for Bedrock Edition logic (this repository).  
- **launcher** – Golang-based launcher that manages obfuscated Lumine builds during runtime.  
- **api** – REST API (Go) for key handling and distributing production models.  
- **discord** – Rust + Serenity based Discord bot for generating Lumine keys.  
- **gophertunnel** – General purpose Bedrock library in Go (MIT Licensed).  

---

## Features

- Built-in utility & exploit commands (toggleable) such as:  
  - ANTI KNOCKBACK  
  - AUTO CLICK  
  - FAKE OP  
  - FAST EAT  
  - FLY  
  - FREE CAM  
  - GAME MODE  
  - HELP  
  - HIT BOX  
  - KILL AURA  
  - NO CLIP  
  - NO PACKET  
  - PING  
  - REACH  
  - READ NBT  
  - REFUSE TP  
  - TELEPORT  
  - TIMER  
  - VELOCITY  

---

## Tech Stack

- **Go** – Core proxy logic (Gophertunnel).  
- **TypeScript / Next.js / Wails** – Frontend client.  
- **Rust (Serenity)** – Discord bot.  
- **REST API** – Backend key distribution.  

---

## Screenshots

Below are previews of the **Lumine Client** that integrates with Lumine Proxy:

### Launcher Start
![Launcher Start](assets/e714b0bb-e8b2-403e-959e-6b6b5db822dd.png)

### Microsoft Account Management
![No Account](assets/d19356f1-6e9a-42e7-88c3-7e4ffc051b0c.png)  
![Connection Code](assets/c9211e0c-e8ba-470a-b267-adb493fabdb0.png)  
![Multiple Accounts](assets/1dcda159-5615-4dd1-a06d-b0056fff4fa6.png)  

### Server Connection
![Connect to Server](assets/4546c240-c633-42b7-98f2-fe22b0f8458d.png)

### Waiting for Player
![Waiting for Player](assets/24517bcf-d456-4159-9885-945430d4ccc9.png)

### Connected
![Connected](assets/fc42dcf0-ae5f-4dc5-9ac9-f4d7fa8a4352.png)

---

## License

This project is part of the private Lumine ecosystem.  
`gophertunnel` is licensed under the MIT License.  
