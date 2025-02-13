# ProviderDetail-WiFiQuality
This repository contain about the analysis of detail and status about some providers using Network Cell Info and checking the quality of WiFi using WiFi Analyzer

Group 2 :
- Fery Dwi Darmawan
- M. Gavin Hawwari
- Rizky Ramadhan
- Muhammad Rizki Febrian

## Why we need to Analyze?
Analyzing mobile network providers and WiFi quality is crucial for ensuring a stable, fast, and reliable connection in different locations. Here’s why it matters:

**1. Ensuring Good Mobile Network Connectivity**
- Better Call Quality & Data Speed → Identifying which provider offers the best signal strength (RSSI, RSRP, RSRQ, SINR) for smoother calls and faster internet.
- Coverage Optimization → Helps users decide which provider works best in a specific area (home, office, or outdoors).
- Troubleshooting Connectivity Issues → Finding weak signal zones to improve mobile network coverage
  
**2️. Improving WiFi Performance**
- Better Internet Speed & Stability → Analyzing WiFi signal strength (dBm), latency, and congestion to ensure a smooth browsing and streaming experience.
- Reducing Interference → Identifying overlapping WiFi channels and switching to a less congested one for better performance.
- Optimizing Router Placement → Finding the best location for a WiFi router to maximize coverage and minimize dead zones.
  
**3️. Helping in Decision-Making**
- Choosing the Best Mobile Provider → Based on signal strength and reliability in a specific area.
- Upgrading or Changing ISP (Internet Service Provider) → If WiFi performance is poor, users can decide whether to upgrade their plan or switch ISPs.
- Planning for Businesses & Smart Homes → Ensuring strong connectivity for offices, IoT devices, and smart home systems.
  
**4️. Supporting Network Engineers & IT Professionals**
- Network Troubleshooting → Helps IT teams diagnose connectivity issues efficiently.
- Optimizing Public WiFi Networks → Useful for organizations providing public WiFi (cafes, malls, airports).
- Data-Driven Network Expansion → Helps telecom companies identify areas needing better coverage.

## Tools used for Analyzing

Here, we use 3 tools to help us to analyze the provider's detail and WiFi's quality, which are :

**- Network Cell Info**, to know to detail's of provider used

**- CellMap**, to know the location of BTS Tower of the provider

**- Wifi Analyzer**, to know the used WiFi's strength

## Step-by-Step
**0. Menggunakan **CellMap** untuk memastikan lokasi dari Tower BTS Terdekat**

   CellMap digunakan untuk memprakirakan lokasi Tower BTS terdekat dari suatu provider

**1. Melakukan analisis data seluler dengan **Network Cell Provider** di rumah**



   Dalam kasus ini, provider yang digunakan adalah XL-Axiata, Telkomsel, dan 3
   - **Rizky Ramadhan** : SIM 1 dengan operator 3 (Tri) memiliki RSRP sebesar -91 dBm, yang menunjukkan sinyal dalam kategori sedang. RSSNR bernilai 0.4 dB, yang sangat rendah, sehingga kemungkinan besar koneksi mengalami gangguan akibat noise yang tinggi. RSRQ memiliki nilai -17 dB, yang menandakan kualitas sinyal buruk. Secara keseluruhan, meskipun kekuatan sinyal cukup, kualitas jaringan kurang optimal dan bisa menyebabkan koneksi tidak stabil.
   - **M Rizki Febrian** : SIM 1 dengan operator XL memiliki RSRP sebesar -87 dBm, yang menunjukkan sinyal cukup baik. RSSNR bernilai 0.3 dB, yang tergolong sangat rendah, sehingga dapat menyebabkan gangguan koneksi. RSRQ berada di angka -12 dB, yang menunjukkan kualitas sinyal sedang. Secara keseluruhan, sinyal masih dapat digunakan dengan baik, tetapi kemungkinan terjadi gangguan akibat nilai RSSNR yang rendah.
   - **Fery Dwi Darmawan** : Informasi mengenai SIM 1 yang menunjukkan parameter kualitas sinyal jaringan LTE+ dari Provider 3 (Reference Signal Received Power) memiliki nilai -108 dBm, yang memunjukkan kekuatan sinyal yang terbilang lemah karena kecilnya nilai yang dipelihatkan dBm,  RSSNR (Reference Signal Signal-to-Noise Ratio) bernilai 15 dB, yang berarti bahwa daya sinyal referensi 15 dB lebih kuat dibandingkan noise di lingkungan tersebut. Semakin tinggi nilai RSSNR, semakin baik kualitas sinyal dan semakin besar kemungkinan untuk mendapatkan kecepatan data yang lebih tinggi dengan latensi yang lebih rendah.
   - **M Gavin Hawwari** : SIM 1 dengan operator Telkomsel memiliki RSRP sebesar -80 dBm, yang menunjukkan sinyal dalam kondisi baik. RSSNR bernilai 5.0 dB, yang cukup stabil untuk koneksi data, meskipun tidak terlalu tinggi. RSRQ berada di angka -11 dB, yang menunjukkan kualitas sinyal dalam kategori sedang. Secara keseluruhan, jaringan Telkomsel pada SIM 1 memiliki kekuatan sinyal yang baik dengan kualitas yang cukup stabil untuk digunakan.

