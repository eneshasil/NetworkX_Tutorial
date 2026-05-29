# NetworkX ve Ağ Analizi Ders Notu

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) [![NetworkX](https://img.shields.io/badge/NetworkX-3.0%2B-F15A24?style=for-the-badge&logo=networkx&logoColor=white)](https://networkx.org/) [![Quarto](https://img.shields.io/badge/Quarto-Website-75C790?style=for-the-badge&logo=quarto&logoColor=white)](https://quarto.org/) [![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Canlı-22C55E?style=for-the-badge&logo=github&logoColor=white)](https://eneshasil.github.io/NetworkX_Tutorial/)

Bu depo, **IST5128 - Veri Düzenleme ve Görselleştirme** dersi kapsamında **Abdullah Enes Haşıl (255B7018)** tarafından hazırlanan, Python'ın en popüler ağ analizi kütüphanesi **NetworkX** üzerine kurulmuş kapsamlı, interaktif ve modern ders notlarını içermektedir.

Ders notu materyali, teorik graf teorisi kavramlarını pratik Python kodlarıyla birleştiren ve tarayıcı üzerinde canlı fizik tabanlı ağ görselleştirmeleri sunan modern bir web sitesi olarak tasarlanmıştır.

> **Ders notu web sitesine canlı olarak ulaşmak için:** [eneshasil.github.io/NetworkX_Tutorial/](https://eneshasil.github.io/NetworkX_Tutorial/)

------------------------------------------------------------------------

## Ders İçeriği ve Bölüm Detayları

Ders notu serisi 5 ana bölümden oluşmakta ve sırasıyla takip edilmesi önerilmektedir:

| Bölüm | Başlık | Kapsanan Konular & Teknolojiler |
|:---|:---|:---|
| **01** | [Tarihçe & Temel Kavramlar](https://eneshasil.github.io/NetworkX_Tutorial/01_tarihce_temelkavramlar.html) | Graf teorisinin doğuşu (Königsberg'in Yedi Köprüsü), Leonhard Euler, düğüm/kenar ekleme metotları, Python nesnelerinin düğüm olma şartları ve istisnalar. |
| **02** | [Eleman İnceleme & Öznitelikler](https://eneshasil.github.io/NetworkX_Tutorial/02_elemanlar_oznitelikler.html) | Graf elemanlarını sorgulama (`Set-like Views`), düğüm-kenar komşulukları, dereceler (`degree`), düğümlere/kenarlara özel öznitelikler (dictionary yapıları) ve özel `weight` (ağırlık) kavramı. |
| **03** | [Graf Türleri](https://eneshasil.github.io/NetworkX_Tutorial/03_graf_turleri.html) | Yönsüz (`Graph`), Yönlü (`DiGraph`), Çoklu Yönsüz (`MultiGraph`) ve Çoklu Yönlü (`MultiDiGraph`) yapılar. Giriş-çıkış dereceleri, öncüller/ardıllar ve graf türleri arası dönüşümler. |
| **04** | [Graf Üreteçleri & Algoritmalar](https://eneshasil.github.io/NetworkX_Tutorial/04_uretecler_algoritmalar.html) | Sentetik graf üreteçleri (Complete, Path, Cycle), Rastgele Ağ Modelleri (Erdős-Rényi, Barabási-Albert "Zengin daha da zenginleşir" kuralı). Dijkstra ile En Kısa Yol analizi, Derece, Arasındalık (Betweenness) ve PageRank merkezilik analizleri. |
| **05** | [Görselleştirme & İnteraktif Analiz](https://eneshasil.github.io/NetworkX_Tutorial/05_gorsellestirmeler.html) | Matplotlib ile statik çizimler, konumlandırma düzenleri (`spring`, `circular`), dereceye göre dinamik boyutlandırma ve renklendirme. Tarayıcı içi interaktif fizik tabanlı Pyvis ağ modellemeleri. |

------------------------------------------------------------------------

## Kurulum ve Gereksinimler

Projedeki kodları kendi yerel bilgisayarınızda çalıştırmak veya ders notu sitesini yerel olarak derlemek için aşağıdaki adımları takip edebilirsiniz.

### 1. Python Kütüphanelerinin Kurulumu

Projeyi çalıştırmak için gerekli olan kütüphaneleri `pip` kullanarak tek seferde kurabilirsiniz:

``` bash
pip install networkx matplotlib pyvis pandas ipykernel scipy
```

### 2. Quarto Kurulumu

Ders notları bir **Quarto** projesidir. Projeyi derlemek ve HTML formatına çevirmek için bilgisayarınızda Quarto yüklü olmalıdır. - İşletim sisteminize uygun Quarto kurulum paketini [quarto.org/docs/get-started](https://quarto.org/docs/get-started/) adresinden indirebilirsiniz.

------------------------------------------------------------------------

## Yerel Çalıştırma ve Derleme Kılavuzu

Projeyi klonladıktan sonra yerelinizde test etmek ve geliştirmek için aşağıdaki komutları terminalden çalıştırın:

### Projeyi Canlı Önizleme (Live Preview) Modunda Açmak:

Aşağıdaki komut, yerel bir sunucu başlatır ve herhangi bir `.qmd` dosyasında yaptığınız değişikliği anında tarayıcıda canlı olarak görmenizi sağlar:

``` bash
quarto preview
```

### Projeyi Derlemek (Build/Render):

Tüm sayfaları, kod hücrelerini çalıştırarak statik HTML dosyalarına dönüştürmek ve web sitesini yayına hazırlamak için:

``` bash
quarto render
```

Derleme sonrasında üretilen tüm statik web sitesi dosyaları otomatik olarak `_site` klasörünün altına yerleştirilecektir. Bu klasörün içeriği doğrudan GitHub Pages üzerinden sunulmaktadır.

------------------------------------------------------------------------

## Yazar / Geliştirici

-   **Abdullah Enes Haşıl** - [GitHub Profili](https://github.com/eneshasil)
-   **Öğrenci Numarası:** 255B7018
-   **Ders:** IST5128 - Veri Düzenleme ve Görselleştirme

------------------------------------------------------------------------

## Lisans

Bu proje  amaçlı geliştirilmiş olup, kaynak gösterilerek serbestçe kullanılabilir, geliştirilebilir ve paylaşılabilir.
