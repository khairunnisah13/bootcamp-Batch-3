# Writing-and-Presentation-week1

## Unix Comman Lind
1.  Terminal Basic merupakan proses menampilkan file/folder dengan pengetikkan di Command Prompt atau Windows Powershell.
Terdapat beberapa perintah atau navigation pada terminal basic sebagai berikut:
- perintah ls untuk menampilkan list folder/file 
- perintah ls-la untuk menampilkan folder yang disembuyikan
- perintah cd untuk memindahkan folder ke dokumen yang diinginkan
- perintah cd+.. untuk kembali ke folder sebelumnya
- perintah ni nama_file.extensi untuk membuat file baru didalam folder
- perintah clear untuk membersihkan tampilan terminal
- perintah cp untuk mengkopi atau menggandakan file/folder
- perintah rm untuk meremove atau menghapus file/folder
- perintah mkdir untuk membuat folder baru

2.  contoh exercise
    - Directory: C:\Users\ADMIN


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         5/24/2022  11:16 AM                .config
d-----         5/13/2022   2:16 PM                .quokka
d-----          4/5/2021  12:16 AM                .vscode
d-----         7/18/2022   7:44 AM                .wakatime
d-----         5/12/2022   2:17 PM                .wallaby
d-r---          6/1/2022   9:02 PM                3D Objects
d-r---          6/1/2022   9:02 PM                Contacts
d-r---         7/18/2022   7:42 AM                Desktop
d-r---         7/18/2022  12:06 PM                Documents
d-r---         7/18/2022  10:29 AM                Downloads
d-r---          6/1/2022   9:02 PM                Favorites
d-----         7/18/2022  11:21 AM                Firts
d-r---          6/1/2022   9:02 PM                Links
d-----         7/18/2022  11:21 AM                ls
d-r---          6/1/2022   9:02 PM                Music
d-r---          4/5/2021  12:28 AM                OneDrive
d-r---         7/14/2022   8:08 AM                Pictures
d-r---          6/1/2022   9:02 PM                Saved Games
d-r---          6/1/2022   9:02 PM                Searches
d-r---          6/1/2022   9:02 PM                Videos
-a----         7/15/2022   8:03 PM           6081 .bash_history
-a----         4/28/2022   4:14 PM              0 .dbshell
-a----         4/18/2022   2:39 PM             88 .gitconfig
-a----         5/31/2022  10:34 AM             20 .lesshst
-a----         4/28/2022  10:30 AM              0 .mongorc.js
-a----         5/12/2022  10:25 AM              6 .node_repl_history
-a----         7/18/2022   9:55 AM            169 .wakatime-internal.cfg
-a----         7/18/2022   9:55 AM          65536 .wakatime.bdb
-a----          6/3/2022   2:07 PM             92 .wakatime.cfg
-a----         7/18/2022   7:51 AM          18303 .wakatime.log
-a----         5/24/2022  11:35 AM            121 .yarnrc
-a----         7/18/2022   7:04 AM             23 README.md


PS C:\Users\ADMIN> cd Documents
PS C:\Users\ADMIN\Documents> ls


    Directory: C:\Users\ADMIN\Documents


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         7/18/2022  10:07 AM                AMMAN CODING BOOTCAMP3
d-----         7/14/2022   8:34 AM                Custom Office Templates
d-----         7/18/2022  12:06 PM                First
d-----         7/15/2022   5:40 PM                khairunnisah


PS C:\Users\ADMIN\Documents> cd First
PS C:\Users\ADMIN\Documents\First> ls


    Directory: C:\Users\ADMIN\Documents\First


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         7/18/2022  12:06 PM              0 Person.txt


PS C:\Users\ADMIN\Documents\First> ls


    Directory: C:\Users\ADMIN\Documents\First


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         7/18/2022  12:06 PM              0 Another.txt.txt


PS C:\Users\ADMIN\Documents\First> ls


    Directory: C:\Users\ADMIN\Documents\First


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         7/18/2022  12:06 PM              0 Another.txt


PS C:\Users\ADMIN\Documents\First> cp Another.txt copy.txt
PS C:\Users\ADMIN\Documents\First> ls


    Directory: C:\Users\ADMIN\Documents\First


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         7/18/2022  12:06 PM              0 Another.txt
-a----         7/18/2022  12:06 PM              0 copy.txt


PS C:\Users\ADMIN\Documents\First> rm copy.txt
PS C:\Users\ADMIN\Documents\First> ls


    Directory: C:\Users\ADMIN\Documents\First


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         7/18/2022  12:06 PM              0 Another.txt


PS C:\Users\ADMIN\Documents\First> cd ..
PS C:\Users\ADMIN\Documents> cp First Second
PS C:\Users\ADMIN\Documents> ls


    Directory: C:\Users\ADMIN\Documents


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         7/18/2022  10:07 AM                AMMAN CODING BOOTCAMP3
d-----         7/14/2022   8:34 AM                Custom Office Templates
d-----         7/18/2022  12:19 PM                First
d-----         7/15/2022   5:40 PM                khairunnisah
d-----         7/18/2022  12:19 PM                Second


PS C:\Users\ADMIN\Documents> rm Second
PS C:\Users\ADMIN\Documents> ls


    Directory: C:\Users\ADMIN\Documents


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         7/18/2022  10:07 AM                AMMAN CODING BOOTCAMP3
d-----         7/14/2022   8:34 AM                Custom Office Templates
d-----         7/18/2022  12:19 PM                First
d-----         7/15/2022   5:40 PM                khairunnisah


PS C:\Users\ADMIN\Documents> ^C
PS C:\Users\ADMIN\Documents> ls


    Directory: C:\Users\ADMIN\Documents


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         7/18/2022  10:07 AM                AMMAN CODING BOOTCAMP3
d-----         7/14/2022   8:34 AM                Custom Office Templates
d-----         7/18/2022  12:19 PM                First
d-----         7/15/2022   5:40 PM                khairunnisah


** Copywright By Khairunnisah - 2022**
