# GİRİŞ

> Giriş, araştırma konusu hakkında yapılmış araştırmaların sonuçlarının ve bu alanda cevapsız olan soruların bilimsel
> makalelere dayandırılarak anlatıldığı (kaynak taraması) bölümdür.

Standardalizasyon, geçmişten günümüze yazılım alanında sık gerçekleştirilen bir eylemdir. Öyle ki kimi yazılım geliştiricileri
yalnızca standartlar belirlemekte ve bu standartları uygulamaya geçirmeyi diğer geliştiricilere bırakmaktadır.

Bu duruma pek çok örnek olsa da en çok karşılaşılan birkaç örnek olarak:
C++ dili standartlarının ISO (Internation Organization for Standardization) tarafından
gelişirilmesi veya OpenGL standardlarını belirleyen [Khronous Group Inc.](https://www.khronos.org/) verilebilir.

Bu standartlaşma bir işi yapmanın ancak bir yolu olması adınadır. Karışıklığı minimuma indirmek için yapılan bu standardalizasyonları
geliştirmek adına geliştirdiğim projemin hatalarından ders çıkardığı veya esinlendiği programlamlar aşağıda listelenmiştir.

[//]: # (GENE, projesi yapılan derin literatür araştırması sonucunda benzersiz bir proje olarak ortaya çıkmıştır.)

## Pkgs.org

> [pkgs.org](https://pkgs.org/)

Genel Linux ve BSD paket kayıt sistemlerini tek bir yerde sorgulamak için geliştirilmiş bir web sitesidir.
Sadece paket araması yapabilir; indirme, kaldırma gibi işlemler yapamaz.

## WhoHas

WhoHas, Sistemler arası paket sorgulama aracıdır. Kendisi bir paket yöneticisi değildir. Sadece paket yöneticilerinin
kayıt sistemlerine erişerek sizin aradığınız paket isminin hangi paket yöneticisinde hangi isimle kayıtlı olduğunu
gösterir.

Pkgs.org gibi web tabanlı değil, komut satırı tabanlıdır.

## Pacaptr

Pacaptr, paket yöneticilerinin komutlarını pacman'e benzetmek için geliştirilmiş projelerdir.
Bu projenin gözden kaçırdığı nokta, bir paket ekosistemi standardize etmek için o ekosiste yeni komutlar eklemek, standartlaştırmanın tam tersine,
yeni bir standart oluşturmak ve karmaşayı daha da artırmak anlamına gelmektedir. Bu problemin üstesinden gelmek için
`merge`, yeni bir komut sistemi icad etmeden var olan paket yöneticilerinin komutları ile çalışır.

## Mew

Mew paket yönetici komutlarını standartlaştırma konusunda kullanıcılara yardımcı olmayı hedefleyen ufak çaplı bir
projedir. Mew, `.PO` ([GNU gettext
utilities](https://www.gnu.org/software/gettext/manual/html_node/PO-Files.html))  dosyaları gibi çalışır.
12 github commitinden oluşan mew, basit düzeyde bir python kodudur.
6 yıldır geliştirilmeyen bir koddur.


## Bedrock Linux

Pek bilinmeyen bir Linux dağıtımı olan Bedrock Linux, farklı işletim sistemlerinin programlarını, aynı bilgisayar
üzerinde çalıştırır. Bu sayede bedrock linux, bir çok paket yöneticisini beraber kullanmanıza olanak tanır. ancak
bedrock linux, başlı başına bir işletim sistemi olduğundan, standardalizasyon amacı gütmediğinden ve stabilite, bakım
(maintenance) gibi konularda sıkıntılar yaşadığından dolayı paket yöneticisi standardalizasyonu için uygun değildir.

### Eksi yönleri

- Amacı standardalizasyon olmadığından dolayı yeni bir standart ortaya koyuyor.
- Yeni bir işletim sistemi

## Pacman Rosetta

- Site: https://wiki.archlinux.org/title/Pacman/Rosetta

İnternet üzerinde, paket yönetici komutlarının eşleştirildiği bir dökümandır. Dökümanda yer alan paket yöneticisi sayıları kısıtlıdır.

## Kaynaklar

- yumitude: https://github.com/timols/yumitude Project with the same idea but not implemented.
- MEW: https://github.com/fossasia/mew Project similar to pacaptr.
- whohas: https://github.com/whohas/whohas - A system utility to search from general package registries.
- pacaptr: https://github.com/icy/pacapt - pacman-like syntax for all package managers.
- bedrock linux: https://bedrocklinux.org/0.7/pmm-beta.html package manager manager (a.k.a pmm)

- CPP standartları ISO: https://en.wikipedia.org/wiki/C%2B%2B#:~:text=C%2B%2B%20is%20standardized%20by%20the,known%20as%20C%2B%2B20).
