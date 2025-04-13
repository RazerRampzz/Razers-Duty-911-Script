**Razers Duty & 911 Script** is a simple but powerful script that adds a clean on-duty system for LEOs, EMS, and other city departments — plus a functional 911 call system that actually feels useful.

---

### 🚓 What It Does:

* Use `/duty LSPD` (or any department you set up) to go on/off duty
* Shows a live map blip to others on duty — so you know who’s active
* Only players with proper ACE permissions (like `group.leo`) can use the command
* Sends Discord webhooks when players go on/off duty and tracks how long they were active

---

### 🚨 911 Calls Made Useful:

* Players can do `/911 [message]` to alert emergency services
* Shows a blip on the map for 5 minutes at the caller’s location
* Sends a Mythic Notify alert to all on-duty players
* Caller gets a friendly “Call successful” message in chat

---

### 🛠️ Easy to Set Up:

* Works with OneSync
* No database needed
* Fully configurable departments
* Drop in, set your ACE perms, and go

the ace command is command.duty so for example you would put add_ace group.leo command.duty allow in your server.cfg

Requirements

### Ace Permissions: [GitHub - JaredScar/DiscordAcePerms: A fivem script](https://github.com/JaredScar/DiscordAcePerms)

### Mythic Notify (Not needed will fallback on chat if you dont have it but I think it looks a lot more clean) [GitHub - JayMontana36/mythic_notify: A simple FiveM notification resource](https://github.com/JayMontana36/mythic_notify)

### Preview: https://youtu.be/b29NbBfzVMI

| Support | Yes |
