# BV-M3U8-Downloader
BV M3U8 Downloader Extension for Google Chrome


English
A modern, elegant Google Chrome Extension (Manifest V3) designed to detect and download .m3u8 (HLS) video streams directly from the web browser. It features a premium dark glassmorphism dashboard, supports AES-128 stream decryption, parallel chunk fetching, and automatic segment merging.

🌟 Key Features
Auto-Detection: Dynamically monitors network traffic and intercepts .m3u8 stream playlist URLs.
Vibrant Badge Indicators: Keeps track of detected streams per active tab and highlights them on the extension icon.
Master Playlist Analysis: Automatically parses multi-quality manifests and lets you choose your desired resolution (e.g., 1080p, 720p, etc.).
AES-128 Decryption: Fully supports encrypted streams by fetching keys and decrypting segments in-browser via the native Web Crypto API (AES-CBC).
Parallel Queue Processor: Features a customizable concurrency slider (1 to 10 connections) to accelerate segment downloads.
Robust Error Handling: Automatically retries failed chunk requests up to 3 times.
Live Performance Dashboard: Shows download speed, percentage progress, elapsed/remaining time (ETA), and estimated file size, along with a scrolling system log.

🚀 Installation Guide
Option 1: Install via Packaged Extension (.crx) - Recommended
Locate the bv-m3u8-downloader.crx file.
Open Google Chrome and go to chrome://extensions/.
Enable "Developer mode" in the top-right corner.
Drag and drop the bv-m3u8-downloader.crx file directly anywhere onto the chrome://extensions/ page.
Click "Add extension" when the confirmation dialog pops up.


📝 How to Use
Pin the BV M3U8 Downloader icon to your Chrome toolbar.
Go to any website containing an HLS video player and start playing a video.
Once a stream is detected, the extension icon badge will count it.
Click the popup and choose "İndir" (Download) to open the download panel.
In the dashboard, configure the filename, select quality/resolution, adjust concurrency, and click "İndirmeyi Başlat" (Start Download).
The compiled .mp4 video file will automatically save to your computer once complete.

Türkçe
Web tarayıcınızdan .m3u8 (HLS) video akışlarını anında tespit etmek ve indirmek için tasarlanmış modern, şık bir Google Chrome Eklentisidir (Manifest V3). Koyu tema cam morfizmine (glassmorphism) sahip bir kontrol paneli, AES-128 şifre çözme desteği, eşzamanlı (paralel) parça indirme ve otomatik video birleştirme motoru içerir.

🌟 Öne Çıkan Özellikler
Otomatik Tespit: Ağ trafiğini dinamik olarak tarayarak .m3u8 oynatma listesi URL'lerini yakalar.
Dinamik Bildirim Rozeti: Aktif sekmedeki tespit edilen akış sayısını eklenti ikonu üzerinde gösterir.
Master Playlist Analizi: Çoklu çözünürlük içeren yayınları çözümler ve istediğiniz kaliteyi (örneğin 1080p, 720p vb.) seçmenize olanak tanır.
AES-128 Şifre Çözme: Şifreli yayınlarda #EXT-X-KEY bilgisini okur, anahtarı çeker ve tarayıcının yerel Web Crypto API'sini (AES-CBC) kullanarak parçaları şifresiz hale getirir.
Paralel Bağlantı Motoru: İndirme işlemini hızlandırmak için 1 ila 10 arasında ayarlanabilir eşzamanlı parça indirme olanağı sunar.
Hata Toleransı: Başarısız olan parça isteklerini otomatik olarak 3 kez tekrar dener.
Canlı İstatistik Paneli: İndirme hızı, ilerleme yüzdesi, geçen/kalan süre, tahmini dosya boyutu ve ayrıntılı bir sistem günlüğü (terminal) sunar.

🚀 Kurulum Adımları
Yöntem 1: Paketlenmiş Eklenti (.crx) ile Kurulum - Önerilen
bv-m3u8-downloader.crx dosyasının konumunu bulun.
Google Chrome tarayıcınızı açın ve adres çubuğuna chrome://extensions/ yazın.
Sağ üst köşedeki "Geliştirici modu" seçeneğini aktif edin.
bv-m3u8-downloader.crx dosyasını sürükleyip doğrudan chrome://extensions/ sayfasının üzerine bırakın.
Çıkan onay penceresinde "Uzantı ekle" butonuna tıklayın.

📝 Nasıl Kullanılır?
BV M3U8 Downloader ikonunu Chrome araç çubuğunuza sabitleyin.
M3U8 video oynatılan herhangi bir web sayfasına gidin ve videoyu oynatın.
Video algılandığında eklenti ikonunda mavi renkli bir bildirim sayısı belirecektir.
İkona tıklayıp "İndir" butonuna basarak indirme panelini açın.
Dosya adını belirleyin, kalitesini seçin, bağlantı sayısını ayarlayıp "İndirmeyi Başlat" butonuna tıklayın.
İndirme bittiğinde birleştirilmiş .mp4 video dosyanız otomatik olarak bilgisayarınıza kaydedilecektir.

📄 Copyright & License
Copyright © 2026 batutekin.com. All Rights Reserved.
