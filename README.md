# First-Project
My First Project

## Proje Fikirleri

Aşağıda geliştirilebilecek 10 farklı proje fikri yer almaktadır:

1.  **Yerel Gizlilik Odaklı Kişisel Asistan:** Llama 3 veya Mistral gibi modelleri yerel olarak (Ollama vb. ile) kullanarak, internete bağlanmadan kişisel notları ve dosyaları analiz eden bir asistan.
2.  **Kendi Kendini Düzenleyen Makale Yazarı (Agent):** Bir konu hakkında taslak oluşturur, yazdığı taslağı bir "eleştirmen" gözüyle inceler, hataları ve eksikleri bulur, ardından daha iyi bir versiyonu kendi kendine yazar.
3.  **Akıllı Kod Refaktörleme Aracı:** Yerel bir LLM kullanarak projedeki karmaşık fonksiyonları tespit eder ve onları daha temiz bir hale getirmek için öneriler sunar.
4.  **Otonom Hata Ayıklama Botu:** Terminal çıktısındaki hataları okur, çözüm önerir, kodu değiştirir ve testi tekrar çalıştırarak hatanın düzelip düzelmediğini kontrol eder.
5.  **Kendi Prompt'unu Optimize Eden Prompt Mühendisi:** Kullanıcının verdiği basit bir prompt'u alır, çıktıları değerlendirir ve en iyi sonucu almak için prompt'u iteratif olarak geliştirir.
6.  **Yerel Dökümantasyon Soru-Cevap Sistemi (RAG):** Bir şirketin veya projenin tüm PDF/Markdown dökümanlarını yerel bir vektör veritabanına indeksler ve sorulara yerel modelle cevap verir.
7.  **Çoklu Ajanlı Oyun Geliştirme Takımı:** Bir ajan oyun mekaniği tasarlar, diğeri kod yazar, üçüncüsü kodu test eder. Birbirleriyle iletişim kurarak basit bir oyun geliştirirler.
8.  **Kişiselleştirilmiş Yerel Haber Özetleyici:** Kullanıcının ilgi alanlarına göre RSS beslemelerini takip eder ve yerel AI ile her sabah kişiye özel kısa bir bülten hazırlar.
9.  **Duygu Analizli Günlük Uygulaması:** Yazılan günlük girişlerini yerel olarak analiz eder, zaman içindeki mod değişimlerini grafiklerle gösterir ve psikolojik farkındalık sağlar.
10. **Kendi Çıktısını Test Eden SQL Oluşturucu:** Doğal dilden SQL sorgusu oluşturur, sorguyu bir test veritabanında çalıştırır, eğer hata alırsa hatayı analiz ederek sorguyu düzeltir ve tekrar dener.

## Siber Güvenlik Proje Fikirleri (SIEM, Python, Wazuh)

Siber güvenlik alanında AI ve otomasyon odaklı geliştirilebilecek fikirler:

1.  **Yapay Zeka Destekli SOC Analisti:** Wazuh üzerinden gelen alert'leri yerel bir LLM'e (Llama 3 vb.) göndererek, alarmın kritiklik düzeyini analiz eden ve analiste çözüm adımları (remediation) öneren bir sistem.
2.  **AI ile Akıllı "Active Response":** Wazuh'un Active Response özelliğini bir AI ajanı ile birleştirmek. AI, saldırı tipini belirler ve sadece statik kurallarla değil, saldırının doğasına göre (IP engelleme, servis durdurma vb.) dinamik kararlar verir.
3.  **Wazuh API ile Otomatik "Tehdit Avcılığı" (Threat Hunting):** Python kullanarak Wazuh API üzerinden son 24 saatlik logları çeken ve anomali tespiti için bu verileri makine öğrenmesi modelleriyle tarayan bir araç.
4.  **Gelişmiş Python Log Parsers:** Standart formatta olmayan (custom application logs) verileri AI yardımıyla parse eden ve otomatik olarak Wazuh'un anlayabileceği JSON formatına çeviren bir parser.
5.  **Otonom Phishing Analiz Laboratuvarı:** Şüpheli e-postaları bir sandbox ortamında açan, linkleri ve ekleri Python scriptleri ile analiz eden ve sonucu bir rapor olarak sunan bir ajan.
6.  **Zafiyet Tarama ve Otomatik Raporlama:** Nmap veya OpenVAS sonuçlarını alıp, bulunan zafiyetleri açıklayan ve şirketin iç dökümantasyonuna göre risk puanlaması yapan bir AI entegrasyonu.
7.  **Saldırı Yüzeyi İzleyici (Attack Surface Monitor):** Python ile kurumun dış dünyaya açık domain, IP ve portlarını düzenli tarayan ve değişiklikleri (yeni açılan bir port gibi) anında bildiren bir araç.
8.  **Honey-Pot Veri Analizörü:** Bir Honeypot'a gelen saldırı verilerini analiz ederek saldırganların kullandığı yeni teknikleri (TTPs) çıkaran ve bunları MITRE ATT&CK matrisiyle eşleştiren bir sistem.
9.  **AI Destekli Log Azaltma (Log Noise Reduction):** SIEM sistemlerini meşgul eden "noise" (gürültü) seviyesindeki logları tespit edip filtreleyen, sadece gerçekten önemli olanları öne çıkaran bir Python aracı.
10. **Siber Güvenlik Eğitim Botu (CTF Yardımcısı):** Güvenlik açıklarını öğrenmek isteyenler için CTF (Capture The Flag) sorularında ipuçları veren, ancak direkt cevabı söylemek yerine mantığı anlatan bir AI ajanı.
