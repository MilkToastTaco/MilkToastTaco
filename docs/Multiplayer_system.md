# Milk Toast Taco Multiplayer System `V1`

Universal Multiplayer System for MTT!

Lives under `core/multiplayer/`.

In MTT multiplayer, the **Server** is the 'prime authority'.
The Server Manages everything, clients listen to the server, clients can send input to the server and the server updates the state and sends it back to the client.

We'll probbably need a **Account** system to manage the MTT Player accounts.

Each MTT user will be assigned an **Account ID** and a **Player ID**.

The account ID is there main ID.
The player ID is the ID of there individual profiles.

Any MTT user can create up to 20 individual profiles on there account, each with diffrent names.
There profile accounts have there own seperate saves and stats.
One profile might have $500 and 600XP, and another might have $0 and 0XP. All under one MTT user.

If you get banned from a server, your **Account ID** is what gets banned.
So changing your player profile and you will still be banned, nothing will change.

Bans are saved to a MTT servers `bans.xml`.

Even in singleplayer MTT, it still uses the same **Account ID** and **Player ID** system. Just you cant get banned in singleplayer 🤣
