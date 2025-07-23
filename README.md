# 📝 Analisis Diskritisasi Diabetes

**Analisis Diskritisasi Data Diabetes dengan Python**  
Eksplorasi dataset diabetes menggunakan Pandas untuk diskritisasi data dengan metode equal-width dan equal-frequency.

---

## 📖 Deskripsi Proyek

**Analisis_Diskritisasi_Diabetes** adalah proyek pembelajaran Python yang berfokus pada analisis diskritisasi data pada dataset diabetes. Proyek ini mencakup:

- 📊 **Pemuatan dan Penampilan Data**: Menggunakan Pandas untuk memuat dan menampilkan dataset diabetes.
- 🔍 **Diskritisasi Equal-Width**: Membagi kolom *Glukosa* dan *Tekanan Darah* menjadi interval dengan lebar yang sama (RENDAH, NORMAL, TINGGI).
- 🔢 **Diskritisasi Equal-Frequency**: Membagi kolom *Glukosa* dan *Tekanan Darah* menjadi kelompok dengan jumlah data yang seimbang.
- 🧹 **Analisis Distribusi**: Menampilkan batas bin dan distribusi data hasil diskritisasi.

Proyek ini menggunakan Jupyter Notebook (`Diskritisasi_235314099.ipynb`) untuk analisis dan dataset (`diabetes.csv`).🟢

---

## 🧠 Teknologi

- Python 3.x
- Pandas
- Jupyter Notebook

---

## 📂 Struktur File

```
Analisis_Diskritisasi_Diabetes/
├── Diskritisasi_235314099.ipynb    # 📊 Notebook untuk analisis diskritisasi data diabetes
├── diabetes.csv                    # 📈 Dataset diabetes
```

---

## 📈 Contoh Output

**Diskritisasi_235314099.ipynb**

```
Batas Bin Equal-Width:
Batas Glukosa Equal-Width: [0.         66.33333333 132.66666667 199.       ]
Batas Tekanan Equal-Width: [0.         40.66666667 81.33333333 122.       ]

Batas Bin Equal-Frequency:
Batas Glukosa Equal-Frequency: IntervalIndex([(-0.001, 105.0], (105.0, 130.0], (130.0, 199.0]], dtype='interval[float64, right]')
Batas TekananDarah Equal-Frequency: IntervalIndex([(-0.001, 66.0], (66.0, 76.0], (76.0, 122.0]], dtype='interval[float64, right]')

Data yang Didiskritisasi (5 Baris Pertama):
    Glucose Glucose_EW Glucose_EF  BloodPressure BloodPressure_EW BloodPressure_EF
0       148     TINGGI     TINGGI             72           NORMAL          NORMAL
1        85     NORMAL     RENDAH             66           NORMAL          RENDAH
2       183     TINGGI     TINGGI             64           NORMAL          RENDAH
3        89     NORMAL     RENDAH             66           NORMAL          RENDAH
4       137     TINGGI     TINGGI             40           RENDAH          RENDAH

Distribusi Diskritisasi Equal-Width:
Distribusi Glukosa EW:
Glucose_EW
RENDAH     12
NORMAL    515
TINGGI    241
Name: count, dtype: int64

Distribusi TekananDarah EW:
BloodPressure_EW
RENDAH     40
NORMAL    563
TINGGI    165
Name: count, dtype: int64

Distribusi Diskritisasi Equal-Frequency:
Distribusi Glukosa EF:
Glucose_EF
RENDAH    264
NORMAL    253
TINGGI    251
Name: count, dtype: int64

Distribusi TekananDarah EF:
BloodPressure_EF
RENDAH    273
NORMAL    245
TINGGI    250
Name: count, dtype: int64
```

---

## 👨‍💻 Pengembang

**MBAHSINGO22**  
🔗 [GitHub](https://github.com/MBAHSINGO22)
