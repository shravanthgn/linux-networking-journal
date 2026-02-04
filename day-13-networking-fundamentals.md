# Day 13 – Networking Fundamentals (CCNA Ep 0 & 1)

## What I did today
- Watched NetworkChuck CCNA Episode 0 ("What is a Network") and Episode 1 ("What is a Switch").
- Explored the difference between "dumb" and "smart" network devices.
- Verified my Ubuntu VM's network "door" using the terminal.

## Key Concepts Learned
- **The Network:** Simply a collection of devices connected to share resources (files, internet, printers).
- **The Hub (The "Dumb" Device):** It repeats every signal it receives to every port. It creates "noise" and collisions because it doesn't know who is who.
- **The Switch (The "Smart" Device):** The heart of the modern LAN. It builds a **MAC Address Table** to remember which device is on which port, sending data only where it needs to go.



## Hands-on (Ubuntu Terminal)
- Used `ip a` to find my interface name and MAC address (link/ether).
- Used `ping` to verify that my "virtual" network cable is working.

## One Takeaway
A switch is like a smart mailman who knows exactly which house a letter belongs to, while a hub is like someone standing in the street shouting the letter's contents to everyone.

## Next Goal
Understand the "GPS" of networking: IP Addresses and Subnetting.
