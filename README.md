# Blue Lock Rival - Auto Farm Neo Ego 2.0

Auto farm script for Blue Lock Rival (Roblox). Automatically completes Neo Ego tasks, collects XP, and claims rewards.

## Features
- ✅ Auto complete 5 tasks: Score, Assist, Tackle, Pass, Distance
- ✅ Auto collect XP orbs
- ✅ Auto claim rewards
- ✅ Auto reset task list after completion
- ✅ Toggle ON/OFF with F9
- ✅ Anti-cheat bypass (basic)
- ✅ Respawn handler

## Requirements
- Roblox Executor (Delta X, KANZ, Synapse, Krnl, etc.)
- Blue Lock Rival game

## Installation
1. Copy the entire script from `main.lua`
2. Open your executor
3. Inject into Roblox
4. Paste the script
5. Click Execute

## Usage
- Script starts automatically after execution
- Press **F9** to toggle Auto Farm ON/OFF
- Check executor console for status messages

## Configuration
Edit the `CONFIG` table at the top of the script:
```lua
local CONFIG = {
    Speed = 60,              -- Walk speed
    JumpPower = 150,         -- Jump power
    TeleportDistance = 30,   -- Max distance to teleport
    AutoClaimReward = true,  -- Auto claim rewards
    AutoCollectXP = true,    -- Auto collect XP
    TaskInterval = 1.0,      -- Delay between tasks (seconds)
    AutoResetTasks = true,   -- Auto reset task list
    ToggleKey = Enum.KeyCode.F9 -- Toggle key
}
