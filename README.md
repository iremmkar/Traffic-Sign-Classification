
## CONVOLUTIONAL NEURAL NETWORK (CNN) İLE TRAFİK İŞARET VE LEVHALARININ TANIMLANMASI

Günümüz teknoloji koşullarında araçlarda kullanılan sürücü destek sistemleri oldukça
yaygınlaşmıştır. Araç sayısındaki artış nedeni ile oluşacak kazalar, araçlarda kullanılan sürücü
destek sistemleri ile azaltılması amaçlanmaktadır.

Sürücü destek sistemlerinin başında da yollardaki trafik işaretlerini tanıyıp sürücüye, işaretlere
göre yol koşullarını bildiren otomatik trafik işareti tanıma sistemleri gelmektedir.

Ayrıca yolcunun seyahat için tamamen araca güvenebileceği, kendi kendine giden arabaların
kullanımı gittikçe artmaktadır. Ancak 5. seviye otonoma ulaşmak için araçların tüm trafik
kurallarını anlaması ve bunlara uyması gerekir.

Yapay Zeka ve teknolojilerdeki ilerleme dünyasında, birçok araştırmacı ve Tesla, Uber,
Google, Mercedes-Benz, Toyota, Ford, Audi gibi büyük şirketler, otonom araçlar ve kendi
kendine giden arabalar üzerinde çalışımaktadır. Dolayısıyla bu teknolojide doğruluğun
sağlanabilmesi için araçların trafik işaretlerini yorumlayabilmeleri ve buna göre karar
verebilmeleri gerekmektedir.

**Trafik İşareti Tanıma Nedir?**

Hız limitleri, giriş yapılmaması, trafik işaretleri, sola veya sağa dönüş, çocukların karşıya
geçmesi, ağır araçların geçmemesi vb. gibi birçok farklı trafik işareti türü vardır. Trafik
işaretleri sınıflandırması, bir trafik işaretinin hangi sınıfa ait olduğunu belirleme işlemidir.

## Kullanılan Ortam, Yöntem ve Kütüphaneler

### PyCharm

PyCharm, çapraz platform bir Python geliştirme ortamı (IDE)' dir. Kod analizleri, grafiksel hata
ayıklamacısı (debugger), versiyon kontrol sistemi (VCS) ile entegre ve Django ile Python web
geliştirmeleri yapılmasını sağlamaktadır.

### Convolutional Neural Network

CNN genellikle görüntü işlemede kullanılan ve girdi olarak görselleri alan bir derin öğrenme
algoritmasıdır. Farklı operasyonlarla görsellerdeki featureları (özellikleri) yakalayan ve onları
sınıflandıran bu algoritma farklı katmanlardan oluşmaktadır. Convolutional Layer, Pooling ve
Fully Connected olan bu katmanlardan geçen görsel, farklı işlemlere tabii tutularak derin
öğrenme modeline girecek kıvama gelir. CNN modelleri oluştururken, unstructural (düzensiz)
veri ile uğraşıldığından klasik makine öğrenmesi algoritmalarına kıyasla veri ön işleme
kısmında çok uğraşılır.

### Keras

Keras, neredeyse her tür derin öğrenme modelini tanımlamak ve eğitmek için uygun bir yol
sağlayan Python için bir derin öğrenme kütüphanesidir. Keras, Tensorflow, Theano ve CNTK üzerinde çalışabilen Python ile yazılmış bir üst düzey sinir ağları API’sıdır. İçerdiği çok fazla
işlevsel fonksiyon sayesinde Keras kolayca bir derin öğrenme modeli oluşturmayı ve onu
eğitmeyi sağlar.

### Matplotlib
Matplotlib, figürlerin görselleştirilmesinde ve analizine yardımcı olan en popüler 2 Boyutlu bir
çizim kütüphanesidir. Görselleştirme bilgiyi analiz etmenin ve ondan belirli sonuçlar
çıkarmanın en kolay yoludur. Yapılan bu görselleştirmeler karmaşık bir sorunu kolayca
anlamaya yardımcı olur. Görselleştirmeler verideki ilişkileri, yapıları ve aykırı değerleri tespit
etmeye destek sağlar. Aynı zamanda EDA (Exploratory Data Analysis) ve Makine Öğrenmesi
gibi süreçlere veriyi hazırlar.

### Scikit-learn

Scikit-learn, veri bilimi ve machine learning için en yaygın kullanılan Python paketlerinden
biridir. Birçok işlemi gerçekleştirmeyi ve çeşitli algoritmaları sağlar. Scikit-learn ayrıca
sınıfları, yöntemleri ve işlevleri ile kullanılan algoritmaların arka planıyla ilgili belgeler sunar.

### Pandas

Pandas, “ilişkisel” ve “etiketli” verilerle çalışmayı kolay ve sezgisel hale getirmek için
tasarlanmış hızlı, esnek ve etkileyici veri yapıları sağlayan bir Python paketidir. Python’da
pratik, gerçek dünya veri analizi yapmak için temel yapı taşı olmayı hedefler. Ayriyeten, her
dilde mevcut olan en güçlü ve esnek açık kaynak veri analizi / manipülasyon aracı olmak gibi
daha geniş bir amaca sahiptir.

### PIL

Python Image Library, yani Python Resim Kütüphanesi, Pythonda image işlemlerini kolayca
yapabilmek için geliştirilmiş kütüphanedir. 2009'dan beri geliştirilmemiş onun yerine Pythonda PIL' ın forklanmış hali Pillow kullanılmaktadır.

