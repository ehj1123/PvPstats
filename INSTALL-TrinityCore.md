How to install PvPstats system in TrinityCore
========

1) Update your core and database to **latest revision** (recommended), or manually import [this commit](https://github.com/TrinityCore/TrinityCore/commit/b65172910c4f65c3ddd3a7c7ca3d3c7330f4a1f0) (not recommended).

2) Open your **worldserver.conf** file and set:
```
Battleground.StoreStatistics.Enable = 1
```

3) Clone the repository:
```
git clone https://github.com/ShinDarth/PvPstats.git
```

4) Open the "**web**" folder and copy all contents into a new folder of your web server (e.g. /var/www/PvPstats)

5) Open the file **config.php** and edit it properly (it's quite commented).

Do not forget to set the parameters for database connections and your expansion.



Please report any bug at: https://github.com/ShinDarth/PvPstats/issues