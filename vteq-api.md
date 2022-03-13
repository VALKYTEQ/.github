# API | ..a project by VALKYTEQ


API Service Calls  
Project: **_vteq-api_**

### Contact:
You can reach out to us over...  
[E-Mail](mailto:mail@valkyteq.com?Subject=Github)   |    [Twitch](https://www.twitch.tv/valkyfischer)   |    [Discord](https://discord.gg/Ug2ne5K)  

<br><br>

## API
### Artificial Intelligence
Send a POST ```req``` to following URI and get according ```res```:
```
URI                     Response              Command
--------------------------------------------------------------------
/ai/chat                AI Chat               -
/ai/translate           AI Translation        -
```

### Discord
Send a POST ```req``` to following URI and get according ```res```:
```
URI                     Response              Command
--------------------------------------------------------------------
/discord/news           -                     Discord News
/discord/announce       -                     Discord Announcement
```

### Animat3D
Send a POST ```req``` to following URI and get according ```res```:
```
URI                     Response              Command
--------------------------------------------------------------------
/animat3d/login         A3D Account Info      -
/animat3d/hash          A3D Client Hashes     -
/animat3d/get           A3D Character Info    -
/animat3d/set           -                     A3D Character Save
/animat3d/buy           -                     A3D Item Unlock
/user/{#id}/a3d         -                     A3D Client Event
```

### Misc
Send a POST ```req``` to following URI and get according ```res```:
```
URI                     Response              Command
--------------------------------------------------------------------
/quotes                 All Quotes            -
/quotes/{#id}           Quote by ID           -
/ping                   Heartbeat             -
```
