# 🔍 Laporan Hasil Scan Nmap – Metasploitable2

Repository ini berisi dokumentasi hasil scanning Nmap pada host 192.168.100.10.

---

## 🖼️ Screenshot Hasil Scan

### 📌 Screenshot 1
<img src="gambar\gambar 1.png" width="800">

---

### 📌 Screenshot 2
<img src="gambar\gambar 2.png" width="800">

---

### 📌 Screenshot 3
<img src="gambar/gambar 3.png" width="800">

---


---

# 📌 Command Nmap


---

# 📊 Tabel Hasil Scan Port

| Port | Status | Deskripsi |
|------|--------|-----------|
| 21 | open | FTP – vsftpd 2.3.4<br>• ftp-anon: Anonymous login allowed (FTP code 230)<br>• FTP server status: Connected to 192.168.100.10 |
| 22 | open | SSH – OpenSSH 4.7p1 Debian 8ubuntu1 (protocol 2.0)<br>Fingerprint RSA & DSA terdeteksi |
| 23 | open | Telnet – Linux telnetd |
| 25 | open | SMTP – Postfix smtpd<br>• Mendukung PIPELINING, SIZE, VRFY, ETRN<br>• Cert CommonName: ubuntu804-base.localdomain |
| 53 | open | DNS – ISC Bind 9.4.2 |
| 80 | open | HTTP – Apache httpd 2.2.8 (Ubuntu) DAV/2<br>• Title: Metasploitable2 – Linux |
| 111 | open | rpcbind – RPC #100000 |
| 139 | open | SMB – Samba 3.0.20-Debian (WORKGROUP) |
| 445 | open | SMB – Samba 3.0.20-Debian<br>• Vuln NetBIOS<br>• SMB security mode: user-level<br>• Signing disabled |
| 512 | open | exec – BSD rexec |
| 513 | open | login – BSD rlogin |
| 514 | open | shell – BSD rsh |
| 1099 | open | Java RMI – GNU Classpath girmiregistry |
| 2049 | open | NFS – rpc.nfsd |
| 2121 | open | ProFTPD 1.3.1 |
| 3306 | open | MySQL 5.0.51a-3ubuntu5<br>• Default credentials: root (blank) |
| 3632 | open | distccd v1 (GNU) — sering dieksploitasi |
| 5432 | open | PostgreSQL 8.3.x |
| 5900 | open | VNC – protocol 3.3 |
| 6000 | open | X11 (access denied) |
| 6667 | open | UnrealIRCd – IRC (rentan terhadap backdoor) |
| 7001 | open | Apache JServ (Protocol v1.3) |
| 8009 | open | Apache Tomcat AJP13 |
| 8180 | open | Apache Tomcat/Coyote JSP Engine 1.1 |

---

Di buat oleh : Putra Rizki Febriyanta

