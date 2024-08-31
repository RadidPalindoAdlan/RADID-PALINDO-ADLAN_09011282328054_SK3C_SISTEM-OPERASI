## Tugas 1 instalasi linux

### 1. Persiapan Virtual Machine

- **Buat Nama dan Pilih Sistem Operasi**

  ![Langkah 1](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/1.png)

- **Konfigurasi Hardware**
  Modifikasi RAM dan CPU (jangan melewati batas hijau)
  
  ![Langkah 2](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/2.png)

- **Tambahkan Hard Disk Virtual**
 
  ![Langkah 3](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/3.png)

- **Finalisasi Pengaturan**
 
  ![Langkah 4](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/4.png)

### 2. Konfigurasi Display

- **Atur Display**
 
  ![Langkah 5](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/5.png)

### 3. Memulai Instalasi

- **Mulai Virtual Machine**
  
  ![Langkah 6](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/6.png)

- **Pilih "Install Linux Mint"**
  
  ![Langkah 7](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/7.png)

### 4. Proses Instalasi

- **Lanjutkan Instalasi**
  
  ![Langkah 8](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/8.png)
  ![Langkah 9](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/9.png)

- **Pilih Opsi Tambahan**
  Centang "Install multimedia codecs"
  
  ![Langkah 10](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/10.png)

- **Pilih Metode Instalasi**
  Klik "Something else" dan lanjutkan
  
  ![Langkah 11](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/11.png)

- **Konfigurasi Partisi**
  
  ![Langkah 12](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/12.png)

- **Konfirmasi Instalasi**
  
  ![Langkah 13](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/13.png)

### 5. Pengaturan Lokasi dan Pengguna

- **Pilih Lokasi (Jakarta)**
  
  ![Langkah 14](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/14.png)

- **Buat Username dan Password**
  
  ![Langkah 15](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/15.png)

### 6. Finalisasi

- **Tunggu Proses Instalasi Selesai**
  
  ![Langkah 16](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/16.png)

- **Restart Sistem**
  Klik "Restart now" setelah instalasi selesai
  
  ![Langkah 17](https://github.com/RadidPalindoAdlan/RADID-PALINDO-ADLAN_09011282328054_SK3C_SISTEM-OPERASI/blob/main/17.png)

<h>

## Tugas 2

### 1. Mengapa Memilih "/" sebagai Mount Point?

Memilih `"/"` sebagai opsi Mount Point saat instalasi sangat penting karena:

- `"/"` adalah root directory atau direktori akar dari seluruh sistem file di Linux.
- Ini adalah dasar dari struktur file sistem, di mana semua direktori dan file lainnya berada.
- Tanpa menetapkan `"/"` sebagai mount point, sistem operasi tidak akan tahu di mana harus menginstal file sistem.
- Memastikan ruang disk dialokasikan dengan benar untuk semua file penting.
- Membantu menjaga keamanan dan stabilitas sistem dengan memisahkan file sistem dari data lainnya.

### 2. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs !

| Sistem File | Deskripsi |
|-------------|-----------|
| **ext4**    | - Penerus dari ext3<br>- Peningkatan performa<br>- Ukuran file maksimal: 16TB<br>- Ukuran volume: 1EB |
| **ext3**    | - Sistem file Linux<br>- Ukuran file maksimal: 2TB<br>- Ukuran volume: 32TB |
| **swap**    | - Bukan sistem file<br>- Ruang disk untuk memori virtual<br>- Membantu RAM saat penuh |
| **ntfs**    | - Sistem file Windows<br>- Ukuran file dan volume maksimal: 16EB |
| **fat32**   | - Sistem file sederhana<br>- Ukuran file maksimal: 4GB<br>- Ukuran volume maksimal: 2TB |
| **btrfs**   | - Sistem file Linux modern<br>- Fitur: snapshot, subvolume<br>- Ukuran volume maksimal: 16EB |
