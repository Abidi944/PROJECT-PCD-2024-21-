# HASIL ANALISIS

Berdasarkan percobaan yang telah dilakukan untuk mengamati perbadaan tingkat akurasi dari model KNN untuk klasifikasi jenis mobil berdasarkan citra digitalnya yang telah mengalami proses preprocessing berupa edge detection yang berbeda yaitu dengan Sobel, Prewitt, Robert, Thinning, dan Morfologi Gradient. Dapat disimpulkan beberapa hal berikut:

1. Tingkat akurasi pada percobaan pertama untuk setiap metode berada di bawah 50%, hal tersebut terjadi karena preprocessing yang dilakukan tidak cukup untuk memudahkan model untuk menklasifikasikan citra jenis mobil.
2. Akurasi tertinggi pada percobaan pertama untuk setiap metode adalah pada percobaan dengan metode morfologi gradient dengan 38,4% karena citra hasil preprocessingnya lumayan bagus dan jelas sehingga memudahkan model dalam melakuakan klasifikasi. Sehingga dapat disimpulkan bahwa morfologi gradient adalah metode deteksi tepi terbaik dengan komposisi preprocessing dan jenis model machine learning yang digunakan.
3. Peningkatan akurasi dapat dilakukan dengan preprocessing seperti deteksi fitur dan pemilihan jenis model yang cocok sesuai dengan jenis dataset yang digunakan.