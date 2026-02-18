```bash
nmap -sV -O -A 92.51.39.106           
Starting Nmap 7.98 ( https://nmap.org ) at 2026-02-15 18:11 +0300
Nmap scan report for 1427771-cg36175.tw1.ru (92.51.39.106)
Host is up (0.0092s latency).
Not shown: 998 filtered tcp ports (no-response)
PORT   STATE  SERVICE VERSION
22/tcp open   ssh     OpenSSH 8.2p1 Ubuntu 4ubuntu0.13 (Ubuntu Linux; protocol 2.0)
| ssh-hostkey: 
|   3072 35:81:8a:da:50:19:aa:65:c1:95:ad:2f:db:a9:ea:ed (RSA)
|   256 7b:c8:3e:dc:d6:70:77:37:be:a5:72:6d:20:5b:ee:8f (ECDSA)
|_  256 31:f5:6d:b5:34:6a:96:fd:97:5c:5e:4e:2c:64:fc:4f (ED25519)
53/tcp closed domain
Device type: VoIP adapter|bridge|general purpose
Running (JUST GUESSING): AT&T embedded (93%), Oracle Virtualbox (91%), Slirp (91%), QEMU (89%)
OS CPE: cpe:/o:oracle:virtualbox cpe:/a:danny_gasparovski:slirp cpe:/a:qemu:qemu
Aggressive OS guesses: AT&T BGW210 voice gateway (93%), Oracle Virtualbox Slirp NAT bridge (91%), QEMU user mode network gateway (89%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 1 hop
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

TRACEROUTE (using port 80/tcp)
HOP RTT     ADDRESS
1   0.32 ms 1427771-cg36175.tw1.ru (92.51.39.106)

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 15.67 seconds

```

