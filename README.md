# Banking-Marketing-SVM-Modelling

Bu proje, banka pazarlama kampanyalarının etkinliğini tahmin etmek amacıyla Destek Vektör Makineleri (SVM) kullanarak bir model geliştirmektedir. Model, bankaların mevcut pazarlama stratejilerinin başarı oranını tahmin etmek için kullanılabilecek bir araç sunmayı amaçlamaktadır.

## Proje İçeriği

Bu projede, Bank Marketing Dataset kullanılmıştır. Dataset, banka pazarlama kampanyalarında müşterilerin telefonla yapılan tekliflere yanıt verip vermediklerine dair veriler içermektedir.

## İçerik

Bankingmarketing.ipynb: Projenin ana Python kodu. Bu dosya, verilerin işlenmesi, modelin oluşturulması ve değerlendirilmesini içeren adımları kapsar.
Data: Dataset'in yer aldığı klasör (eğer projeye dahil edildiyse).

## Kullanılan Yöntemler
Veri Ön İşleme: Eksik verilerin işlenmesi, kategorik verilerin dönüştürülmesi ve veri temizliği.
Destek Vektör Makineleri (SVM): SVM algoritması ile sınıflandırma yapılmıştır.
Model Değerlendirme: Çeşitli değerlendirme metrikleri (doğruluk, doğruluk oranı, F1 skoru) kullanılarak modelin başarısı ölçülmüştür.

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır:

numpy
pandas
matplotlib
seaborn
scikit-learn

Projede yer alan tüm gereksinimler için aşağıdaki komut ile gerekli kütüphaneleri yükleyebilirsiniz:

```bash
pip install -r requirements.txt
```

## Kullanım

1. Bu projeyi bilgisayarınıza klonlayın:

```bash
git clone https://github.com/ecegny1/Banking-Marketing-SVM-Modelling.git
```

2. Gerekli kütüphaneleri yüklemek için requirements.txt dosyasını kullanın:
```bash
pip install -r requirements.txt
```

3. Ana notebook dosyasını çalıştırarak modelinizi oluşturabilirsiniz:
```bash
jupyter notebook bankingmarketing.ipynb
```

## Sonuçlar
Bu proje, banka pazarlama kampanyalarının başarısını tahmin etmek için etkili bir SVM modeli oluşturmuş ve sonuçların analizini sunmuştur.

