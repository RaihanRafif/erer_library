# erer_lib 📖
**erer_lib** adalah aplikasi berbasis Android yang membantu pengguna menghafalkan kosakata. Aplikasi ini memungkinkan pengguna menambahkan kosakata berdasarkan negara, arti, kategori kata, dan contoh kalimat, serta memiliki fitur pengujian hafalan kosakata dalam bentuk pilihan ganda. Selain itu, pengguna dapat mengekspor data kosakata ke dalam file PDF atau JSON, serta memanfaatkan widget untuk menampilkan kosakata di layar utama perangkat.

## Fitur Utama 🚀
1. **Menambahkan Kosakata**: Pengguna dapat menambahkan kosakata beserta arti, kategori kata, dan contoh kalimat, serta memilih negara asal kosakata.
2. **Mengimpor Data JSON**: Pengguna dapat mengupdate data dari file JSON ke dalam database lokal aplikasi.
3. **Ekspor Data**: Fitur untuk mengekspor kosakata yang telah ditambahkan menjadi file PDF atau JSON.
4. **Uji Hafalan Kosakata**: Fitur kuis pilihan ganda yang dapat difilter berdasarkan negara, kategori, dan waktu penambahan kosakata.
5. **Widget Kosakata**: Widget yang dapat ditampilkan di layar utama perangkat untuk menampilkan kosakata secara bergantian setiap 5 menit.
6. **Tema**: Aplikasi mendukung tema light, dark, atau mengikuti pengaturan sistem.

## Teknologi yang Digunakan 🛠
- **React Native**: Untuk pengembangan aplikasi mobile.
- **SQLite/Realm**: Untuk penyimpanan data kosakata secara lokal.
- **React Native AsyncStorage**: Untuk penyimpanan preferensi pengguna, seperti tema dan pengaturan lainnya.
- **react-native-html-to-pdf**: Untuk mengekspor kosakata ke dalam format PDF.
- **react-native-fs**: Untuk mengakses sistem file lokal perangkat dan mengelola ekspor JSON/PDF.
- **Redux/Context API**: Untuk manajemen state di seluruh aplikasi.
- **React Native Widgets**: Untuk menampilkan widget kosakata di layar utama perangkat.

## Instalasi ⚙️
### 1. Clone Repository
```bash
git clone https://github.com/username/erer_lib.git
cd erer_lib
