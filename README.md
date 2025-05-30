Proje Adı:
🔍 Google Trends Zaman Serisi Analizi: “AI” Tahmini

Amaç:
Google Trends’ten alınan “AI” kelimesine ait geçmiş arama ilgisini analiz ederek gelecek 20 haftayı tahmin etmek.

Adımlar:

pytrends ile son 1 yılın (haftalık) “AI” arama verisi çekildi.

Veriler görselleştirildi ve MinMaxScaler ile ölçeklendi.

LSTM modeli kullanılarak zaman serisi öğrenildi (time_step=20).

Modelin eğitim performansı grafikle değerlendirildi.

Son olarak gelecekteki 20 haftalık arama ilgisi tahmin edildi.