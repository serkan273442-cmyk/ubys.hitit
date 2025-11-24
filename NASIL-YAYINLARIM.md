# 🚀 UBYS CLONE - NASIL YAYINLARIM?

## ⚠️ ÖNEMLİ NOT

Bu proje **Next.js** kullandığı için **sadece Vercel veya Netlify** ile yayınlanabilir.
**GitHub Pages** veya basit static hosting **ÇALIŞMAZ!**

---

## ✅ EN KOLAY YÖNTEM: VERCEL (3 ADIM)

### ADIM 1: Vercel Hesabı Aç
1. https://vercel.com adresine git
2. **"Sign Up"** butonuna tıkla
3. **GitHub** ile giriş yap (veya email ile üye ol)

### ADIM 2: Projeyi Yükle
1. Vercel Dashboard'da **"Add New..."** → **"Project"**
2. **"Import Git Repository"** altında **"Continue with GitHub"**
3. GitHub'a proje yükle (veya local klasörden upload et)

### ADIM 3: Deploy
1. Framework Preset otomatik **Next.js** seçilecek
2. **"Deploy"** butonuna tıkla
3. 2-3 dakika bekle
4. **SİTENİZ YAYINDA!** 🎉

**Site URL'iniz:** `https://ubys-clone-xxxx.vercel.app`

---

## 🎯 ALTERNATİF: GitHub ile Vercel (Otomatik)

### ADIM 1: GitHub'a Yükle

Terminalde veya CMD'de:

```bash
cd ubys-clone
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADINIZ/ubys-clone.git
git push -u origin main
```

### ADIM 2: Vercel'e Bağla

1. Vercel Dashboard → **"Add New Project"**
2. **"Import Git Repository"**
3. GitHub repo'nuzu seç
4. **"Deploy"** tıkla
5. BİTTİ! 🎉

---

## 📝 GİRİŞ BİLGİLERİ

Siteniz yayınlandıktan sonra bu bilgilerle giriş yapın:

- **Kullanıcı Adı:** `224511057`
- **Şifre:** `fifa2014`

---

## ❌ ÇALIŞMAYACAK YÖNTEMLER

- ❌ GitHub Pages
- ❌ FTP Upload
- ❌ Basit Web Hosting
- ❌ cPanel Hosting

**NEDEN?** Bu proje server-side rendering kullanıyor, sadece Vercel/Netlify/Railway gibi platformlar destekliyor.

---

## 🆘 SORUN ÇÖZME

### "Deployment Hatası" Alıyorsanız:

1. **Build Command:** `npm run build` veya `bun run build`
2. **Output Directory:** `.next`
3. **Install Command:** `npm install` veya `bun install`
4. **Node Version:** 18.x veya üstü

### "Site Açılmıyor" Hatası:

1. Tarayıcı cache temizle: `Ctrl + F5`
2. 2-3 dakika bekle (ilk yükleme)
3. Vercel/Netlify loglarını kontrol et

---

## 🎉 BAŞARILI DEPLOYMENT SONRASI

Site yayınlandıktan sonra:

1. Vercel/Netlify size bir URL verecek
2. Bu URL'i paylaşabilirsiniz
3. Custom domain bağlayabilirsiniz (opsiyonel)

**İyi Yayınlar! 🚀**

---

## 📞 DESTEK

- Vercel Docs: https://vercel.com/docs
- Next.js Docs: https://nextjs.org/docs
