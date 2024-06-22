<h1> Aygaz Yapay Zekaya Giriş Bootcamp</h1>
  <h2> Aygaz Yapay Zekaya Giriş Bootcamp Final Projesi </h2>
  <p> Proje PDF: <a href="Aygaz Yapay Zeka Bootcamp.pdf" download>Aygaz Yapay Zeka Bootcamp PDF </a></p>
  <p> Google Colab Link: <a href="https://colab.research.google.com/drive/1XD47zCzj9BrPj6p8_En0dBOa50H9bEGV?usp=sharing"> Aygaz Yapay Zeka Bootcamp Colab </a></p>
  <img src="Aygaz Yapay Zeka Bootcamp.jpg" width="700" height="400"></a>

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
   <li><b>Sınıflar:</b> Tişört, Pantolon, Kazak, Elbise, Ceket, Sandalet, Gömlek, Spor Ayakkabı, Çanta, Bot. </li>
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

   ![Ekran görüntüsü 2024-06-22 191653](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/e62a82f4-cc4a-4696-9063-c668b4e37378)

  <h3> ROC Eğrisi ve AUC Skorları </h3>

 <h4> <b> Sınıf 0 : </b> </h4>
    
  ![Ekran görüntüsü 2024-06-22 192659](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/78af19a5-762e-4c96-a975-a3d4fdde1f06) 
  
  <h4> <b> Sınıf 1 : </b> </h4>
    
  ![Ekran görüntüsü 2024-06-22 192944](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/bdae513d-411a-481f-8820-49820215e0dc)

  <h4> <b> Sınıf 2 : </b> </h4>

  ![Ekran görüntüsü 2024-06-22 193811](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/fa414c29-f3a3-4cb5-b411-279655cf1a65)

  <h4> <b> Sınıf 3 : </b> </h4>

  ![Ekran görüntüsü 2024-06-22 193937](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/4509e7c8-eaf4-4a92-a2ac-80635818c14b)

  <h4> <b> Sınıf 4 : </b> </h4>

  ![Ekran görüntüsü 2024-06-22 194008](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/26e49d73-7935-4239-b97b-31cb19b44a45)

  <h4> <b> Sınıf 5 : </b> </h4>

  ![Ekran görüntüsü 2024-06-22 194649](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/2a0a4261-4c0c-47e4-ba16-53815e1d8a89)


  <h4> <b> Sınıf 6 : </b> </h4>
  
  ![Ekran görüntüsü 2024-06-22 194627](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/d04473f1-633c-4876-a04a-c4e24b471ae4)

  <h4> <b> Sınıf 7 : </b> </h4>

  ![Ekran görüntüsü 2024-06-22 194053](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/45ebc471-5a8c-4918-9694-ca3fb008ad2c)

  <h4> <b> Sınıf 8 : </b> </h4>

  ![Ekran görüntüsü 2024-06-22 194350](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/244ac580-4e6b-4f4c-98b4-6540056a2e38)


  <h4> <b> Sınıf 9 : </b> </h4>

  ![Ekran görüntüsü 2024-06-22 194406](https://github.com/nuricakir/AygazYapayZeka/assets/112883476/9fb48fae-b106-4745-a25e-ac0bc2602383)

<h2> Tartışma </h2>
 <p>
  <ul>
   <li> <b> Başarılar:</b> Modelin genel doğruluğu %91 olarak oldukça yüksektir.</li>
   <li> <b> Güçlü Yönler: </b> Model, birçok sınıfta yüksek doğruluk oranlarına sahiptir. </li>
   <li> <b> Zayıf Yönler: </b> Bazı sınıflarda (Örneğin Sınıf 6) daha düşük doğruluk oranları gözlemlenmiştir.</li>
   <li> <b> Geliştirme Alanları:</b>  Modelin bazı sınıflarda daha iyi performans göstermesi için hiperparametre optimizasyonu yapılabilir.</li>
  </ul>
 </p>
<h2> Kaynaklar </h2>
 <p>
  <ul>
   <li> <a href="https://keras.io/"> Keras Documentation</a></li>
   <li> <a href="https://github.com/zalandoresearch/fashion-mnist">Fashion MNIST Dataset</a></li>
   <li> <a href="https://colab.google">Google Colab</a></li>
   <li> <a href="https://medium.com/@gulcanogundur/roc-ve-auc-1fefcfc71a14"> ROC ve AUC Medium</a></li>
   <li> <a href="https://medium.com/@gulcanogundur/do%C4%9Fruluk-accuracy-kesinlik-precision-duyarl%C4%B1l%C4%B1k-recall-ya-da-f1-score-300c925feb38)">Doğruluk (Accuracy) , Kesinlik(Precision) , Duyarlılık(Recall) ya da F1 Score Medium</a></li>
    
  </ul>
</p>


