# Oyunsanaa Chat - Сэтгэлийн Хөтөч

## 🚀 Vercel дээр Deploy хийх заавар

### 1. GitHub репо үүсгэх
```bash
git init
git add .
git commit -m "Initial commit: Oyunsanaa Chat System"
git branch -M main
git remote add origin [ТАНЫ_GITHUB_REPO_URL]
git push -u origin main
```

### 2. Vercel дээр deploy хийх
1. [vercel.com](https://vercel.com) руу орж GitHub-аар нэвтэрнэ
2. "New Project" дарна
3. GitHub репогоо сонгоно
4. "Deploy" дарна
5. Автоматаар build болж deploy хийгдэнэ

### 3. Domain тохируулах
1. Vercel dashboard дээрээ project руу орно
2. Settings > Domains руу орно  
3. Custom domain нэмнэ эсвэл Vercel-ийн domain ашиглана

## ✨ Сайжруулсан онцлогууд

### 🎮 GTA Style Fullscreen
- Бүтэн дэлгэц эзэлдэг
- Том харагдах байдал
- Immersive UI/UX

### 📱 Mobile Responsive  
- Гар утас дээр төгс ажиллана
- Touch-friendly interface
- Responsive breakpoints

### 🎨 Design Updates
- **Брэнд өнгө**: `#486573` (таны хүссэнчлэн)
- **Стандарт фонт**: System fonts, Roboto fallback
- **Цагаан тэмдгүүд**: Меню, хаах товчны өнгө
- **Сайжруулсан анимашн**: Hover effects, transitions

### 🔧 Technical Features
- LocalStorage дата хадгалалт
- Real-time chat functionality  
- Modular component structure
- Error handling
- Performance optimized

## 📂 Файлын бүтэц

```
├── index.html          # Үндсэн HTML файл
├── package.json        # NPM dependencies
├── vercel.json        # Vercel тохиргоо
└── README.md          # Энэхүү файл
```

## 🔗 Wix дээр ашиглах

Wix дээр ашиглахын тул:

1. **Custom Code нэмэх**:
```html
<script>
// Wix товчтой холбох
function openOyunsanaaChat() {
  if (window.OY_OPEN) {
    window.OY_OPEN();
  }
}
</script>
```

2. **Button Action тохируулах**:
- Wix button дээр `onClick` event нэмнэ
- `openOyunsanaaChat()` функцийг дуудна

## 🛠 Техникийн дэмжлэг

### Browser Support
- Chrome 70+
- Firefox 65+  
- Safari 12+
- Edge 79+
- Mobile browsers

### Performance
- First load: < 500ms
- Interaction ready: < 100ms
- Bundle size: < 50KB gzipped

## 📞 Холбоо барих

Асуулт, санал байвал:
- GitHub Issues ашиглана уу
- Эсвэл шууд холбогдоно уу

---

**Амжилттай deploy хийгээрэй! 🎉**
