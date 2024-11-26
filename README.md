Parameter test
Report Store ..... = GSM Telkomsel + GSM XL

Ping :
- 10.232.5.251 (DNS 1) OK
- 33.33.3.251 (DNS 2) OK
- store.sat.co.id OK
- kiosk.alfacart.com OK
- emkt.sat.co.id OK
- etrans.sat.co.id OK
- androidgate.sat.co.id OK
- tracert intranet.sat.co.id OK
- newkiosk.alfacart.com OK
- portal.sat.co.id OK
- google.com OK
- sso.ext.sat.co.id OK
- alfastore.co.id OK
- telnet 34.101.190.176 3307 = blank screen NOK (not recognized)
- facebook.com = OK
- youtube.com = OK
- instagram.com = OK


Aplikasi :
- GSM Primary signal strength RSRP OK -95 (excelent)
- GSM Backup signal strength RSRP OK -94 (pair to poor)
- Speedtest.net OK
- e-transaction OK
- web portal/SIS android OK
- Scan Ponta OK
- https://google.com OK
- https://partner.sunmi.com OK
- https://gobiz.co.id OK 
- https://www.alfastore.co.id/about OK (error)
- https://api.alfastore.co.id/api/sis/test_endpoint OK
- https://app.alfastore.co.id/prd/api/so OK
- https://kiosk.alfacart.com/login OK
- https://intranet.sat.co.id/ OK
- https://service-anjungan-prd-rjzigbgnna-et.a.run.app/ OK
- https://histonetec.com OK
- www.facebook.com = blocked NOK
- www.youtube.com = blocked NOK
- www.instagram.com = blocked NOK
- www.shopee.co.id = blocked NOK
- https://portal.sat.co.id OK


Perangkat Tambahan :
- PDA OK
- TABLET OK
ASA [ OK ] 
MAXDIS [ OK ]  
PRODUK INFO [ OK ] 
Alfa Learning [ OK ] 

Dual GSM
- GSM Primary Telkomsel UP
- GSM Backup XL UP
- Failover OK

Test applikasi tambahan via Backup :
- Etrans  OK
- ⁠Web portal OK
- ⁠Scan ponta OK
- ⁠Zimbra OK



=============================================================

step by step failover
1. ping 10.232.5.251 -t (di cmd pc kasir)
2. tunggu 5 detik, cabut link modem primary di port wan forti
3. pantau cmd di pc kasir, jika ada rto sekali atau latency nya berubah, tanda nya failover sukses
4. Foto ping nya di cmd nya
5. colok lgi link modem primary di port wan forti
