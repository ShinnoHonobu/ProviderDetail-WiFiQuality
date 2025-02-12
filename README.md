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
0. Menggunakan **CellMap** untuk memastikan lokasi dari Tower BTS Terdekat

   CellMap digunakan untuk memprakirakan lokasi Tower BTS terdekat dari suatu provider

2. Melakukan analisis data seluler dengan **Network Cell Provider** di rumah

   Dalam kasus ini, provider yang digunakan adalah XL-Axiata, Telkomsel, dan 3

3. Melakukan analisis data seluler dengan **Network Cell Provider** di dekat tower BTS

   Dalam kasus ini, provider yang digunakan adalah XL-Axiata, Telkomsel, dan 3
   - Rizky Ramadhan : Pada SIM 1, kualitas sinyal ditunjukkan oleh tiga parameter utama, yaitu RSRP, RSSNR, dan RSRQ. RSRP (Reference Signal Received Power) bernilai -74 dBm, yang menunjukkan sinyal cukup kuat karena berada dalam rentang yang masih baik untuk koneksi LTE (idealnya di atas -80 dBm). RSSNR (Reference Signal Signal-to-Noise Ratio) memiliki nilai 0.8, yang berarti terdapat sedikit noise dalam sinyal, tetapi masih bisa digunakan dengan cukup stabil (nilai ideal untuk koneksi lancar biasanya di atas 5 dB). Sementara itu, RSRQ (Reference Signal Received Quality) bernilai -11 dB, yang menandakan kualitas sinyal dalam kategori sedang, di mana semakin mendekati 0 dB semakin baik. Dengan kondisi ini, sinyal SIM 1 cukup baik untuk aktivitas internet dan komunikasi, meskipun bisa mengalami sedikit gangguan jika noise meningkat atau sinyal melemah.
   - M Rizki Febrian : Pada SIM 1, kualitas sinyal diukur menggunakan tiga parameter utama yaitu RSRP, RSSNR, dan RSRQ. RSRP bernilai -82 dBm, yang menunjukkan bahwa sinyal berada dalam kategori cukup baik untuk jaringan LTE, meskipun tidak terlalu kuat (nilai yang lebih tinggi, mendekati 0 dBm, lebih baik). RSSNR, yang berarti sinyal mengalami gangguan noise yang cukup tinggi, sehingga dapat mempengaruhi stabilitas koneksi data. RSRQ tercatat -13 dB, yang menunjukkan kualitas sinyal dalam kategori kurang baik, karena semakin mendekati 0 dB semakin bagus. Dengan kondisi ini, meskipun kekuatan sinyal masih cukup memadai, gangguan noise yang tinggi dapat menyebabkan koneksi internet menjadi tidak stabil atau mengalami penurunan kecepatan.
   - Fery Dwi Darmawan :
   - M Gavin Hawwari : Informasi mengenai SIM 1 menunjukkan parameter kualitas sinyal jaringan LTE+ dari operator Telkomsel. RSRP (Reference Signal Received Power) memiliki nilai -117 dBm, yang menunjukkan kekuatan sinyal yang lemah karena semakin kecil nilai dBm, semakin lemah sinyalnya. RSSNR (Reference Signal Signal-to-Noise Ratio) bernilai -1 dB, yang berarti rasio sinyal terhadap noise rendah dan dapat menyebabkan gangguan dalam komunikasi data. RSRQ (Reference Signal Received Quality) memiliki nilai -19 dB, yang menunjukkan kualitas sinyal yang buruk, karena semakin rendah nilainya, semakin buruk kualitas koneksi

5. Melakukan analisis kualitas WiFi dengan **WiFi Analyzer** pada jarak yang cukup jauh

   WiFi yang dianalisis yaitu WiFi @net-unsri-BB di Gedung Diploma Universitas Sriwijaya, dan 

6. Melakukan analisis kualitas WiFi dengan **WiFi Analyzer** pada jarak yang dekat dengan router

   WiFi yang dianalisis yaitu WiFi @net-unsri-BB di Gedung Diploma Universitas Sriwijaya, dan
