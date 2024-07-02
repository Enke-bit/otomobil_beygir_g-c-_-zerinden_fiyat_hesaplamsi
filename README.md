# Regresyon Modelleri Karşılaştırması
Bu proje, çeşitli regresyon modellerini kullanarak bir hedef değişkeni tahmin etmeyi ve bu modellerin performansını karşılaştırmayı amaçlar. Veri seti, makine gücü ve fiyatla ilgili özellikleri içerir.

## Kullanılan Modeller
Aşağıdaki regresyon modelleri kullanılmış ve değerlendirilmiştir:

- Doğrusal Regresyon (LR)
- Ridge Regresyon (Ridge)
- Lasso Regresyon (Lasso)
- Karar Ağacı (DT)
- Rastgele Orman (RF)
- Gradient Boosting (GB)
- Destek Vektör Regresyonu (SVR)
- K-En Yakın Komşu (KNN)
- Veri Seti
- Veri setinde aşağıdaki sütunlar bulunmaktadır:

KekuatanMesin (Makine Gücü)
Harga (Fiyat)
## Sonuçlar
Her modelin performansı aşağıdaki metrikler kullanılarak değerlendirilmiştir:

- Ortalama Kare Hata (MSE)
- Kök Ortalama Kare Hata (RMSE)
- Ortalama Mutlak Hata (MAE)
- R^2 Skoru

## Elde Edilen Sonuçlar
### Doğrusal Regresyon (LR):

- MSE: 4442.55
- RMSE: 66.65
- MAE: 46.79
- R^2: 0.65

### Ridge Regresyon (Ridge):

- MSE: 4442.57
- RMSE: 66.65
- MAE: 46.79
- R^2: 0.65

### Lasso Regresyon (Lasso):

- MSE: 4442.76
- RMSE: 66.65
- MAE: 46.79
- R^2: 0.65

### Karar Ağacı (DT):

- MSE: 2529.23
- RMSE: 50.29
- MAE: 30.35
- R^2: 0.80

### Rastgele Orman (RF):

- MSE: 2307.78
- RMSE: 48.04
- MAE: 28.22
- R^2: 0.82

### Gradient Boosting (GB):

- MSE: 2623.94
- RMSE: 51.22
- MAE: 31.55
- R^2: 0.79

### Destek Vektör Regresyonu (SVR):

- MSE: 5899.78
- RMSE: 76.81
- MAE: 47.93
- R^2: 0.53

### K-En Yakın Komşu (KNN):

- MSE: 3116.53
- RMSE: 55.83
- MAE: 35.69
-R^2: 0.75

### Rastgele Orman (RF):
- MSE: 2307.78
- RMSE: 48.04
- MAE: 28.22
- R^2: 0.82

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Ayrıntılar için LICENSE dosyasına bakınız.

