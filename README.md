# Bulut Biliþim Dersi - Kiþisel Web Sayfasý

Bu proje, Bulut Biliþim dersi kapsamýnda Docker kullanýlarak çalýþtýrýlan ve GitHub Pages üzerinden yayýnlanan kiþisel bir web sayfasýdýr.

* **Öðrenci Adý:** Begüm Aytar
* **Bölüm:** Bilgisayar Programcýlýðý
* **Kullanýlan Teknolojiler:** HTML, CSS, Docker, GitHub, GitHub Pages 

## Docker Çalýþtýrma Komutlarý
Projeyi lokalde Docker üzerinden çalýþtýrmak için aþaðýdaki komutlar kullanýlmýþtýr:

1. Docker image oluþturmak için:
`docker build -t webproje .`

2. Docker container'ý çalýþtýrmak için:
`docker run -d -p 8080:80 webproje`