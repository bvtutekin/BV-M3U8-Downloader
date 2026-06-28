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


📄 Copyright & License
Copyright © 2026 batutekin.com. All Rights Reserved.
