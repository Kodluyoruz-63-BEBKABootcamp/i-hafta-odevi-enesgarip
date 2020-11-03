#### <u>HESAPLARIM</u>

* [GitHub](https://github.com/enesgarip)

* [HackerRank](https://www.hackerrank.com/enes98_garip)

* [Stackoverflow](https://stackoverflow.com/users/14513395/garip)

#### <u>Docker Nedir?</u>

Docker bir nevi sanal makine çözümüdür. VirtualBox gibi uygulamalardan daha hafiftir. Çünkü daha az gereksinimi vardır. Web sistemlerinin kurulumu, testi, dağıtımı yapılabilir. Aynı zamanda açık kaynak kodlu bir platformdur.

Docker, yazılımları ve o yazılımlar için gerekli her şeyi **container** adı verilen birimlerde paketler. Bu sayede programlar containerlar altında taşınır ve sistem değişikliğinden dolayı programın çalışmaması gibi sorunlara çözüm oluşturur.

Docker, **dockerfile** adı verilen dosyadan komutları okuyup bu komutlara göre yazılımın hangi işletim sistemine kurulacağını, hangi programlama dili paketlerini gerektirdiğini, hani komutlarla yazılımın çalıştırılacağı bilgilerini içeren bir dosyadır. Bu dosyanın çalıştırılması sonucu sanal bir işletim sistemi ve diğer gereksinimler kurulur ve ortaya bir **image** çıkar. Bu image dosyasını kullanarak yazılımımız için bir container oluşur ve yazılımımız çalışır.

**Docker Hub** , docker image dosyalarının yüklenip ortak kullanıma açıldığı bir repositorydir. Bu sayede hali hazırda ücretsiz image dosyalarına ulaşım kolaylıkla sağlanabilir.

#### <u>.Net Core Versiyonları</u>

.Net Core, Microsoft ve .Net topluluğu tarafından geliştirilen yazılım geliştirme platformudur. Açık kaynak kodludur. Çapraz platform desteği vardır. Bu sayede Windows, macOS ve Linux üzerinde çalışan web uygulamaları bu platform sayesinde yazılabilir. Aynı zamanda Kubernetes, Docker gibi sistemleri desteklediği için kolaylıkla container oluşturulabilir. 

#### <u>.Net 5 Versiyonuna Geçilme İhtiyacı</u>

.Net 5 ile hedeflenen .Net Core, .Net Framework, Xamarin ve Mono'nun avantajlarını bir arada tek bir çatı altında toplamaktır. Yani artık tek bir .Net olacak. Fakat .Net 5 ile veda edilecek sistemlerde mevcut. ASP.NET Web Forms, WCF (Windows Communication Foundation) .Net 5 tarafından desteklenmeyecek. .Net Core'da olduğu gibi cross-platform desteği devam edecek.

#### <u>Markdown</u>

Markdown internet üzerinde metinleri HTML gibi düzenleyebileceğiniz bir sistemdir. Yazımı ve öğrenimi çok kolaydır. Aynı zamanda bir çok yerde kullanımı vardır. Özellikle Github platformunda README dosyaları markdown olarak hazırlanır ve projeye eklenir.

#### <u>Yazılım Alanında Takip Ettiğim Kişiler</u>

* Bora Kaşmer
* Engin Demiroğ
* Sadi Evren Şeker
* Onur Kemal Koç
* Selman Kahya
* Bilgem Çakır

#### <u>Microsoft Azure</u>

Microsoft Azure, Microsoft şirketinin cloud platformudur. Windows Server işletim sisteminin özelleştirilmiş halidir. 

![Azure Services](https://www.mshowto.org/images/articles/2015/03/032115_0557_MicrosoftAz3.png)

Yukarıda Azure bileşenleri ve hizmetleri gösterilmiştir.

#### <u>Kodun Kalitesinin Metrik Olarak Ölçülmesi</u>

Kodun kalitesinin metrik olarak ölçülmesi için belirli ölçekler vardır. Bu ölçekler bize ilerde daha büyük maliyetlere sebep olacak hatalardan kurtulma imkanı tanır. Oldukça fazla miktarda metrik olduğu için hepsini uygulamak çok mümkün değil fakat en çok kullanılanlar kısmına dikkat edebiliriz. Bu kısmı 2 bölüme ayırabiliriz

1. Koda Dayalı Ölçümler

   * Code Coverage

   * Cohesion 

   * Coupling
   * Cyclomatic Complexity
   * Cyclomatic Density
   * Response For Class (RFC)
   * Weighted Methods for Class (WMC)
   * Class Hierarchy Level veya Depth of Inheritance Tree (DIT)
   * Number of Methods in Class (NOM)
   * Specialization Index (SIX)

2. Dizayna Dayalı Ölçümler

   * Afferent Couplings (Ca)
   * Efferent Couplings (Ce)
   * Abstractness (A)
   * Instability (I)
   * Distance from the Main Sequence (D)

Bu tekniklere ek olarak kod tekrarı sayısı, dizayn ve kodun ne kadar izlenebilir olduğu da önemli noktalar arasındadır.

#### <u>Kaynakça</u>

https://docs.docker.com/

https://www.emrealadag.com/docker-nedir.html

https://guides.github.com/features/mastering-markdown/

https://stackify.com/everything-you-need-to-know-about-net-5-0/

https://medium.com/devopsturkiye/net-5-ve-yenilikleri-623aae985001

https://docs.microsoft.com/en-us/dotnet/core/dotnet-five

https://www.ultraedit.com/company/blog/community/what-is-markdown-why-use-it.html

https://www.mshowto.org/microsoft-azure-nedir-ne-ise-yarar-neden-kullanilir.html

https://www.baranbayram.net.tr/kod-kalite-olcumleri-ve-sik-kullanilan-metrikler.html