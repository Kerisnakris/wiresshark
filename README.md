menjalankan data Wireshark dengan wifi
![awal](https://github.com/Kerisnakris/wiresshark/assets/126413528/636e6680-c5a1-4870-9c3a-03eeab7fec58)
membuka wifi buka aplikasi yang akan di jalankan selama 10 menit untuk mendapatkan data, setelah semua di lakukan stop aplikasi tersebut
![image](https://github.com/Kerisnakris/wiresshark/assets/126413528/8a53719f-c6bc-4b48-a1c9-0858d2b5ae85)
selanjutnya kita akan menghitung throughput
![image](https://github.com/Kerisnakris/wiresshark/assets/126413528/cbadb928-ab4c-41bc-9b5c-5b5c4981a9e7)
analisi: jumlah bytes : time span= 81000183 bytes : 690.521 s = 117302 bytes/s = 117302 kb/s = 117.302 x 8 = 938 kb/s
selanjutnya menghitung packet loss
![image](https://github.com/Kerisnakris/wiresshark/assets/126413528/2c594baa-eb6f-4317-8371-7e9020b34ef5)
analisis: paket diterima= paket dikirim - paket diterima = 83766 - 959 = 82807 paket loss= (((paket dikirim - paket diterima)/paket dikirim) x 100) = (((83766 - 82807)/83766)x100) = 114.5758661887694
menghitung delay
![image](https://github.com/Kerisnakris/wiresshark/assets/126413528/0e2c2fae-3c4f-4457-9ab4-addd59218e8f)
jadi nilai dari data delay dan rata-rata delay sebagai berikut total delay= 1378.4232 rata-rata delay= 0.0164558
![image](https://github.com/Kerisnakris/wiresshark/assets/126413528/0af92e33-6d62-4945-bea6-cb051484872e)
jadi, didapatkan hasil dari nilai jitter dan rata-sata jitter juga sebagai berikut: total jitter= 1381.5802 rata-rata jitter= 0.0164935
