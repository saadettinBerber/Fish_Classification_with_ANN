# Fish_Classification_with_ANN

Bu proje, İzmir Ekonomi Üniversitesi'nde toplanan ve 9 farklı deniz ürünü türüne ait 1000'er adet RGB görüntü ile bunların karşılık gelen ground truth etiketlerini içeren bir veri seti üzerinde sınıflandırma çalışması yapmayı amaçlamaktadır. Görüntüler iki farklı kamera ile toplanmış, boyutları 590x445 olacak şekilde yeniden boyutlandırılmış ve "00000.png" ile "01000.png" arasında adlandırılmıştır. Veri seti, özellik çıkarımı, segmentasyon ve sınıflandırma algoritmalarını test etmek için kullanılmıştır; biz ise bu projede **sınıflandırma** odaklı bir yaklaşım benimseyerek, farklı hiperparametreler üzerinden deneyler gerçekleştirdik. Bu deneyler kapsamında, 128 ve 512 nöronlu gizli katmanlara sahip modelleri kıyasladık, dropout değerlerini 0.5 ve 0.7 olarak ayarlayarak modellerin genelleme yeteneklerini inceledik, optimizasyon algoritmaları olarak Adam ve SGD'yi karşılaştırdık ve (giriş_boyutu, 512, 128, kategori_sayısı - 9) katmanlı bir model eğittik. Son olarak, eğitilen tüm modellerin performanslarını değerlendirerek en iyi sonuçları elde etmeyi hedefledik.

Kaggle Link:
https://www.kaggle.com/code/sadomazoo/fish-classification-with-ann/notebook
