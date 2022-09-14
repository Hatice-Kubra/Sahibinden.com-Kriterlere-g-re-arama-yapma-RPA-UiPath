# Sahibinden.com-Kriterlere-gore-arama-yapma-RPA-UiPath

	PROJE İÇERİĞİ
  
Proje kapsamında geliştirilmesi beklenen örnek senaryonun adımları aşağıdaki gibidir.

• Chrome browser açılarak, sahibinden.com sayfasına gidilir.

• Satılık konut ilanlarında Click, Type Into ve gerekli görülen diğer activityler kullanılarak, İstanbul/Kadıköy ilçesinde yer alan 1.000.000₺- 2.000.000₺ arası, 0-10 yaş arası, Emlak Ofisinden ilan verilmiş satılık olan konutlar aratılır. 

• Arama sonucunda gelen ilanların, Data Scraping kullanılarak ilan listesi harici bir excel dosyasına yazdırılır. İşlemler ReFramework yapısında Init State’i içerisinde gerçekleştirilmelidir. 

• Her bir ilan için, detayında yer alan tüm bilgiler(il,ilçe,mah,fiyat, ilan no, tarih, emlak türü vb.) excel dosyasına alınır. Gerekli işlemler Process Transaction State’inde gerçekleştirilir.

• Kaydedilen rapor excel dosyası, SMTP ile farklı bir mail adresine iletilmelidir.
