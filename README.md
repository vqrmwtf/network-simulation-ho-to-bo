# network-simulation-ho-to-bo
Use Case: Sebuah perusahaan memiliki kantor pusat di Jakarta dan kantor cabang di Surabaya. Namun Kedua kantor perlu terhubung. Bagaimana caranya? 

Topologi Jaringan

Head Office Network

Router: Cisco 2911 (R1-HO)\
Switch: Cisco 2960-24TT (SW1-HO) - Support VLAN\
Server: Generic Server (Web Server, DNS Server)\
PC Staff: 2 unit PC untuk staff (VLAN 10)\
PC Manager: 1 unit PC untuk manager (VLAN 20)\
PC Direktur: 1 unit PC untuk direktur (VLAN 30)\
Printer: Generic Printer (VLAN 10 - Shared)

Branch Office Network

Router: Cisco 2911 (R2-BO)\
Switch: Cisco 2960-24TT (SW2-BO) - Support VLAN\
PC Staff: 1 unit PC untuk staff (VLAN 10)\
PC Manager: 1 unit PC untuk manager (VLAN 20)\
Laptop: 1 unit Laptop untuk direktur (VLAN 30)

Koneksi Antar Site

Metode: Ethernet Connection (Cross-over cable)\
Interface: FastEthernet/GigabitEthernet

Skema IP Addressing & VLAN\
VLAN Configuration

VLAN 10 (Staff): 192.168.x.0/26 (62 host per VLAN)\
VLAN 20 (Manager): 192.168.x.64/27 (30 host per VLAN)\
VLAN 30 (Direktur): 192.168.x.96/28 (14 host per VLAN)\
VLAN 99 (Management): 192.168.x.224/28 (14 host per VLAN)

📞 Contact & Collaboration\
Proyek ini dikembangkan sebagai bagian dari portfolio IT Network & Cybersecurity. Untuk diskusi lebih lanjut mengenai implementasi atau pengembangan proyek ini, silakan hubungi melalui:

LinkedIn: https://www.linkedin.com/in/viqramwataf/  
Email: viqram01@gmail.com
