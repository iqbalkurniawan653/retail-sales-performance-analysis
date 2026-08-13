# Retail Transaction Data Analysis & Business Insights

## Project Overview

Proyek ini menganalisis data transaksi penjualan ritel untuk memahami kondisi penjualan, kontribusi produk, karakteristik pelanggan, serta pola operasional berdasarkan informasi yang tersedia pada dataset.

Analisis dilakukan melalui Data Preparation, Variable Analysis, Relationship Analysis, dan Dashboard Development menggunakan Microsoft Excel dan Power BI.

## Objective

Analisis bertujuan untuk:

- Memahami performa penjualan dan profitabilitas
- Mengidentifikasi kontribusi setiap Product Category dan Region
- Memahami karakteristik pelanggan berdasarkan atribut yang tersedia
- Mengeksplorasi hubungan antara variabel penjualan, pelanggan, produk, dan operasional
- Menyajikan hasil analisis melalui interactive dashboard

## Dataset

Dataset yang digunakan merupakan Retail Transaction Dataset.

- Initial dataset: 4,310 transactions
- Final dataset: 4,200 transactions
- Data mencakup informasi mengenai order, customer, product, financial, shipping, payment method, customer satisfaction, dan return

## Tools

- Microsoft Excel
- Power Query
- Microsoft Power BI

## Analysis Process

### 1. Data Preparation

Data diperiksa melalui beberapa proses, meliputi:

- Missing Value Assessment
- Duplicate Data Assessment
- Data Type Validation
- Consistency Check
- Invalid Value Investigation
- Data Transformation
- Feature Engineering

Nilai yang tidak dapat ditentukan kembali secara akurat tidak diisi menggunakan asumsi dan tetap dipertahankan sebagai missing value agar hasil analisis tetap merepresentasikan informasi yang tersedia pada dataset.

### 2. Variable Analysis

Analisis dilakukan untuk memahami distribusi dan karakteristik variabel yang tersedia, baik numerical maupun categorical.

Beberapa aspek yang dianalisis meliputi:

- Customer characteristics
- Product Category
- Product Name
- Revenue
- Profit
- Profit Margin
- Quantity
- Region
- Payment Method
- Order Status
- Return Rate
- Customer Satisfaction
- Shipping information

### 3. Relationship Analysis

Relationship Analysis dilakukan untuk mengeksplorasi pola antarvariabel, termasuk:

- Revenue dan Product Category
- Revenue dan Region
- Revenue dan Age Group
- Profit Margin dan Discount Group
- Customer Satisfaction dan Return Rate
- Return Rate dan Product Category
- Shipping Time dan Order Status

Hasil relationship analysis digunakan sebagai dasar untuk menentukan informasi yang relevan untuk ditampilkan pada dashboard.

## Key Findings

- Dataset menghasilkan Total Revenue sebesar Rp264,27 juta dan Total Profit sebesar Rp49,52 juta dengan Profit Margin sebesar 18,74%
- Electronics merupakan Product Category dengan kontribusi Revenue dan Profit terbesar
- Electronics juga memiliki Return Rate yang relatif lebih tinggi dibandingkan kategori lainnya
- South merupakan Region dengan kontribusi Revenue tertinggi
- EMI merupakan Payment Method dengan kontribusi Revenue terbesar
- Customer Satisfaction yang lebih rendah cenderung disertai Return Rate yang lebih tinggi
- Beberapa transaksi memiliki Quantity yang sangat tinggi, termasuk nilai Quantity sebesar 999. Nilai tersebut tetap dipertahankan karena belum terdapat bukti yang cukup untuk memastikan bahwa nilai tersebut merupakan kesalahan pencatatan
- Perbedaan rata-rata Profit Margin antar Discount Group tidak menunjukkan pola yang kuat pada dataset yang dianalisis

## Dashboard

Dashboard dikembangkan menggunakan Microsoft Power BI dan terdiri dari empat halaman:

1. Executive Business Overview
2. Product Performance Analysis
3. Customer Analysis
4. Operational Performance

Dashboard menggunakan KPI, visualisasi perbandingan, tren, dan slicer interaktif dengan cross-page filtering.

### Executive Business Overview

Memberikan gambaran umum mengenai Revenue, Profit, Orders, Profit Margin, Return Rate, Product Category, Region, customer characteristics, dan return.

### Product Performance Analysis

Mengeksplorasi performa produk dan Product Category berdasarkan Revenue, Profit, Profit Margin, Quantity, serta Return Rate.

### Customer Analysis

Mengeksplorasi karakteristik pelanggan berdasarkan Age Group, Gender, Region, City, Payment Method, Customer Satisfaction, dan Return.

### Operational Performance

Mengeksplorasi Order Status, Shipping Time, Discount Level, Profit Margin, dan Return Rate.

## Conclusion

Secara keseluruhan, analisis memberikan gambaran mengenai kondisi penjualan, karakteristik pelanggan, performa produk, wilayah, dan aspek operasional berdasarkan data transaksi yang tersedia.

Electronics memberikan kontribusi Revenue dan Profit terbesar, namun juga memiliki Return Rate yang relatif lebih tinggi. Dari sisi wilayah, South memiliki kontribusi Revenue tertinggi, sedangkan pola Customer Satisfaction dan Return Rate menunjukkan kecenderungan bahwa tingkat kepuasan yang lebih rendah disertai Return Rate yang lebih tinggi.

Beberapa transaksi dengan Quantity yang sangat tinggi juga menjadi bagian penting dalam interpretasi performa penjualan karena dapat memengaruhi kontribusi Revenue dan Product Category.

## Business Recommendations

Beberapa area yang dapat menjadi perhatian lebih lanjut meliputi:

- Mengevaluasi performa Electronics dengan mempertimbangkan Revenue, Profit, Return Rate, dan transaksi bernilai tinggi secara bersamaan
- Memantau Return Rate bersama Customer Satisfaction
- Melakukan monitoring terhadap transaksi dengan nilai atau volume yang jauh lebih tinggi dibandingkan transaksi lainnya
- Mengevaluasi perbedaan performa antar Region
- Mempertahankan fleksibilitas Payment Method
- Mengevaluasi strategi diskon secara berkala berdasarkan Revenue, Profit, volume transaksi, dan tujuan promosi

## Project Documentation

Dokumentasi lengkap mengenai Data Preparation, Variable Analysis, Relationship Analysis, Dashboard Analysis, serta Conclusion & Business Recommendations tersedia pada:

#Documentation

[Documentation.pdf].(./documentation/Documentation.pdf)