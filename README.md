# 🛒 Mini Sepet Uygulaması

Bu proje, [Next.js](https://nextjs.org) kullanılarak [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app) ile oluşturulmuş modern bir e-ticaret sepet uygulamasıdır.

## 🎯 Proje Hakkında

Bu uygulama, gerçek bir e-ticaret sitesinin sepet fonksiyonlarını simüle eder:

- **Ürün Listesi:** Çeşitli ürünleri görüntüleme
- **Sepet Yönetimi:** Ürün ekleme, çıkarma, miktar değiştirme
- **Responsive Tasarım:** Mobil ve masaüstü uyumlu
- **Veri Saklama:** Sepet verilerini tarayıcıda saklama

## 🚀 Başlangıç

Önce geliştirme sunucusunu çalıştırın:

```bash
npm run dev
# veya
yarn dev
# veya
pnpm dev
# veya
bun dev
```

Tarayıcınızda [http://localhost:3000](http://localhost:3000) adresini açarak sonucu görün.

`app/page.tsx` dosyasını düzenleyerek sayfayı değiştirebilirsiniz. Dosyayı düzenlediğinizde sayfa otomatik olarak güncellenir.

## 🛠️ Kullanılan Teknolojiler

- **Next.js 15** - React framework'ü
- **TypeScript** - Tip güvenliği
- **Tailwind CSS** - Stil framework'ü
- **ShadCN UI** - UI bileşen kütüphanesi
- **Zustand** - State yönetimi
- **Radix UI** - Erişilebilir UI primitives

## 📁 Proje Yapısı

```
src/
├── app/                 # Next.js App Router
│   ├── cart/           # Sepet sayfası
│   ├── page.tsx        # Ana sayfa
│   └── layout.tsx      # Ana layout
├── components/         # React bileşenleri
│   ├── Header.tsx      # Üst menü
│   ├── ProductCard.tsx # Ürün kartı
│   └── ui/            # ShadCN UI bileşenleri
├── data/              # Veri dosyaları
│   └── products.ts    # Ürün listesi
├── store/             # State yönetimi
│   └── cartStore.ts   # Sepet store'u
└── types/             # TypeScript tipleri
    └── index.ts       # Tip tanımları
```

## 🎨 Özellikler

### ✅ Mevcut Özellikler
- Ürün listesi görüntüleme
- Sepete ürün ekleme
- Sepetten ürün çıkarma
- Ürün miktarını değiştirme
- Toplam tutar hesaplama
- Responsive tasarım
- Persistent sepet verisi

### 🔮 Gelecek Özellikler
- Kullanıcı girişi
- Ödeme sistemi
- Ürün kategorileri
- Arama fonksiyonu
- Favori ürünler

## 📱 Kullanım

1. **Ana Sayfa:** Ürünleri görüntüleyin ve "Sepete Ekle" butonuna tıklayın
2. **Sepet:** Üst menüdeki sepet ikonuna tıklayarak sepete gidin
3. **Miktar Değiştirme:** Artı/eksi butonları ile miktar değiştirin
4. **Ürün Silme:** Çöp kutusu ikonuna tıklayarak ürünü silin

## 🔧 Geliştirme Komutları

```bash
npm run dev      # Geliştirme sunucusu (http://localhost:3000)
npm run build    # Production build
npm run start    # Production sunucusu
npm run lint     # Kod kalitesi kontrolü
```



**Not:** Bu proje eğitim amaçlıdır ve gerçek bir e-ticaret sitesi değildir.
