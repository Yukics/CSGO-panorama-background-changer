@echo off

REM Where the 30 is displayed change this number for the number of videos you have in the folder
REM you must rename your videos from 1 to quantity of videos you have
SET /a nombre=%RANDOM% %%30 +1

REM ruta_videos = path of the folder where you have videos
SET ruta_videos="E:\webm\"

REM ruta_panorama = path of the folder where you have cs installed
SET ruta_panorama="D:\SteamLibrary\steamapps\common\Counter-Strike Global Offensive\csgo\panorama\videos\"

echo %nombre%
copy /y "%ruta_videos%%nombre%.webm" "%ruta_videos%%nombre%1.webm" 
ren "%ruta_videos%%nombre%1.webm" blacksite.webm 
move /Y "%ruta_videos%blacksite.webm" "%ruta_panorama%"


copy /y "%ruta_videos%%nombre%.webm" "%ruta_videos%%nombre%1.webm" 
ren "%ruta_videos%%nombre%1.webm" blacksite540p.webm 
move /Y "%ruta_videos%blacksite540p.webm" "%ruta_panorama%"


copy /y "%ruta_videos%%nombre%.webm" "%ruta_videos%%nombre%1.webm" 
ren "%ruta_videos%%nombre%1.webm" blacksite720p.webm 
move /Y "%ruta_videos%blacksite720p.webm" "%ruta_panorama%"


copy /y "%ruta_videos%%nombre%.webm" "%ruta_videos%%nombre%1.webm" 
ren "%ruta_videos%%nombre%1.webm" nuke.webm 
move /Y "%ruta_videos%nuke.webm" "%ruta_panorama%"


copy /y "%ruta_videos%%nombre%.webm" "%ruta_videos%%nombre%1.webm" 
ren "%ruta_videos%%nombre%1.webm" nuke540p.webm 
move /Y "%ruta_videos%nuke540p.webm" "%ruta_panorama%"


copy /y "%ruta_videos%%nombre%.webm" "%ruta_videos%%nombre%1.webm" 
ren "%ruta_videos%%nombre%1.webm" nuke720p.webm 
move /Y "%ruta_videos%nuke720p.webm" "%ruta_panorama%"
ping 127.0.0.1 -n 2 > nul
