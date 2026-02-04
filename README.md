# Config-mikrotik
Reset Konfigurasi Default MikroTik
Konfigurasi WAN di MikroTik yang menuju ke ISP ( Indihome, Oxygen, MyRepublic, Biznet, dll )
ping dari MikroTik ke Internet  
Memberikan IP Address untuk jaringan LAN
Buatkan DHCP Server untuk ke jaringan LAN sehingga Laptop/PC dapat IP Otomatis
Network Address
Gateway
IP Pool 
DHCP Address Space = otomatis akan terisi NETWORK Address nya
Gateway for DHCP Network = otomatis akan terisi IP si Router ( 192.168.100.1 )
Addresses to Give Out = Range IP yang akan diberikan oleh client, misal nya 192.168.100.2-254
DNS Servers = Isi salah satu DNS Server yang akan digunakan, bisa DNS Provider, DNS Google, dll
Lease Time : Waktu “sewa” yang akan diberikan oleh client, jika client tidak akses jaringan lebih dari waktu itu, maka ip tersebut bisa diberikan ke client lain.
pastikan Laptop/PC mendapatkan IP Otomatis dan bisa ping ke Router
