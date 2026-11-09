# PAYDAY-2-Lobby-Resync-Fix
PAYDAY 2 Lobby Resync Fix is a mod that it's still wip that fixes peer-to-peer connection between players ensuring there is no random player visibility issues in lobby and trying to resync it for everyone.



There is an issue in new Diesel Engine 3.0 on 64 bit that causes players to lose sync between them

Example:
player 1 -- host (sees everyone just fine)
player 2 -- sees everyone just fine
player 3 -- doesn't see player 4 (sync issue)
player 4 -- doesn't see player 3 (sync issue)

when you try to start the game, everyone will be ready but game won't start because player 3 and player 4 are desynced from each other 
fix for that is leaving lobby and joining back or restarting whole game, in worst case host need to restart whole lobby in order to sync to fix on next connections

Currently trying to look for patterns that can cause that bug, for the last 2 month i've been playing public lobby's or private with friends there is always a bug after couple games
