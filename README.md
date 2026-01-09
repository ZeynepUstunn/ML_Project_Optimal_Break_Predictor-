# 🚀 Optimal Break Predictor: Social Media vs. Productivity

Bu çalışma, sosyal medya kullanım alışkanlıklarının bireysel üretkenlik üzerindeki etkilerini analiz eden ve veri bilimi yöntemleriyle ideal mola sayısını tahmin eden bir **Makine Öğrenmesi** projesidir.

## 📝 Proje Hakkında
Bu proje, verimliliğin sadece rastgele bir sonuç değil, kontrol edilebilir değişkenlere bağlı bir disiplin olduğunu kanıtlamayı amaçlar. Veri seti üzerinden uyku süresi, çalışma saati ve sosyal medya kullanımı gibi parametreler incelenerek, "Üretken" sınıfına girmek için gerekli olan mola düzeni modellenmiştir.

## 👥 Proje Ekibi
Bu proje, veri analizi ve makine öğrenmesi süreçlerinin uçtan uca uygulanması amacıyla aşağıdaki ekip tarafından geliştirilmiştir:

Zeynep Üstün
Merve Çankaya
Uğur Özkan

## 🛠️ Kullanılan Teknolojiler
* **Dil:** Python 3.x
* **Kütüphaneler:**
    * `Pandas` & `NumPy` (Veri Manipülasyonu)
    * `Matplotlib` & `Seaborn` (Veri Görselleştirme)
    * `Scikit-Learn` (Makine Öğrenmesi)

## 🧠 Makine Öğrenmesi Yaklaşımı
Projede en doğru tahmini yapabilmek için dört farklı sınıflandırma algoritması karşılaştırılmıştır:

* **Random Forest Classifier:** Karmaşık veri örüntülerini yakalamak için.
* **Decision Tree Classifier:** Karar mekanizmalarını görselleştirmek için.
* **K-Nearest Neighbors (KNN):** Benzer kullanıcı davranışlarını gruplandırmak için.
* **Gaussian Naive Bayes:** Olasılıksal sınıflandırma analizi için.


### ⚙️ Model Optimizasyonu
* **Ölçeklendirme:** `StandardScaler` kullanılarak tüm özellikler aynı boyuta getirildi.
* **Hiperparametre Ayarı:** `GridSearchCV` ile modellerin en iyi çalışan versiyonları seçildi.
* **Değerlendirme:** Modeller `Confusion Matrix` ve `Classification Report` (Precision, Recall, F1-Score) ile test edildi.


## 📁 Dosya Yapısı
* `Project/ML_Project_Code.ipynb`: Veri ön işlemeden modelleme aşamasına kadar tüm kodlar.
* `social_media_vs_productivity.csv`: Analizde kullanılan veri seti.

## 📌 Temel Çıkarım (VİZYON)
> *"Bu yolculuk bize mola sayısının bir formülün sonucu değil, üretken insanlar tarafından bilinçli olarak uygulanan bir **disiplin** olduğunu gösterdi. Bu nedenle projemiz, kullanıcıya sadece geleceğini tahmin etmeyi değil, **nasıl daha başarılı olabileceğine dair bir hedef** sunmayı amaçlamaktadır."*

## 🚀 Kurulum ve Kullanım
1. Bu depoyu klonlayın.
2. Gerekli kütüphaneleri yükleyin: `pip install pandas seaborn scikit-learn matplotlib`
3. `ML_Project_Code.ipynb` dosyasını Jupyter Notebook veya VS Code üzerinden çalıştırın.
