# Kalp Hastalığı Tahmini Projesi
Bu projede, kalp hastalığı tahmini için makine öğrenmesi teknikleri kullanılarak hem gözetimli öğrenme hem de gözetimsiz öğrenme modelleri uygulanmıştır. Farklı veri ön işleme adımları, modelleme yaklaşımları ve performans değerlendirme metrikleri bu projede yer almaktadır.

# Proje İçeriği
Veri Seti: Bu veri seti, [https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease]'den alınmıştır. Veri seti kalp hastalığı ve bireysel sağlık özellikleri ile ilgili çeşitli değişkenleri içermektedir.
</br> Amaç: Bu projenin amacı, kalp hastalığı riskini tahmin eden bir makine öğrenmesi modeli geliştirmektir.
Model Türleri: Hem gözetimli hem de gözetimsiz öğrenme algoritmaları kullanılarak modelleme yapılmıştır.
# Veri Seti
Veri seti aşağıdaki değişkenlerden oluşmaktadır:

HeartDisease: Kalp Hastalığı (No, Yes)</br>
BMI: Vücut Kitle İndeksi (Sürekli)</br>
Smoking: Sigara İçme (No, Yes)</br>
AlcoholDrinking: Alkol Kullanımı (No, Yes)</br>
Stroke: İnme (No, Yes)</br>
PhysicalHealth: Fiziksel Sağlık (Kesikli)</br>
MentalHealth: Zihinsel Sağlık (Kesikli)</br>
DiffWalking: Yürüme Zorluğu (No, Yes)</br>
Sex: Cinsiyet (Female, Male)</br>
AgeCategory: Yaş Kategorisi</br>
Race: Irk</br>
Diabetic: Diyabet Hastası (Yes, No, Borderline, Gebelikte)</br>
PhysicalActivity: Fiziksel Aktivite (No, Yes)</br>
GenHealth: Genel Sağlık (Very Good, Fair, Good, Poor, Excellent)</br>
SleepTime: Uyku Süresi (Kesikli)</br>
Asthma: Astım (No, Yes)</br>
KidneyDisease: Böbrek Hastalığı (No, Yes)</br>
SkinCancer: Cilt Kanseri (No, Yes)</br>
# Veri Ön İşleme
Kategorik değişkenlerin one-hot encoding label-enconding ve ordinal-encoding ile dönüştürülmesi</br>
Feature scaling (StandardScaler)</br>
Veri dengesizliğini gidermek için SMOTE kullanılması</br>
# Kullanılan Modeller
Gözetimli Öğrenme Modelleri:</br>
Logistic Regression</br>
Random Forest</br>
K-Nearest Neighbors (KNN)</br>
XGBClassifier</br>
ExtraTreesClassifier</br>
Gözetimsiz Öğrenme Modelleri:</br>
K-Means</br>
DBSCAN</br>
# En İyi Model </br>
En iyi performans gösteren model RandomForestClassifier olmuştur. Yüksek Accuracy, Precision, Recall ve F1 skorlarına ulaşmıştır. </br>
RandomForestClassifier modeli için hiper parametreleri optimize edilip model tekrar uygulanmıştır.

# Proje Kaggle Linki [https://www.kaggle.com/code/fatihakar5/heart-disease-prediction-project]

