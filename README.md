# Jarkom-Modul-2-F11-2022

### Kelompok F11

| **No** | **Nama** | **NRP** | 
| ------------- | ------------- | --------- |
| 1 | Ryo Hilmi Ridho  | 5025201192 | 
| 2 | Moh. Ilham Fakhri Zamzami | 5025201275 |
| 3 | Putu Andhika Pratama | 5025201132 |

## Script

- Ostania
    
    ```bash
    iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 10.34.0.0/16
    ```
    
- SSS
    
    ```bash
    echo nameserver 192.168.122.1 > /etc/resolv.conf
    ```
    
- Garden
    
    ```bash
    echo nameserver 192.168.122.1 > /etc/resolv.conf
    ```
    
- WISE
    
    ```bash
    echo nameserver 192.168.122.1 > /etc/resolv.conf
    ```
    
- Berlint
    
    ```bash
    echo nameserver 192.168.122.1 > /etc/resolv.conf
    ```
    
- Eden
    
    ```bash
    echo nameserver 192.168.122.1 > /etc/resolv.conf
    ```
    
    
## Soal 1

### Soal
WISE akan dijadikan sebagai DNS Master, Berlint akan dijadikan DNS Slave, dan Eden akan digunakan sebagai Web Server. Terdapat 2 Client yaitu SSS, dan Garden. Semua node terhubung pada router Ostania, sehingga dapat mengakses internet

### Jawaban
