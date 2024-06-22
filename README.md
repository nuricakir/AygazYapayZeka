<h1> Aygaz Yapay Zekaya Giriş Bootcamp</h1>
  <h2> Aygaz Yapay Zekaya Giriş Bootcamp Final Projesi </h2>
  <p> Proje PDF: <a href="Aygaz.Bootcamp.pdf" download>Aygaz Yapay Zeka Bootcamp PDF </a></p>
  <img src="AygazBootcamp.jpg"></a>

 <h2> Proje </h2>

  <p> Bu proje, Aygaz ve Global AI Hub işbirliğinde 06.06.2024 – 22.06.2024 tarihleri arasında düzenlenen "Aygaz Yapay Zekaya Giriş Bootcamp" kapsamında gerçekleştirilen bir final proje çalışmasıdır.
</p>

 <h2> Projenin Amacı </h2>
  <p>Projenin amacı, Fashion MNIST veri seti kullanılarak giyim eşyalarının doğru bir şekilde görüntü sınıflandırılmasını sağlamaktır. Bu kapsamda Evrişimli Sinir Ağları (CNN) mimarisi kullanılarak bir model oluşturulmuştur. Modelin performansı çeşitli metrikler kullanılarak değerlendirilmiştir.</p>

 <h2> Materyal – Metod </h2>
  <p>
   <ul>
     <li><b>Veri Seti:</b> Fashion MNIST</li>
     <li><b>Kütüphaneler:</b>NumPy, Matplotlib, TensorFlow, Seaborn, Sklearn</li>
     <li><b> Model:</b> Evrişimli Sinir Ağı (CNN) </li>
     <li> <b> Değerlendirme Metrikleri: </b> Karmaşıklık Matrisi, Sınıflandırma Raporu, ROC Eğrisi ve AUC Değerler.</li>
   </ul>
  </p>

 <h2> Veri Seti Hakkında Bilgi</h2>
 <p> Fashion MNIST, 60,000 eğitim ve 10,000 test örneği içeren veri 
setidir.</p>
 <p> 
  <ul>
   <li><b>Görüntü Boyutu:</b> 28x28 gri tonlamalı görüntülerdir.</li>
   <li><b>Sınıflar:</b> T-shirt, Pantolon, Kazak, Elbise, Ceket, Sandalet, Gömlek, Spor Ayakkabı, Çanta, Bot. </li>
  </ul>
 </p>

<h2> Veri Görselleştirme </h2>
 <p> Eğitim veri setinden örnek veri görselleştirme görüntüsü (10 adet):</p>

 ![Ekran görüntüsü 2024-06-22 163636](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/7fe3afb3-ef14-4b13-a872-8e7bbb7cafdd)

 <h2> Model Mimarisi </h2>
  <p>
   <ul>
    <li> <b> Katman 1: </b> 32 filtreli, 3x3 boyutunda Conv2D, ReLU aktivasyonu  </li>
    <li> <b> Katman 2: </b> 2x2 MaxPooling2D  </li>
    <li> <b> Katman 3: </b>  64 filtreli, 3x3 boyutunda Conv2D, ReLU aktivasyonu  </li>
    <li> <b> Katman 4: </b> 2x2 MaxPooling2D  </li>
    <li> <b> Katman 5: </b> Flatten  </li>
    <li> <b> Katman 6: </b> 128 nöronlu Dense, ReLU aktivasyonu  </li>
    <li> <b> Katman 7: </b> 10 nöronlu Dense, Softmax aktivasyonu  </li>
   </ul>
  </p>

 <h2> Eğitim ve Değerlendirme</h2>
  <p> Modelin eğitimi 10 epoch boyunca gerçekleştirilmiştir. Eğitim ve doğrulama doğrulukları ile kayıpları aşağıdaki grafiklerde gösterilmiştir:</p>

  ![Ekran görüntüsü 2024-06-22 170756](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/da6c2ded-7685-4e02-b36e-449d67800888)
  ![Ekran görüntüsü 2024-06-22 170920](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/5275ae56-6a3c-4b67-b51d-bfd179d2179d)

 <h2> Deney Sonuçları </h2>

  <h3> Modelin Test Verisindeki Performansı:</h3>

  ![Ekran görüntüsü 2024-06-22 134939](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/55e64717-ec24-4ec5-ad10-a9e80fc5081a) 


  <h3> Karmaşıklık Matrisi </h3>

   ![Ekran görüntüsü 2024-06-22 181605](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/fdf67d1b-4184-4563-a0ef-d651915d85c2) 

  <h3> ROC Eğrisi ve AUC Skorları </h3>


<h2> Tartışma </h2>
 <p>
  <ul>
   <li> <b> Başarılar:</b> Modelin genel doğruluğu %91 olarak oldukça yüksektir.</li>
   <li> <b> Güçlü Yönler: </b> Model, birçok sınıfta yüksek doğruluk oranlarına sahiptir. </li>
   <li> <b> Zayıf Yönler: </b> Bazı sınıflarda (örneğin Class 6) daha düşük doğruluk oranları gözlemlenmiştir.</li>
   <li> <b> Geliştirme Alanları:</b>  Modelin bazı sınıflarda daha iyi performans göstermesi için hiperparametre optimizasyonu yapılabilir.</li>
  </ul>
 </p>
<h2> Kaynaklar </h2>
 <p>
  <ul>
   <li> <a href="https://keras.io/"> Keras Documentation</a></li>
   <li> <a href="https://github.com/zalandoresearch/fashion-mnist">Fashion MNIST Dataset</a></li>
  </ul>
</p>


