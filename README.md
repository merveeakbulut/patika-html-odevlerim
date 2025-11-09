# patika-html-odevlerim

Bu depo, Patika.dev HTML kursu Bölüm Sonu Çalışması 2 için oluşturulmuştur.

---

## Ödev 2 İçeriğinden Bir Kesit 

HTML sayfamda yer alan içeriklerin `README.md` dosyasındaki bir önizlemesidir.

![Bu, sevdiğim bir köpek resmi.](https://picsum.photos/id/237/400/300)

Bu, sevdiğim bir köpek resmi.

### Sevdiğim Filmler

* [Kara Şövalye (The Dark Knight)](https://www.imdb.com/title/tt0468569/)
* Yüzüklerin Efendisi: Kralın Dönüşü
* Esaretin Bedeli

### Sevdiğim Diziler

* [Game of Thrones](https://www.imdb.com/title/tt0944947/)
* Breaking Bad
* Chernobyl

### Sevdiğim Kitaplar

* [Açlık Oyunları (Suzanne Collins)](https://www.goodreads.com/book/show/3735293-the-hunger-games)
* 1984 (George Orwell)
* Simyacı (Paulo Coelho)

---

# Kodlama Günlüğüm

* **[Ana Sayfa](index.html)**
* **[Hakkımızda](hakkimizda.html)**
* **[İletişim](iletisim.html)**

---

## Hakkımızda

### Biz Kimiz?

![Rastgele bir ofis görseli](https://picsum.photos/id/48/600/300)

Biz, Patika.dev üzerinde HTML ve CSS öğrenen meraklı yazılımcı adaylarıyız.

Bu web sitesi, HTML Bölüm Sonu Çalışması kapsamında oluşturulmuştur.

### Vizyonumuz

Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum, sint quos. Repellat, reprehenderit. Laboriosam, et.

* Yenilikçi çözümler üretmek.
* Sürekli öğrenmeye devam etmek.
* Açık kaynak projelere katkı sağlamak.

### Misyonumuz

Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia, sunt. Similique, nobis.

Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quod, repellendus?

---

* **[Ana Sayfa](index.html)**
* **[Hakkımızda](hakkimizda.html)**
* **[İletişim](iletisim.html)**

*© 2025 Tüm Hakları Saklıdır. Bu bir Patika.dev ödevidir.*


---
# Kodlama Günlüğüm

* **[Ana Sayfa](index.html)**
* **[Hakkımızda](hakkimizda.html)**
* **[İletişim](iletisim.html)**

---

## Ana Sayfa

HTML öğrenme yolculuğuma hoş geldiniz! Bu site, Patika.dev HTML kursundaki bölüm sonu çalışmamdır.

Bu sayfada kişisel projelerimi ve öğrendiklerimi paylaşıyorum.

![Rastgele bir çalışma masası görseli](https://picsum.photos/id/1/600/300)

### Bu Sitede Neler Var?

Bu site 3 sayfadan oluşmaktadır:

1.  **Ana Sayfa:** Şu an bulunduğunuz sayfa. Genel bir karşılama içerir.
2.  **Hakkımızda Sayfası:** Bu projenin amacı ve vizyonum hakkında bilgiler.
3.  **İletişim Sayfası:** Bana ulaşabileceğiniz adres ve iletişim bilgileri.

### İlgi Alanlarım (Ödev 2'den)

Boş zamanlarımda yapmayı sevdiğim şeylerden bazıları:

* **Film:** [Dövüş Kulübü](https://www.imdb.com/title/tt0137523/)
* **Dizi:** Breaking Bad
* **Kitap:** [1984 - George Orwell](https://www.goodreads.com/book/show/40961427-1984)

---

* **[Ana Sayfa](index.html)**
* **[Hakkımızda](hakkimizda.html)**
* **[İletişim](iletisim.html)**

*© 2025 Tüm Hakları Saklıdır. Bu bir Patika.dev ödevidir.*

---

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frambuazlı Cheesecake Tarifi</title>
    
    <style>
        body {
            background-color: #fdfaf6; /* Açık, sıcak bir bej arka plan */
            font-family: Arial, Helvetica, sans-serif; /* Okunaklı bir yazı tipi */
            line-height: 1.6; /* Satır aralığını artırarak okumayı kolaylaştırır */
            margin: 0;
            padding: 0;
        }

        /* İçeriği ortalayan ve beyaz bir kart içine alan ana kutu */
        .container {
            width: 80%;
            max-width: 900px;
            margin: 20px auto; /* Üstten/alttan boşluk, sağdan/soldan otomatik ortala */
            padding: 25px 40px;
            background-color: #ffffff; /* İçerik alanı beyaz kalsın */
            border-radius: 10px; /* Kenarları yumuşatır */
            box-shadow: 0 4px 12px rgba(0,0,0,0.05); /* Hafif bir gölge */
        }

        h1 {
            color: #D9376E; /* Ana başlık için canlı bir frambuaz rengi */
            text-align: center; /* Başlığı ortala */
        }

        h2 {
            color: #333;
            border-bottom: 2px solid #f0f0f0; /* Başlıkların altını hafifçe ayırır */
            padding-bottom: 5px;
        }
        
        h3 {
            color: #555;
        }

        ul, ol {
            padding-left: 20px; /* Listelerin girintisini ayarlar */
        }

        li {
            margin-bottom: 8px; /* Liste elemanları arasına boşluk koyar */
        }
        
        /* Videoyu sayfaya gömmek için (isteğe bağlı) */
        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            height: 0;
            overflow: hidden;
            margin-bottom: 20px;
            border-radius: 8px;
        }
        .video-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

    </style>
    </head>
<body>

    <div class="container">

        <header>
            <h1>Frambuazlı Cheesecake Tarifi</h1>
            <p>Nefis Yemek Tarifleri'nin popüler tarifi ile ev yapımı frambuazlı cheesecake. Hem göze hem damağa hitap eden muhteşem bir lezzet!</p>
        </header>

        <hr>

        <main>
            
            <section class="video-wrapper">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/S2pP-nLd-f0" 
                        title="YouTube video player" frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                        allowfullscreen>
                </iframe>
            </section>

            <article>
                <section>
                    <h2>Malzemeler</h2>

                    <h3>Tabanı İçin:</h3>
                    <ul>
                        <li>2 paket yulaflı bisküvi</li>
                        <li>100 gr tereyağı (eritilmiş)</li>
                    </ul>

                    <h3>Kreması İçin:</h3>
                    <ul>
                        <li>600 gr labne peyniri (suyu süzülmüş)</li>
                        <li>1 su bardağı toz şeker</li>
                        <li>1 paket vanilya</li>
                        <li>3 adet yumurta</li>
                        <li>1 adet limon kabuğu rendesi</li>
                        <li>200 ml krema (1 paket)</li>
                    </ul>
                    
                    <h3>Frambuaz Sosu İçin:</h3>
                    <ul>
                        <li>250 gr frambuaz (dondurulmuş veya taze)</li>
                        <li>4 yemek kaşığı toz şeker</li>
                        <li>1 yemek kaşığı mısır nişastası</li>
                        <li>Yarım su bardağı su</li>
                    </ul>
                </section>
                
                <hr>

                <section>
                    <h2>Nasıl Yapılır?</h2>

                    <ol>
                        <li><strong>Taban Hazırlığı:</strong> Bisküvileri rondodan un gibi olana kadar çekin. Eritilmiş tereyağı ile karıştırın.</li>
                        <li>Kelepçeli kalıbın (26 cm) tabanına yağlı kağıt serin. Bisküvili karışımı tabana eşitçe yayın ve bir bardak yardımıyla bastırarak sıkıştırın.</li>
                        <li>Tabanı, krema hazırlanana kadar buzdolabında dinlendirin.</li>
                        <li><strong>Krema Hazırlığı:</strong> Labne, toz şeker, vanilya ve limon kabuğu rendesini bir çırpma kabına alın. Mikserle pürüzsüz olana kadar çırpın.</li>
                        <li>Yumurtaları teker teker, her birini ekledikten sonra düşük devirde sadece karışana kadar (yaklaşık 15 saniye) çırparak harca yedirin.</li>
                        <li>Son olarak kremayı (sıvı olan) ekleyin ve bir spatula ile yavaşça, alttan üste doğru karıştırın. (Fazla çırpmayın, çatlamasın).</li>
                        <li>Hazırladığınız kremayı bisküvili tabanın üzerine dökün.</li>
                        <li><strong>Pişirme:</strong> Kalıbın kenarlarını dıştan alüminyum folyo ile kaplayın (Su almaması için).</li>
                        <li>Cheesecake kalıbını fırın tepsisine oturtun. Fırın tepsisinin içine, kalıbın yarısına gelecek kadar sıcak su doldurun (Benmari usulü).</li>
                        <li>Önceden ısıtılmış **160°C** fırında, alt-üst ayarda yaklaşık **60 dakika** (üzeri hafif sallanırken kenarları sabitlenmiş olmalı) pişirin.</li>
                        <li>Fırını kapatın. Fırının kapağını hafifçe aralayıp cheesecake'i 1 saat fırının içinde dinlendirin.</li>
                        <li><strong>Sos Hazırlığı:</strong> Sos için frambuaz, şeker, su ve nişastayı küçük bir tencereye alın.</li>
                        <li>Orta ateşte, sürekli karıştırarak koyulaşıp kaynayana kadar pişirin. Ocaktan alıp tamamen soğumaya bırakın.</li>
                        <li><strong>Birleştirme:</strong> Fırından çıkan ve oda sıcaklığına gelen cheesecake'in üzerine, tamamen soğumuş olan frambuaz sosunu dökün.</li>
                        <li>Cheesecake'i buzdolabında **en az 4-5 saat**, tercihen 1 gece dinlendirdikten sonra servis yapın.</li>
                    </ol>
                </section>
            </article>
        </main>

        <footer>
            <h2 style="text-align: center; color: #D9376E;">Afiyet Olsun!</h2>
        </footer>

    </div> </body>
</html>
