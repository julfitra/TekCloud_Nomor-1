# Teknologi Cloud 

## Containerd

Perusahaan pengembang teknologi kontainer (container) di sebuah layanan komputasi awan bernama Docker kini telah menawarkan sebuah solusi bernama Containerd. Containerd pada awalnya dibuat sebagai manajer runtime lapisan rendah untuk mesin Docker. Kasus penggunaan containerd terbesar adalah sebagai lapisan antara mesin Docker dan eksekutor runc OCI.  Containerd adalah sebuah runtime kontainer standar industri yang fokus pada kesederhanaan, ketahanan, dan portabilitas. Ini berarti ia adalah perangkat lunak yang bertanggung jawab untuk menjalankan kontainer. Karena containerd berfokus pada kasus penggunaan operasional, seperti menjalankan kontainer di server, maka ia mengelola siklus hidup kontainer secara lengkap dari sistem host-nya, mulai dari penyimpanan dan transfer image hingga eksekusi dan pengawasan kontainer. 

## Fungsi Utama Containerd

1. **Mengelola siklus hidup kontainer**: Dari mulai pembuatan, menjalankan, hingga menghentikan kontainer.

2. **Mengunduh dan membuka kemasan gambar kontainer**: Mendapatkan dan mempersiapkan gambar kontainer untuk dijalankan.

3. **Mengawasi kontainer**: Memantau kinerja dan status kontainer.

## Keuntungan Menggunakan Containerd
1. **Kinerja yang lebih baik**: Karena fokus pada inti fungsionalitas, containerd cenderung lebih cepat dan efisien daripada Docker.

2. **Portabilitas**: Dapat digunakan dengan berbagai platform dan sistem operasi.
Keamanan yang lebih baik: Dengan fokus pada keamanan, containerd membantu melindungi aplikasi Anda

