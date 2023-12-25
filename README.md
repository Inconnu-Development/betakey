# BetaKey - advanced beta access system

# Buy me https://builtbybit.com/resources/betakey-advanced-beta-access-system.18428/

Support:

Discord: https://discord.gg/vrQUJnN


English

This is a beta system with which you can give codes to your community, these codes can be activated on the website provided. As soon as a player has unlocked himself with a code, he can join the Minecraft server/network.


As an admin you can easily create random and custom keys on the Minecraft server


Set up:

First you have to set up the Minecraft plugin and then the website can be set up.


Spigot:

Load the plugin into the plugin folder of the Spigot server. Restart this server and enter your MySql data in Config.yml and add your Minecraft name to the whitelist. Restart your Spigot server again, give you the permission betakey.admin or OP and create or delete keys with the command /betakey.


BungeeCord:

Load the plugin into the plugin folder of the BungeeCord server (not into the other sub-servers, only into the proxy). Restart this server and enter your MySql data in Config.yml and add your Minecraft name to the whitelist. Restart your BungeeCord server again, give you the betakey.admin or OP permission and create or delete keys with the /betakey command.


Use either the spigot or the bungee cord version of the plugin. The spigot version is not necessary for bungee cord!


Website:

Upload the website to your webspace (var / www / html) and enter your MySql data in MYSQL.php.


Features:

    Create keys ingame
    Delete keys ingame
    Whitelist for player
    Create random key
    Create custom key
    100% custom messages
    Custom prefix
    Custom kick-message
    Custom Mysql port (Plugin & Website)
    Custom website background images
    Website support German and English
    Player can just redeem one code
    Code can just be redeemed once
    UUID support
    MySQL support
    Developer API
    SourceCode


Commands / Permissions:

    /betakey - shows you help - betakey.admin
    /betakey delete <key> - remove a key - betakey.admin
    /betakey create custom <key> - create a custom beta key -  betakey.admin
    /betakey create random -  create a random beta key -  betakey.admin
    /betakey reload -  Reload the Config.yml -  betakey.admin

API:

Create a key:

[CODE]BetaKeyAPI.createKey("key");[/CODE]

Delete a key:

[CODE]BetaKeyAPI.deleteKey("key");[/CODE]

Check if a key already exists:

[CODE]if (BetaKeyAPI.keyAlreadyExists("key")){

  // Do stuff if key exists

}[/CODE]


Tutorial:

- [MEDIA=youtube]r5VgLeTZPEM[/MEDIA]


Deutsch

Das ist ein Beta System mit den ihr Codes an eure Community geben könnt, diese Codes lassen sich auf der mitgelieferten Webseite freischalten. Sobald sich ein Spieler mit einem Code freigeschaltet hat, kann er auf den Minecraft Server/Netzwerk joinen. 


Als Admin kannst du ganz einfach auf dem Minecraft Server random und custom Keys erstellen  


Setup:

Als erstes muss richtest du das Minecraft Plugin ein und danach kann die Webseite eingerichtet werden.  


Spigot:

Lade das Plugin in den Plugin Ordner des Spigot Servers. Restarte diesen Server und trage in die Config.yml deine MySql Daten an und adde deinen Minecraft Namen in der Whitelist. Restarte erneut deinen Spigot Server, gib dir die Permission betakey.admin oder OP und erstelle bzw lösche Keys mit den Command /betakey.  


BungeeCord:

Lade das Plugin in den Plugin Ordner des BungeeCord Servers (Nicht in die anderen Unterserver nur in den Proxy). Restarte diesen Server und trage in die Config.yml deine MySql Daten an und adde deinen Minecraft Namen in der Whitelist. Restarte erneut dein BungeeCord Server, gib dir die Permission betakey.admin oder OP und erstelle bzw lösche Keys mit den Command /betakey. 


Nutze entweder die Spigot- oder die Bungeecord-Version des Plugins. Für Bungeecord ist die Spigot-Version nicht notwendig!


Webseite:

Lade die Webseite auf dein webspace (var/www/html) hoch und trage in die MYSQL.php deine MySql Daten ein.


Features:

    Erstelle keys ingame
    Lösche keys ingame
    Whitelist für Spieler
    Erstelle random key
    Erstelle custom key
    100% custom messages
    Custom prefix
    Custom kick-message
    Custom MySql Port (Plugin & Webseite)
    Custom Webseiten Hintergrundbild
    Webseite support Deutsch und Englisch
    Spieler können nur einen Key verwenden
    Jeder Key kann nur einmal verwendet werden
    UUID support
    MySQL support
    Developer API
    SourceCode


Commands / Permissions:

    /betakey - zeigt dir eine Hilfe an - betakey.admin
    /betakey delete <key> - Lösche ein key - betakey.admin
    /betakey create custom <key> - erstlle einen custom Betakey -  betakey.admin
    /betakey create random -  erstlle einen random Betakey -  betakey.admin
      /betakey reload -  Lade die Config.yml neu -  betakey.admin 

API:

Erstelle einen Key:

[CODE]BetaKeyAPI.createKey("key");[/CODE]

Lösche einen Key:

[CODE]BetaKeyAPI.deleteKey("key");[/CODE]

Schau, ob ein Key schon existiert:

[CODE]if (BetaKeyAPI.keyAlreadyExists("key")){

  // Do stuff if key exists

}[/CODE]


Tutorial:

- [MEDIA=youtube]5z7CSiRmCXw[/MEDIA]
