import pandas as pd

df = pd.read_csv('ogrenci_veriseti_500.csv')

print("--- İlk 5 Satır ---")
print(df.head())


print("\n--- Sütun Başına Eksik Veri Sayısı ---")
print(df.isna().sum())


print("\n--- İstatistiksel Özet ---")
print(df.describe())
