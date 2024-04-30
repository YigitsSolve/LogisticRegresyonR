Kredi Riski Tahmini için Lojistik Regresyon Modeli
Bu GitHub deposu, lojistik regresyon modelini kullanarak kredi riskini tahmin etmeye yönelik bir çalışmayı içerir.

Amaç:

Bir kredi başvurusu yapan bir bireyin krediyi geri ödeyip ödemeyeceğini tahmin etmek için bir lojistik regresyon modeli geliştirmek.
Modelin performansını değerlendirmek ve sonuçları analiz etmek.
Kullanılan Veriler:

Veri seti, başvuru sahibinin demografik bilgileri, gelir durumu, kredi geçmişi ve diğer ilgili bilgileri içeren loan_data_set.csv dosyasından oluşmaktadır.

Veri İşleme:

Eksik veriler ve aykırı değerler ele alınmıştır.
Kategorik değişkenler ikili değişkenlere dönüştürülmüştür.
Veri seti, eğitim ve test setlerine ayrılmıştır.

Modelleme:

Lojistik regresyon modeli, eğitim seti üzerinde eğitilmiştir.
Model, test seti üzerinde tahminlerde bulunmak için kullanılmıştır.
Değerlendirme:

Modelin performansı, bir confusion matrisi kullanılarak değerlendirilmiştir.
