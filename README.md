import pandas as pd

# CSV dosyasını okuma
df = pd.read_csv('ogrenci_veriseti_500.csv')

# 1. Veri setinin ilk 5 satırına göz atın
print("--- İlk 5 Satır ---")
print(df.head())

# 2. Hangi sütunda kaç tane eksik (NaN) değer olduğunu tespit edin
print("\n--- Sütun Başına Eksik Veri Sayısı ---")
print(df.isna().sum())

# 3. Temel istatistiksel özet
print("\n--- İstatistiksel Özet ---")
print(df.describe())
