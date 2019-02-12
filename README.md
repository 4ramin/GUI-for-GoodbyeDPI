# GoodByeDPI GUI

[GoodByeDPI](https://github.com/ValdikSS/GoodbyeDPI) 안티 검열을 위한 프로그램.

> 링크 다운로드
>
> 원 저자 (터키어)
>
>[32 Bit](https://github.com/hex4d0r/GUI-for-GoodbyeDPI/releases/download/v1.0/GoodByeDPI_GUI_32Bit.zip)
>
>[64 Bit](https://github.com/hex4d0r/GUI-for-GoodbyeDPI/releases/download/v1.0/GoodByeDPI_GUI_64Bit.zip)
>
> 한글 번역 본
>
>[64 Bit](https://github.com/hex4d0r/GUI-for-GoodbyeDPI/releases/download/v1.0.2k/GoodByeDPI_GUI_64Bit.zip)
>

# 간단 요약
>
> 위 프로그램은 DNS(1.1.1.1)으로 변경하여 감지를 피하는 방식입니다.
>
> 빌드 및 소스코드 변경이 필요 할 경우 다음과 같은 환경 세팅이 필요합니다.

# 환경 세팅
>
>(Link) Visual Studio 2017 : (ttps://support.microsoft.com/tr-tr/help/2977003/the-latest-supported-visual-c-downloads)
>
>(Link) Qt : (https://www.qt.io/download)

# 빌드 환경
>
> OS : Windows
> 컴파일러 : MSVC-2017(64Bit) / MinGW-5.3.0(32Bit) 
> Qt : 4.7.2

-------
# Kullanım

Parametrelerin tam olarak kayıt edilebilmesi için Ayarlar penceresini **kapatıp** çalıştırmanız gerekli. Sonraki güncellemede eklenecek. Ana ekrandaki **Log** bölümünden uygulamanın düzgün çalışıp çalışmadığını kontrol edebilirsiniz, herhangi bir problem yaşadığınızda bildirmekten çekinmeyin.

> 64Bit Sürümü kullanmak için VC++ 2017 paketini yüklemeniz gerekmektedir.
>
> Link: [Visual Studio 2017](https://support.microsoft.com/tr-tr/help/2977003/the-latest-supported-visual-c-downloads)

Başlangıçta özel bir ayar yapmanıza gerek yoktur. **Başlat** butonuna tıklayıp sansürsüz internetin keyfini çıkarabilirsiniz. Özel Ayarlar isteğe bağlı şekilde düzenlenebilir. İlk açılışta en uygun ayar **Ön Tanımlı** olarak ayarlanmıştır.

**Windows DNS adresini kendiniz değiştirmeniz gerekmektedir. Aksi halde kuvvetle muhtemel engellenmiş sitelere erişim sağlayamayacaksınız.**

## Kaynak Koddan Derleme

Yazılım MSVC-2017(64Bit Versiyon) ve MinGW-5.3.0(32Bit Versiyon) versiyonları ile derlenip **test** edilmiştir. Sadece bu derleyicileri kullanma zorunluluğu yoktur. Qt Framework Online Installer ile kurulum gerçekleştirirken, **MSVC ve MinGW derleyicilerinin yüklenmesi için işaretlemeyi unutmayın**.

Qt Creator'ı başlattıktan sonra File - Open File tıklayıp **.pro** uzantılı dosyayı seçin. Sonraki ekranda Configure butonuna basarak derleyiciniz için gerekli ayarlamaları yaptıktan sonra Build butonuna basarak yazılımı derleyebilirsiniz. Ardından Debug veya Release dizininde windeployqt uygulaması ile yazılımın çalışabilmesi için gerekli olan Qt kütüphanelerini otomatik şekilde kopyalayabilirsiniz.

## GoodByeDPI'ı Kaynak Koddan Derleme

> [Google Docs](https://docs.google.com/document/d/1LMGmFVu17NKItqTpJKGKXMhX58xWcCJPezddCo73e7c/edit?usp=sharing)

## İleriki Sürümlerde Eklenmesi Planlanan/Beklenen Özellikler
|Özellik| İyileştirme |
|--| --|
| Çalışma Saatleri Ayarlama |Parametre Sisteminin Yeniden Kodlanması|
| Güncelleme Yöneticisi  |Daha İyi Hata Tespiti|
| Sistem DNS'i Değiştirebilme|Arayüzde Yapılacak Değişiklikler |

## Bağış

Destek olmak için,

[Patreon](https://www.patreon.com/hex4d0r)