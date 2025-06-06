## GROWTH: Greenhouse Remote Operations With Temperature & Humidity

![Logo GROWTH](https://github.com/MHaniifan/GROWTH/blob/main/Assets/Banner%20GROWTH.jpg)

<div align="justify">
    Proyek ini bertujuan untuk mengembangkan sistem automasi cerdas berbasis Mikrokontroler AVR untuk Smart Farming, menggunakan komponen utama seperti Arduino Mega, sensor YL-69 dan DHT-11, serta pompa air dan kipas. Arduino Mega bertindak sebagai mikrokontroler utama yang mengontrol komunikasi antar sensor dan aktuator, memungkinkan pemantauan dan pengontrolan secara real-time. Sistem ini menggunakan Timer pada AVR untuk menjaga sinkronisasi waktu, dan Interrupt untuk menyalakan Pompa Air ketika kelembaban dibawah batas.
</div>

<div align="justify">
    Pompa Air akan menyala setiap jadwal penyiraman yang sudah ditentukan. Dimana jadwal penyiraman dan lama pompa menyala, diatur pada GUI pada Komputer yang terhubung ke Mikrokontroler menggunakan komunikasi UART. Untuk Kipas akan menyala setiap suhu telah melewati batas yang ditentukan, dimana batas suhunya dapat diatur pada GUI.
</div>

<div align="justify">
    Dengan menggunakan UART, seluruh data dari sensor-sensor ini dikirimkan ke Komputer. Memungkinkan petani untuk memantau penggunaan energi dan kondisi lingkungan secara langsung dari Komputer. Sistem ini dirancang untuk meningkatkan efisiensi energi, hasil produksi, serta dapat mengurangi kerugian dengan mengotomatiskan berbagai fungsi dan memberikan kendali yang lebih fleksibel.
</div>

## Supported By :
>- Dosen Pengampu : Akhmad Hendriawan ST., MT. (NIP.197501272002121003)
>- Mata kuliah : Mikrokontroler
>- Program Studi : Sarjana Terapan Teknik Elektronika
>- Politeknik Elektronika Negeri Surabaya<br> 

## Team Member :
|      NRP      |       Nama      |    Jobdesk    |   Github |
| :-----------:|:----------------:| :------------:| :-----:|
| 2123600007    | Muhammad Haniifan  | Project Manager       | [Haniifan](https://github.com/MHaniifan)
| 2123600011    | Monalisa Br. Sidauruk         |   Hardware Specialist | [Lisa](https://github.com/MonalisaSidauruk)
| 2123600015    | Fakhrihans Ardiyanto         |    UI/UX Designer      | [Rihan](https://github.com/FakhrihansArdiyanto)
| 2123600027    | Darda Drestanala                | 3D Designer | [Darda](https://github.com/dardadrestanala)
| 2123600029    | Aurora Putri Salsabillah Rofii               | PCB Designer     | [Aurora](https://github.com/aurorapsr)
| 2124640016    | Arif Ramadhan               | Programmer     |[Arif](https://github.com/arif-rmdhn)

##
![Flyer GROWTH](https://github.com/MHaniifan/GROWTH/blob/main/Assets/Flyer%20GROWTH.png)

## Daftar Isi
- [Deskripsi Project](https://github.com/MHaniifan/GROWTH#growth-greenhouse-remote-operations-with-temperaturehumidity)
- [Team Member](https://github.com/MHaniifan/GROWTH#team-member-)
- [Keunggulan](https://github.com/MHaniifan/GROWTH#keunggulan)
- [Desain Hardware](https://github.com/MHaniifan/GROWTH#desain-hardware)
- [Printed Circuit Board](https://github.com/MHaniifan/GROWTH#printed-circuit-board-pcb)
- [Program](https://github.com/MHaniifan/GROWTH#program)
- [Tampilan UI/UX](https://github.com/MHaniifan/GROWTH#tampilan-uiux)

## Keunggulan
- **Pemantauan Real-Time**: Mengukur perubahan kelembaban dan suhu dengan sensor secara terus - menerus.
- **Efisiensi dan Penghematan Biaya**: Mengurangi penggunaan listrik karena pompa dan kipas hanya dinyalakan ketika melewati batas normal tanaman.
- **Kendali Otomatis**: Menggunakan sensor untuk mengamati perubahan kondisi dan relay untuk mengaktifkan pompa dan kipas sehingga tidak dikontrol oleh manusia.
- **Meningkatkan Hasil Panen**: Mencegah tanaman kekeringan dan kepanasan sehingga dapat meningkatkan kondisi tanaman.

## Desain Hardware
Blok Diagram
![Diagram Blok GROWTH](https://github.com/MHaniifan/GROWTH/blob/main/Hardware/Diagram%20Blok%20GROWTH.png)

Wiring Diagram
![Wiring GROWTH](https://github.com/MHaniifan/GROWTH/blob/main/Hardware/Wiring%20GROWTH.png)

## Printed Circuit Board (PCB)
Skematik PCB
![Skematik PCB GROWTH](https://github.com/MHaniifan/GROWTH/blob/main/Hardware/Skematik%20PCB%20GROWTH.jpg)

Desain PCB
![Desain PCB GROWTH](https://github.com/MHaniifan/GROWTH/blob/main/Hardware/Desain%20PCB%20GROWTH.png)

## Desain 3D
![Desain 3D GROWTH](https://github.com/MHaniifan/GROWTH/blob/main/3D%20Design/Desain%203D%20GROWTH.png)

## Flowchart Program
<img src="https://github.com/MHaniifan/GROWTH/blob/main/Assets/Flowchart%20GROWTH.png" alt="Flowchart GROWTH" width="300">

## Tampilan UI/UX
![Desain UI GROWTH](https://github.com/MHaniifan/GROWTH/blob/main/UI%20UX%20Design/Desain%20UI%20GROWTH.jpg)

## Pengembangan Kedepannya
- Penambahan IoT untuk Pemantauan Jarak Jauh
- Penambahan RTC untuk Penjadwalan Penyiraman
- Penambahan Desain Casing yang Tahan Air
- Penambahan Baterai untuk Supply Darurat