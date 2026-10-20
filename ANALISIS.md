# Analisis Kemiskinan Indonesia

## Tujuan
Mengeksplorasi perbedaan tingkat kemiskinan antarwilayah serta keterkaitannya dengan indikator pembangunan.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn; HTML, CSS dan JavaScript untuk dashboard.

## Cakupan
516 observasi, 514 kombinasi nama kabupaten/kota unik, 34 provinsi. Tahun pengamatan dan sumber primer belum dicantumkan dalam notebook.

## Temuan keseluruhan
- Rata-rata kemiskinan antarobservasi: 10,78%; median: 7,53%. Ini bukan angka kemiskinan nasional berbobot penduduk.
- Rata-rata Papua: 27,09%; Bali: 3,40%; selisih 23,69 poin persentase.
- Korelasi kemiskinan dengan IPM: -0,535; sanitasi: -0,475. Korelasi tidak membuktikan sebab-akibat.
- 66 observasi (12,8%) memiliki kemiskinan di atas 20%.
- 164 observasi memiliki kemiskinan di atas median dan IPM di bawah median dataset.

## Proses
532 baris awal; 16 duplikat identik dihapus. Format desimal dinormalisasi. 15 nilai kosong pada IPM, UHH, Sanitasi dan AirMinum diisi median. Satu nilai kemiskinan >100% diganti median. Outlier lain dipertahankan.

## Batasan
Dua pasangan wilayah (Dharmasraya, Sumatera Barat; Kota Medan, Sumatera Utara) masih memiliki dua baris berbeda. Beberapa nilai ekstrem dan pola desimal perlu diverifikasi terhadap sumber primer. Analisis bersifat eksploratif; belum mendukung kesimpulan kausal atau penetapan kebijakan.

## Tindak lanjut yang dapat diuji
Validasi tahun, sumber primer, unit pengeluaran, dan identitas wilayah; periksa kemungkinan salah konversi angka; lalu uji ulang hubungan indikator dan, jika data penduduk tersedia, hitung agregat berbobot.

Sumber: Kemiskinan (3).ipynb, dataset_kemiskinan_clean (1).csv.
SHA-256 CSV: 8ebbcf63e8b6c7f37705f400a787838df5bf4cbcba4b0ebb09a1ef8cab16c9d1
