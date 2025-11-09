# ❌🅾️ Tic-Tac-Toe AI (Minimax dengan Alpha-Beta Pruning)

Proyek ini adalah implementasi klasik permainan Tic-Tac-Toe (X/O) melawan komputer menggunakan Python. Komputer dirancang untuk bermain secara **optimal** (tidak terkalahkan) berkat penerapan algoritma pencarian kecerdasan buatan, yaitu **Minimax** dengan optimasi **Alpha-Beta Pruning**.

Karena Minimax adalah algoritma sempurna untuk permainan zero-sum seperti Tic-Tac-Toe, komputer akan selalu mencapai hasil terbaik: menang jika mungkin, atau seri jika pemain manusia bermain sempurna.

## ✨ Fitur Utama

* **Pemain Tunggal:** Bermain melawan komputer (AI).
* **Optimal Play:** Komputer menggunakan algoritma **Minimax** untuk memilih langkah terbaik, menjamin hasil maksimal (menang atau seri).
* **Efisiensi:** Menggunakan **Alpha-Beta Pruning** untuk mengurangi jumlah langkah yang harus dipertimbangkan oleh AI, membuat keputusan langkah komputer instan.
* **Antarmuka Konsol:** Permainan berjalan sepenuhnya melalui *command line* atau *terminal*.

## ⚙️ Persyaratan (Requirements)

Proyek ini hanya membutuhkan instalasi dasar Python.

* **Python 3.x**
* Modul standar Python: `math`, `random`.

## 🚀 Cara Menjalankan

Anda dapat menjalankan skrip ini di lingkungan Python apa pun, termasuk Google Colab (seperti yang ditunjukkan dalam *notebook* asli).

### 1. Lokal (Terminal/Command Prompt)

1.  Simpan kode program di atas sebagai file bernama, misalnya, `tictactoe_minimax.py`.
2.  Buka terminal atau *command prompt*, navigasikan ke direktori tempat file disimpan.
3.  Jalankan skrip menggunakan Python:

    ```bash
    python tictactoe_minimax.py
    ```

### 2. Google Colab (atau Jupyter Notebook)

1.  Buka *notebook* Colab/Jupyter.
2.  Salin dan tempelkan seluruh kode Python ke dalam sel kode.
3.  Jalankan sel kode tersebut.

## 🕹️ Cara Bermain

1.  Anda akan bermain sebagai **'X'** dan Komputer akan bermain sebagai **'O'**.
2.  Permainan akan menampilkan papan yang diperbarui dan meminta input langkah Anda.
3.  Masukkan **angka 1 sampai 9** untuk memilih posisi kosong pada papan, sesuai dengan peta posisi berikut:

| 1 | 2 | 3 |
|---|---|---|
| 4 | 5 | 6 |
| 7 | 8 | 9 |

4.  Tekan **Enter** dan
