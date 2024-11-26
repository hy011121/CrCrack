![tenor](https://github.com/user-attachments/assets/9347a13f-a49a-4b77-9c12-c71ae19984a6)

This script is a tool to brute force or crack a specific account using the provided proxy and combolist. The process is done in parallel with many threads, allowing users to send a large number of requests to the target server without consuming too much time. In order for this script to run optimally, users must prepare two main files, namely **proxy** and **combolist**.

**Proxy** is a list of IP addresses that can be used to send requests without revealing the original IP address. This proxy file must contain one IP address per line, followed by its port, for example `192.168.1.1:8080`. The main purpose of using a proxy is to avoid IP blocking by the target server, which can happen if too many requests come from one IP in a short time. The proxy will be used randomly each time a request is sent, ensuring that the script remains anonymous.

**Combolist**, on the other hand, is a file that contains a list of username and password combinations that will be tried to log in. The standard format for this file is one combination per line, with the format username:password, for example `user123:password123`. This script will try every combination of the combolist on the target account specified in the script. Make sure the combolist used is not too large to avoid very long processing times.

With these two files prepared, you can simply run the script with the right configuration, and the tool will start sending requests automatically. For more effective results, you can adjust the number of threads and proxies used in the script.

---
Script ini adalah alat untuk melakukan brute force atau crack pada akun tertentu dengan menggunakan proxy dan combolist yang disediakan. Prosesnya dilakukan secara paralel dengan banyak thread, yang memungkinkan pengguna untuk mengirimkan permintaan dalam jumlah besar ke server target tanpa terlalu banyak mengonsumsi waktu. Agar script ini berjalan dengan optimal, pengguna harus menyiapkan dua file utama, yaitu **proxy** dan **combolist**.

**Proxy** adalah daftar alamat IP yang dapat digunakan untuk mengirimkan permintaan tanpa mengungkapkan alamat IP asli. File proxy ini harus berisi satu alamat IP per baris, diikuti dengan portnya, misalnya `192.168.1.1:8080`. Tujuan utama penggunaan proxy adalah untuk menghindari pemblokiran IP oleh server target, yang dapat terjadi jika terlalu banyak permintaan datang dari satu IP dalam waktu singkat. Proxy akan digunakan secara acak setiap kali permintaan dikirim, memastikan bahwa script tetap anonim.

**Combolist**, di sisi lain, adalah file yang berisi daftar kombinasi username dan password yang akan dicoba untuk login. Format standar untuk file ini adalah satu kombinasi per baris, dengan format username:password, misalnya `user123:password123`. Script ini akan mencoba setiap kombinasi dari combolist tersebut pada akun target yang ditentukan dalam script. Pastikan combolist yang digunakan tidak terlalu besar untuk menghindari waktu pemrosesan yang sangat lama.

Dengan dua file ini disiapkan, Anda cukup menjalankan script dengan konfigurasi yang tepat, dan alat ini akan mulai mengirimkan permintaan secara otomatis. Untuk hasil yang lebih efektif, Anda bisa menyesuaikan jumlah thread dan proxy yang digunakan dalam script.
