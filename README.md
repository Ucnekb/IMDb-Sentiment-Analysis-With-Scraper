# IMDb-Sentiment-Analysis-With-Scraper
Bu proje, IMDb'den web scraping yöntemiyle film yorumlarını toplar ve bu yorumlar üzerinde DistilBERT tabanlı bir model kullanarak duygu analizi gerçekleştirir. Proje, yorumların pozitif veya negatif olarak sınıflandırılmasını sağlar ve scraping ile analiz süreçlerini bir arada sunar.


Özellikler
Web Scraper: IMDb'den film yorumlarını toplamak için geliştirilmiştir (PyCharm ile oluşturulmuştur).
Veri İşleme: Toplanan yorumlar temizlenir ve NLP yöntemleriyle analize hazırlanır.
Duygu Analizi: Yorumlar, Transformer tabanlı bir model (DistilBERT) kullanılarak pozitif ya da negatif olarak sınıflandırılır.
Veri Depolama: Çekilen veriler data/ klasöründe saklanır ve işlenir.


GitHub README dosyanız, projenizin ne yaptığını, nasıl çalıştırıldığını ve gerekli detayları içermelidir. İşte size proje odaklı bir README taslağı:

IMDb Duygu Analizi ve Web Scraper
Bu proje, IMDb web sitesinden film yorumlarını toplamak için bir web scraper ve bu yorumlar üzerinde DistilBERT tabanlı duygu analizi modeli kullanarak, yorumların pozitif veya negatif olduğunu sınıflandırır.

Özellikler
Web Scraper: IMDb'den film yorumlarını toplamak için geliştirilmiştir (PyCharm ile oluşturulmuştur).
Veri İşleme: Toplanan yorumlar temizlenir ve NLP yöntemleriyle analize hazırlanır.
Duygu Analizi: Yorumlar, Transformer tabanlı bir model (DistilBERT) kullanılarak pozitif ya da negatif olarak sınıflandırılır.
Veri Depolama: Çekilen veriler data/ klasöründe saklanır ve işlenir.

Kullanım
1. IMDb Yorumlarını Çekmek için Scraper'ı Çalıştırın
Scraper PyCharm ile geliştirilmiştir. scraper/ klasöründeki Python dosyasını çalıştırarak verileri çekebilirsiniz.
Çekilen veriler data/ klasörüne .csv formatında kaydedilir.


Kurulum
Gerekli kütüphaneleri yükleyin:
bash
Kodu kopyala
pip install -r requirements.txt

Scraper için Gerekli Ayarlar:
IMDb scraping işlemi için BeautifulSoup veya Selenium kütüphanelerine ihtiyacınız olacaktır.
Scraper, belirli bir IMDb URL’sinden yorumları çeker.

Duygu Analizi için Modelleri İndirin:
Hugging Face üzerinden distilbert-base-uncased-finetuned-sst-2-english modelini indirin.
Kütüphaneler
Proje aşağıdaki kütüphaneleri kullanır:

Web Scraping: BeautifulSoup, Requests, Selenium
Doğal Dil İşleme: Transformers (Hugging Face), NLTK
Veri İşleme: Pandas, NumPy
Model Eğitimi: PyTorch, Datasets
