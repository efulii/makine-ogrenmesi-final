# HIGGS Veri Seti — Makine Öğrenmesi Final Ödevi

Üsküdar Üniversitesi, Makine Öğrenmesi dersi final projesi.
HIGGS veri seti üzerinde özellik seçimi ve hiperparametre optimizasyonu.

## İçerik
- `ML_Final_Odevi.ipynb` — Tüm kodlar, çıktılar ve grafikler
- `HIGGS_ML_Rapor_APA7.docx` — APA 7 formatında rapor
- `roc_egrileri.png` — Model ROC eğrileri karşılaştırması
- `flowchart_A.png`, `flowchart_B.png` — Nested CV akış şemaları

## Yöntem Özeti
- Ön işleme: IQR ile aykırı değer kırpma + MinMaxScaler
- Özellik seçimi: Mutual Information ile en iyi 15 öznitelik
- Modelleme: Nested CV (dış 5-fold, iç 3-fold)
- Modeller: KNN, SVM, MLP, XGBoost

## Sonuç
En başarılı model: **XGBoost** (ROC-AUC 0.761 ± 0.005)

## Yazar
[Adınız Soyadınız]
