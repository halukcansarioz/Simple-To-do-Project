# ✅ Simple To-do Project
### (Internet Computer Protocol (ICP) Üzerinde Motoko ile Yazılmış Görev Yönetim Uygulaması)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Motoko](https://img.shields.io/badge/Motoko-FF6B00?style=flat&logo=dfinity&logoColor=white)](#)
[![Internet Computer](https://img.shields.io/badge/Internet%20Computer-000000?style=flat&logo=dfinity&logoColor=white)](#)
[![Made with Learning](https://img.shields.io/badge/Made%20with-Learning-1f425f.svg)](#)

Bu repo, Internet Computer Protocol (ICP) ekosisteminde **Motoko** programlama dili kullanılarak geliştirilmiş basit bir görev yönetimi (to-do) uygulamasıdır. Merkeziyetsiz uygulama (dApp) geliştirme pratiği için hazırlanmıştır.

## 📚 İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Özellikler](#özellikler)
- [Teknoloji Yığını](#teknoloji-yığını)
- [Kurulum ve Kullanım](#kurulum-ve-kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Katkıda Bulunma](#katkıda-bulunma)
- [İletişim](#iletisim)
- [Lisans](#lisans)

---

## Proje Hakkında
Ankara Üniversitesi Bilgisayar Mühendisliği'nden mezun olduktan sonra kendimi geliştirme sürecimin bir parçası olan bu proje; Internet Computer Protocol (ICP) üzerinde çalışan merkeziyetsiz bir görev yönetimi uygulamasıdır. Motoko dili ile yazılmış olup, blockchain tabanlı uygulama geliştirme becerilerini pekiştirmek amacıyla oluşturulmuştur.

* **Geliştirici:** Haluk Can SARIÖZ
* **Tür:** Merkeziyetsiz Uygulama (dApp)
* **Platform:** Internet Computer Protocol (ICP)
* **Amaç:** Motoko ve ICP ekosistemini uygulamalı olarak öğrenmek

---

## Özellikler
* **Görev Ekleme:** Yeni yapılacak işleri listeye hızlıca ekleyebilme.
* **Görev Tamamlama:** Tamamlanan görevleri işaretleme veya üzerini çizme.
* **Görev Silme:** İstenmeyen veya bitmiş görevleri listeden kaldırma.
* **Merkeziyetsiz Yapı:** ICP altyapısında çalışan akıllı sözleşme (canister) mimarisi.

---

## Teknoloji Yığını

| Katman | Teknoloji |
|--------|-----------|
| **Programlama Dili** | Motoko |
| **Platform** | Internet Computer Protocol (ICP) |
| **Geliştirme Ortamı** | DFX SDK |
| **Versiyon Kontrol** | Git & GitHub |

---

## Kurulum ve Kullanım

### Ön Gereksinimler
Projeyi yerel makinenizde çalıştırmak için aşağıdaki araçların kurulu olduğundan emin olun:
* [DFX SDK](https://internetcomputer.org/docs/current/developer-docs/setup/install)
* [Node.js](https://nodejs.org/) (ICP geliştirme ortamı için)
* Git

### Kurulum Adımları

**1. Depoyu klonlayın:**
```bash
git clone https://github.com/halukcansarioz/Simple-To-do-Project.git
```

**2. Proje dizinine gidin:**
```bash
cd Simple-To-do-Project
```

**3. ICP yerel ağını başlatın:**
```bash
dfx start --background
```

**4. Canister'ı derleyin ve dağıtın:**
```bash
dfx deploy
```

**5. Uygulamaya erişin:**
Dağıtım tamamlandıktan sonra terminalde görüntülenen yerel adresten (genellikle `http://127.0.0.1:4943`) uygulamaya erişebilirsiniz.

---

## Proje Yapısı
```text
Simple-To-do-Project/
├── Main.mo            # Motoko akıllı sözleşmesi (ana uygulama mantığı)
├── README.md          # Proje dökümantasyonu
└── .gitattributes     # Git yapılandırma dosyası
```

> ℹ️ **Not:** Bu proje, Internet Computer Protocol (ICP) üzerinde çalışan bir akıllı sözleşme (canister) olarak tasarlanmıştır. Kullanıcı arayüzü, ICP'nin sunduğu Candid arayüzü veya ayrı bir frontend canister'ı aracılığıyla sağlanabilir.

---

## Katkıda Bulunma
Katkılarınız, hata bildirimleriniz ve özellik istekleriniz memnuniyetle karşılanır!

1. Bu depoyu **Fork**'layın.
2. Bir **Branch** oluşturun (`git checkout -b feature/YeniOzellik`).
3. Değişikliklerinizi **Commit** edin (`git commit -m 'Ekleme: Yeni özellik'`).
4. Kodlarınızı **Push**'layın (`git push origin feature/YeniOzellik`).
5. Bir **Pull Request** açın.

---

<a name="iletisim"></a>
## İletişim
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- E-posta: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*Bu dApp projesini faydalı bulduysanız ⭐ vermeyi unutmayın!*

---

## Lisans
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
