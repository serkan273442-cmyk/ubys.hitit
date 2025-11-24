# UBYS Clone - Deployment Rehberi

## 📦 Projeniz Yayına Hazır!

### ✅ Proje Özellikleri:
- ✅ Hitit Üniversitesi giriş sayfası
- ✅ Kullanıcı doğrulama sistemi (224511057 / fifa2014)
- ✅ Dashboard sayfası
- ✅ Profil fotoğrafı
- ✅ Çıkış butonu
- ✅ Widget sistemi
- ✅ Hata yok, build başarılı!

---

## 🚀 YAYINLAMA YÖNTEMLERİ

### YÖNTEM 1: Vercel (ÖNERİLEN - En Kolay)

1. **Vercel'e Git:**
   - https://vercel.com adresine gidin
   - "Sign Up" ile GitHub hesabınızla üye olun

2. **Projeyi Yükle:**
   - Dashboard'da "Add New Project" tıklayın
   - "Import Git Repository" yerine "Deploy with Vercel CLI" seçin
   - VEYA: Projeyi GitHub'a yükleyip oradan import edin

3. **Ayarlar:**
   - Framework Preset: **Next.js**
   - Build Command: `npm run build` veya `bun run build`
   - Output Directory: `.next`
   - Install Command: `npm install` veya `bun install`

4. **Deploy:**
   - "Deploy" butonuna tıklayın
   - 2-3 dakika bekleyin
   - Siteniz hazır! 🎉

---

### YÖNTEM 2: Netlify

1. **Netlify'a Git:**
   - https://netlify.com adresine gidin
   - GitHub ile giriş yapın

2. **Manuel Upload:**
   - "Sites" → "Add new site" → "Deploy manually"
   - Proje klasörünü sürükleyip bırakın

3. **Ayarlar:**
   - Build command: `npm run build`
   - Publish directory: `.next`

4. **Deploy:**
   - Otomatik olarak yayınlanacak! 🎉

---

### YÖNTEM 3: GitHub Pages + Cloudflare Pages

Bu yöntem daha gelişmiş kullanıcılar içindir.

---

## 🔧 Lokal Test

Yayınlamadan önce lokal olarak test edin:

```bash
# Development server
bun run dev

# Production build test
bun run build
bun run start
```

---

## 🎯 Giriş Bilgileri

- **Kullanıcı Adı:** 224511057
- **Şifre:** fifa2014

---

## 📝 Notlar

- Next.js 15 kullanıldığı için server-side rendering var
- Statik export değil, dynamic deployment gerekli
- Vercel veya Netlify önerilir
- GitHub Pages tam uyumlu değil

---

## 🆘 Sorun mu var?

1. Build hatası alırsanız: `bun install` komutunu çalıştırın
2. Deployment hatası alırsanız: Node.js versiyonunu 18+ yapın
3. Sayfa yüklenmiyor: Cache temizleyin (Ctrl+F5)

---

**İyi Yayınlar! 🚀**
