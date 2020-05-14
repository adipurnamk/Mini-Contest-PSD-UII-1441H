1. Mengimpor library pandas untuk membaca file CSV
2. Membaca data.csv dengan fungsi pandas.read_csv, tetapkan sebagai df_data
3. Mengambil feature df_data, berupa kolom Age, Total_Purchase, Account_Manager, Years dan Num_Sites, tetapkan sebagai X
4. Mengambil target df_data, yakni kolom Churn, tetapkan sebagai Y
5. Megimpor library sklearn.model_selection untuk melakukan train_test_split, kemudian lakukan train_test_split
6. Megimpor library sklearn.preprocessing untuk melakukan StandardScaler, kemudian lakukan StandardScaler pada X_train dan Y_train
7. Megimpor library sklearn.linear_model untuk melakukan fitting model menggunakan fungsi LogisticRegression
8. Melakukan prediksi terhadap X_test
9. Kemudian cek akurasi menggunakan fungsi accuracy_score dari library sklearn.metrics
10. Menggunakan fungsi f1_score dari library sklearn.metrics, cek f1 score antara data target dari df_data dengan Y dari hasil prediksi feature df_data

11. Membaca test.csv dengan fungsi pandas.read_csv, tetapkan sebagai test_df
12. Mengambil feature test_df, berupa kolom Age, Total_Purchase, Account_Manager, Years dan Num_Sites, tetapkan sebagai X_test_df
13. Lakukan StandardScaler pada X_test_df
14. Prediksi data target, tetapkan hasilnya sebagai Y_pred_test_df
15. Buat kolom Churn pada test_df berisikan data dari Y_pred_test_df# Mini Contest-PSD UII 1441H
 klasifikasi data dengan logistic regression