**2. Melakukan analisis data seluler dengan **Network Cell Provider** di dekat tower BTS**



   Dalam kasus ini, provider yang digunakan adalah XL-Axiata, Telkomsel, dan 3
   - **Rizky Ramadhan** : Pada SIM 1, kualitas sinyal ditunjukkan oleh tiga parameter utama, yaitu RSRP, RSSNR, dan RSRQ. RSRP (Reference Signal Received Power) bernilai -74 dBm, yang menunjukkan sinyal cukup kuat karena berada dalam rentang yang masih baik untuk koneksi LTE (idealnya di atas -80 dBm). RSSNR (Reference Signal Signal-to-Noise Ratio) memiliki nilai 0.8, yang berarti terdapat sedikit noise dalam sinyal, tetapi masih bisa digunakan dengan cukup stabil (nilai ideal untuk koneksi lancar biasanya di atas 5 dB). Sementara itu, RSRQ (Reference Signal Received Quality) bernilai -11 dB, yang menandakan kualitas sinyal dalam kategori sedang, di mana semakin mendekati 0 dB semakin baik. Dengan kondisi ini, sinyal SIM 1 cukup baik untuk aktivitas internet dan komunikasi, meskipun bisa mengalami sedikit gangguan jika noise meningkat atau sinyal melemah.
   - **M Rizki Febrian** : Pada SIM 1, kualitas sinyal diukur menggunakan tiga parameter utama yaitu RSRP, RSSNR, dan RSRQ. RSRP bernilai -82 dBm, yang menunjukkan bahwa sinyal berada dalam kategori cukup baik untuk jaringan LTE, meskipun tidak terlalu kuat (nilai yang lebih tinggi, mendekati 0 dBm, lebih baik). RSSNR memiliki nilai 0.0, yang berarti sinyal mengalami gangguan noise yang cukup tinggi, sehingga dapat mempengaruhi stabilitas koneksi data. RSRQ tercatat -13 dB, yang menunjukkan kualitas sinyal dalam kategori kurang baik, karena semakin mendekati 0 dB semakin bagus. Dengan kondisi ini, meskipun kekuatan sinyal masih cukup memadai, gangguan noise yang tinggi dapat menyebabkan koneksi internet menjadi tidak stabil atau mengalami penurunan kecepatan.
   - **Fery Dwi Darmawan** : Informasi mengenai SIM 1 yang menunjukkan parameter kualitas sinyal jaringan LTE+ dari Provider 3 (Reference Signal Received Power) memiliki nilai -86 dBm, yang memunjukkan kekuatan sinyal yang terbilang cukup baik, walaupun tidak terlalu bagus. RSSNR (Reference Signal Signal-to-Noise Ratio) memiliki nilai 0.8, jarak terlalu jauh dari BTS, atau kondisi lingkungan buruk seperti berada di dalam gedung tebal atau area dengan banyak gangguan elektromagnetik. RSRQ (Reference Signal Received Quality) memiliki nilai -11 dB, menunjukkan kualitas sinyal yang sedang hingga kurang baik dalam jaringan seluler.
   - **M Gavin Hawwari** : Informasi mengenai SIM 1 menunjukkan parameter kualitas sinyal jaringan LTE+ dari operator Telkomsel. RSRP (Reference Signal Received Power) memiliki nilai -117 dBm, yang menunjukkan kekuatan sinyal yang lemah karena semakin kecil nilai dBm, semakin lemah sinyalnya. RSSNR (Reference Signal Signal-to-Noise Ratio) bernilai -1 dB, yang berarti rasio sinyal terhadap noise rendah dan dapat menyebabkan gangguan dalam komunikasi data. RSRQ (Reference Signal Received Quality) memiliki nilai -19 dB, yang menunjukkan kualitas sinyal yang buruk, karena semakin rendah nilainya, semakin buruk kualitas koneksi

