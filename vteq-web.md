# Valkyrie C.M.S. | ..a project by VALKYTEQ


Web Content Management System for VALKYTEQ  
Project: **_vteq-web_**

### Contact:
You can reach out to us over...  
[E-Mail](mailto:mail@valkyteq.com?Subject=Github)   |    [Twitch](https://www.twitch.tv/valkyfischer)   |    [Discord](https://discord.gg/Ug2ne5K)  

<br><br>

## CMS Content
### Artificial Intelligence
- Chat Bot
- Translator

### L.U.N.A.
- API
- Management
- Twitch Bot
- Discord Bot

### Valkyrie C.M.S.
- Server statistics
- Logging of processes
- Registration of user accounts
- Multi Language WebService

### Animat3D
- API
- Management
- Animat3D Launcher
- Animat3D Client

<br><br>

## Requirements
- [vteq-luna](https://github.com/VALKYTEQ/vteq-luna)
- [vteq-animat3d](https://github.com/VALKYTEQ/vteq-animat3d)
- [vteq-animat3d-loc](https://github.com/VALKYTEQ/vteq-animat3d-loc)

<br><br>

## CMS Configuration
### Composer Setup
Install composer, run ```cmd.exe``` and install:
```
  'composer require phpmailer/phpmailer'
```

### ValkyDB Setup
Open ```/core/config.php``` and set:
```
  'mysqlHost' => 'localhost',
  'mysqlUser' => 'user',
  'mysqlPassword' => 'pass',
  'mysqlBase' => 'ValkyDB',
```

### Admin Setup
Open ```/core/config.php``` and set:
```
  'adminLogin' => 'UserAccount',
  'site-url' => 'your-domain.com',
```

### E-Mail Setup
Open ```/core/config.php``` and set:
```
  'email' => 'mail@your-domain.com',
  'smtphost' => 'smtp.your-domain.com',
  'smtpuser' => 'user',
  'smtppass' => 'pass!',
```

### reCaptcha v3 Setup
Open ```/core/config.php``` and set:
```
  'reSiteKey' => 'reCaptcha-v3-Site-Key',
  'reSecretKey' => 'reCaptcha-v3-Secret-Key',
```
