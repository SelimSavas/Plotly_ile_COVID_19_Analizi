# Plotly ile COVID-19 Analizi

# İçindekiler
COVID-19
Plotly
Plotly's Python graphing library
Analiz tanıtımı
Kütüphaneler
Dosya okuma ve İlk bakış
İncelemem sırasında sıkıntı yaratıcak sütun isimleri keşfettim.
İşimize yarıyacak sütunlardan oluşan yeni bir DataFrame
Kaç tane eyaletimiz varmış öğrenelim.
Eyaletlerimizi benzersiz şekilde listeliyelim.
Boş Confirmed, Deaths ve Confirmed_Deaths_rate değerlerini doldurmak:
Verimizi Ölüm oranına göre short edelim
Plotly ile COVID-19 Analizi 1 : Multiple Subplots
Sıralamayı değiştirmek ve yeni görsel
Plotly ile COVID-19 Analizi 2 : WordCloud
Object değerleri floata'a çevirmek
WordCloud kütüphanesini import edelim
Plotly ile COVID-19 Analizi 3 : Scatter Plot Matrix
Plotly ile COVID-19 Analizi 4 : 3D Scatter Plot
Plotly ile COVID-19 Analizi 5 : Pie Charts
Plotly ile COVID-19 Analizi 6 : Yakında...

## COVID-19
Yeni Koronavirüs Hastalığı (COVID-19), ilk olarak Çin’in Vuhan Eyaleti’nde Aralık ayının sonlarında solunum yolu belirtileri (ateş, öksürük, nefes darlığı) gelişen bir grup hastada yapılan araştırmalar sonucunda 13 Ocak 2020’de tanımlanan bir virüstür.

Salgın başlangıçta bu bölgedeki deniz ürünleri ve hayvan pazarında bulunanlarda tespit edilmiştir. Daha sonra insandan insana bulaşarak Vuhan başta olmak üzere Hubei eyaletindeki diğer şehirlere ve Çin Halk Cumhuriyeti’nin diğer eyaletlerine ve diğer dünya ülkelerine yayılmıştır.

Koronavirüsler, hayvanlarda veya insanlarda hastalığa neden olabilecek büyük bir virüs ailesidir. İnsanlarda, birkaç koronavirüsün soğuk algınlığından Orta Doğu Solunum Sendromu (MERS) ve Şiddetli Akut Solunum Sendromu (SARS) gibi daha şiddetli hastalıklara kadar solunum yolu enfeksiyonlarına neden olduğu bilinmektedir. Yeni Koronavirüs Hastalığına SAR-CoV-2 virüsü neden olur.

https://covid19bilgi.saglik.gov.tr/tr/covid-19-yeni-koronavirus-hastaligi-nedir

## Plotly
İngilizceden çevrilmiştir-Plotly, merkezi Montreal, Quebec'te bulunan ve çevrimiçi veri analizi ve görselleştirme araçları geliştiren teknik bir bilgi işlem şirketidir.

https://g.co/kgs/z5oGZn

### Plotly's Python graphing library
İngilizceden çevrilmiştir- Plotly'nin Python grafik kütüphanesi etkileşimli, yayın kalitesinde grafikler yapar. Çizgi grafikleri, saçılma grafikleri, alan grafikleri, çubuk grafikler, hata çubukları, kutu grafikleri, histogramlar, ısı haritaları, alt grafikler, çoklu eksenler, kutup grafikleri ve kabarcık grafikleri oluşturma örnekleri.

https://plotly.com/python/

## Analizler
1 - Onaylanmış hasta sayısı, ölüm sayısı ve ölüm oranlarını, şehirin ölüm oranlarını baz alarak grafikte sıralamak. (Multiple Subplots)

2 - En çok hastanın olduğu 40 şehirin, ölüm oranınına göre şehir ismini ekrana basmak (WordCloud)

3 - Onaylanmış hasta sayısı, ölüm sayısı ve ölüm oranları arasındaki korelasyonu incelemek (Scatter Matrix)

4 - Onaylanmış hasta sayısı, ölüm sayısı ve ölüm oranlarını 3 boyutlu görsellede incelemek (3D Scatter Plot)

5 - En çok hasta barındıran 15 şehirin ölüm oranlarına yüzdelik şekilde bakmak (Pie Charts)

## Veri

https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
