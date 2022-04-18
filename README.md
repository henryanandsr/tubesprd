# tubesprd
Graph Based Web Search

Menggunakan fuzzy string matching dan word-clustering untuk menentukan relevansi antara input dengan data-data pada database database_judul.csv

# How to Use
Instalasi Fuzzy

pip install thefuzz

pip install python-Levenshtein

restart python dan close IDE supaya take effect

## Untuk menjalankan
Masukkan 2 kata (seperti contoh di bawah ini) lalu lihat hasilnya.

# Input Examples
Beberapa contoh input dan output dari program ini

**makan apel** -> Khasiat Makan Apel Setiap Hari

**makan buah** -> Efek Makan Pisang untuk kesehatan; Khasiat Makan Apel Setiap Hari

**apple fruit** -> Khasiat Makan Apel Setiap Hari; Cara memasak pai apple

**apel sma** -> Apel pagi di SMAN; Presiden memimpin apel di SMA 
