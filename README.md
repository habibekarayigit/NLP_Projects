# Türkçe Databalancing_methods
Türkçe Metin Veri dengeleme yöntemleri

1- Neden gereklidir? </br>
2- Hangi yöntemler kullanılır?<br>
3- Hangileri efektiftir? <br>
4- TextGAN çılgınlığı <br>

1- Neden gereklidir? </br>
Sınıf dengesizliği, veri kümesindeki farklı sınıflara ait örneklerin sayısının önemli ölçüde farklı olması durumudur. Özellikle azınlık sınıfların sayısı çok daha az olduğunda, bu durum sınıflandırma modellerinin performansını olumsuz etkileyebilir.


2- Hangi yöntemler kullanılır? </br>
Deneyimlediğim yöntemler;  </br>
ROS oversampling </br>
SMOTE oversampling </br>
K-means SMOTE oversampling </br>
LoRAS oversampling </br>
TextGAN oversampling </br>
Nearmiss undersampling </br>
Tomek Links undersampling </br>
Clustering-based  undersampling yöntemleridir.

3- Hangileri efektiftir? </br>
Elde ettiğim sınıflandırma sonuçları oversampling dengeleme metodlarının daha efektif sonuçlar elde ettiği yönündedir.

4- TextGAN çılgınlığı </br>
TextGAN'a ayrı bir paragraf açmak gerekiyordu. TextGAN çekişmeli ağ yapısını kullanarak veri kümesindeki verileri arttıran bir yöntemdir. Çekişmeli ağ yapısı görüntü verilerinin ardından metin verilerinde de kaliteli artırımlar yapmıştır.
