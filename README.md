Bu projede öncelikle, iyi huylu ve kötü huylu tümörlerin fotoğraflarının bulunduğu bir datasetten PyRadiomics kullanılarak radiomic özellik çıkarımı yapılmıştır.
Daha sonrasında bu radiomic özellikler üzerinde öncelikle feature importance score ve correlation değerleri kullanılarak oluşturulmuş bir katsayı değeri kullanılarak feature selection yapılmıştır.
2. bir yol olarak ise PCA ile özellik seçimi uygulanmıştır.

Sonrasında seçilmiş olan bu özellikler ile model eğitimi yapılarak kanser türünü tahmin eden model oluşturulmuştur.
Modeller oluşturulduktan sonra çeşitli karşılaştırma işlemleri yapılmıştır.

////////////////

In this project, radiomic feature extraction was performed using PyRadiomics from a dataset containing images of benign and malignant tumors.
Subsequently, feature selection was carried out on these radiomic features using a coefficient value derived from feature importance scores and correlation values.
As a second method, feature selection was applied using PCA.

Then, a model predicting the type of cancer was created by training with these selected features.
After the models were created, various comparison procedures were performed.
