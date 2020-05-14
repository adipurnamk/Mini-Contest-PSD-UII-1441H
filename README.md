Langkah-langkah:

1. Mengimpor modul pandas untuk membaca file CSV
2. Membaca data.csv dengan fungsi pandas.read_csv, tetapkan sebagai df_data
3. Mengambil fitur df_data, berupa kolom Age, Total_Purchase, Account_Manager, Years dan Num_Sites, tetapkan sebagai X
4. Mengambil target data_df, yakni kolom Churn, tetapkan sebagai Y
5. Megimpor modul sklearn.model_selection untuk melakukan train_test_split, kemudian lakukan train_test_split
6. Megimpor modul sklearn.preprocessing untuk melakukan StandardScaler, kemudian lakukan StandardScaler pada X_train dan Y_train
7. Megimpor modul sklearn.linear_model untuk melakukan fitting model menggunakan fungsi LogisticRegression
8. Melakukan prediksi terhadap X_test
9. Megimpor modul sklearn.metrics untuk membuat confusion matriks menggunakan fungsi confusion_matrix
10. Kemudian cek akurasi model menggunakan fungsi accuracy_score dari modul sklearn.metrics  


11. Membaca test.csv dengan fungsi pandas.read_csv, tetapkan sebagai test_df
12. Mengambil feature test_df, berupa kolom Age, Total_Purchase, Account_Manager, Years dan Num_Sites, tetapkan sebagai X_test_df
13. Lakukan StandardScaler pada X_test_df
14. Prediksi data target, tetapkan hasilnya sebagai Y_pred_test_df
15. Buat kolom Churn pada test_df berisikan data dari Y_pred_test_df

---

Terima kasih kepada Bapak [Dhomas Hatta Fudholi](https://github.com/hattafudholi) yang sudah menyiapkan mini contestnya