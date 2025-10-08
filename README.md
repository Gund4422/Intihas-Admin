# Intiha's Admin v1.1

**A client-side, FE-safe admin script for Roblox**.  
Designed to work entirely locally in FilteringEnabled (FE) games, with easy command creation via a helper function.

---

## Features

- **Command Bar GUI** – Type commands directly in-game
- **Built-in Commands:**
  - `:fly` – Toggle flying
  - `:speed <number>` – Set WalkSpeed
  - `:jump <number>` – Set JumpPower
  - `:esp` – Toggle ESP on other players
- **Add your own commands easily** using:
  ```lua
  addCmd("commandName", function(args)
      -- Your code here
  end)
