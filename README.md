# Pendahuluan
Repository ini merupakan panduan dalam bahasa Indonesia untuk pembuatan program fuzzy logic controller menggunakan bahasa Python\
Contoh kode dapat dilihat di branch source_code dan principle_code

# Instalasi tool2 yang diperlukan

Saya menggunakan bahasa Python untuk membuat program ini, tata cara menginstall Python dapat dilihat [disini](https://www.python.org/downloads/)\
Setelah instalasi Python selesai, saatnya menginstall library2 Python yang akan dibutuhkan dengan mengetik command2 berikut di Command Prompt (Windows) atau Terminal (MacOS):
```
pip install numpy
```
Library `numpy` adalah kumpulan function perhitungan dasar untuk bahasa Python
```
pip install skfuzzy
```
Library `skfuzzy` adalah kumpulan function fuzzy logic untuk bahasa Python
```
pip install matplotlib
```
Library `matplotlib` digunakan untuk plotting hasil dalam bentuk visual (gambar)
```
pip install PyQt5
```
PyQt5 akan digunakan untuk membangun GUI program kita

# Mulai coding

Dimulai dari deklarasi universe dari variabel kita
