# DBN-Algorithm-Mnist-Dataset

Bu projede, DBN (Deep Belief Network, Derin İnanç Ağları) algoritması ile mnist veri seti üzerinde uygulama yapılmıştır.

DBN kütüphanesi githubda bir başkası tarafından yazılan kütüphane yardımı ile uygulanmıştır. (# at https://github.com/albertbup/deep-belief-network )

Mnist veriseti, 0'dan 9'a kadar olan tüm rakamların elyazısı ile yazılmış bir verisetidir. Bu sebeple 0-9 arası 10 class vardır.
Her bir görüntü 28*28 pikselden oluşmaktadır.
Sklearn kütüphanesi yardımı ile veriseti kolayca projeye yüklenmiştir. 
Her sınıftan 100 örnek alınarak toplam 1000 veri elde edilmiştir.

DBN algoritması önce çok katmanlı daha sonraki kod bloğunda ise tek katmanlı olarak farklı farklı denenerek, en yüksek başarım elde edilmeye çalışılmıştır.
