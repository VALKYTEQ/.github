# L.U.N.A. | ..a project by VALKYTEQ


Limitless Universal Numeric Assistant  
Project: **_vteq-luna_**

### Contact:
You can reach out to us over...  
[E-Mail](mailto:mail@valkyteq.com?Subject=Github)   |    [Twitch](https://www.twitch.tv/valkyfischer)   |    [Discord](https://discord.gg/Ug2ne5K)  

<br><hr><br>

## LUNA Content
### Artificial Intelligence
- Chat Bot
- Translator

### Integrations
- [LUNA's Home](https://valkyteq.com/luna/)
- Twitch Bot
- Discord Bot

### Valkyrie C.M.S.
- Management
- Announcements

### Animat3D
- API

<br><hr><br>

## Requirements
- node-js
- [vteq-web](https://github.com/VALKYTEQ/vteq-web)
- [vteq-animat3d](https://github.com/VALKYTEQ/vteq-animat3d)

<br><hr><br>

## Configuration
### Installation
- Install ```pm2``` with node
- Run ```npm i``` in ```/LUNA``` root directory

### Edit Config
Open ```Valkyrie C.M.S.``` and adjust accordingly:
```
https://valkyteq.com/admin/luna-settings/
```

### Start L.U.N.A.
Go into ```/LUNA``` root directory and run:
```
pm2 start vteq-luna.js --watch
```

### Monitor L.U.N.A.
Go into ```/LUNA``` root directory and run:
```
pm2 monit
```