**3. Melakukan analisis kualitas WiFi dengan **WiFi Analyzer** pada jarak yang cukup jauh**



   WiFi yang dianalisis yaitu WiFi @net-unsri-BB di Gedung Diploma Universitas Sriwijaya, dan Indihome di Rumah Gavin, serta di sekitar Kos Fery
   - **Rizky & Rizki** : WiFi dengan SSID @net-unsri-newBB (7c:57:3c:e1:8c:30) beroperasi pada frekuensi 5 GHz, dengan Channel 52 (58) dan frekuensi pusat 5260 MHz. Lebar kanalnya adalah 80 MHz, yang memungkinkan kecepatan transfer data lebih tinggi dibandingkan jaringan 2.4 GHz. Sinyal WiFi ini memiliki kekuatan -75 dBm, yang menunjukkan sinyal dalam kategori sedang hingga lemah. Perkiraan jarak dari sumber sinyal ke perangkat sekitar 25,5 meter.
   - **Gavin** : WiFi **Gavin2004** bekerja pada frekuensi **2.4 GHz**, menggunakan **Channel 8** dengan frekuensi pusat **2447 MHz** dan lebar kanal **20 MHz**. Sinyal tersebut terdeteksi dengan kekuatan -75 dBm, yang menunjukkan sinyal lemah tetapi masih bisa digunakan, dengan jarak sekitar 55 meter dari sumbernya. Selain itu, kecepatan koneksi yang ditampilkan adalah 19 Mbps, yang cukup untuk browsing dan streaming ringan tetapi mungkin mengalami gangguan jika terlalu jauh dari router atau ada banyak interferensi dari jaringan lain.
   - **Fery** :  Wifi **Delphinium** yang memiliki frekuens **2.4GHz**, menggunakan **Channel 9** lebar kanal **20 MHz**. Sinyal tersebut terdeteksi dengan kekuatan -76 dBm, yang menunjukkan sinyal dalam kategori sedang hingga lemah. Perkiraan jarak dari sumber sinyal ke perangkat sekitar 61 meter.

**4. Melakukan analisis kualitas WiFi dengan **WiFi Analyzer** pada jarak yang dekat dengan router**



   WiFi yang dianalisis yaitu WiFi @net-unsri-BB di Gedung Diploma Universitas Sriwijaya, dan Indihome di Rumah Gavin, serta di sekitar Kos Fery
   - **Rizky & Rizki** : Kekuatan sinyal yang terdeteksi sebesar -50 dBm, menunjukkan koneksi yang sangat baik karena perangkat berada dalam jarak dekat, sekitar 1.4 meter dari titik akses. 
   - **Gavin** : Kekuatan sinyal yang terdeteksi adalah **-46 dBm**, menunjukkan kualitas sinyal yang sangat baik karena perangkat penerima berada dalam jarak sekitar **2 meter** dari sumber WiFi. Dengan kualitas sinyal seperti ini, koneksi internet dari jaringan Gavin2004 kemungkinan besar stabil dan memiliki kecepatan yang optimal.
   - **Fery** :  Kekuatan sinyal yang terdeteksi sebesar -47 dBm, menunjukkan koneksi yang sangat baik karena perangkat berada dalam jarak dekat, sekitar 2 meter dari titik akses. 

