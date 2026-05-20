# Portfolio Muhammad Ridho Hibatulloh

Selamat datang di portfolio website saya! Website ini dibuat menggunakan HTML, CSS, dan JavaScript murni, siap untuk di-deploy ke Vercel.

## 📋 Struktur File

```
PortPancasila/
├── index.html       # File HTML utama
├── style.css        # File CSS untuk styling
├── script.js        # File JavaScript untuk interaktivitas
├── profil.jpg       # Foto profil (HARUS ditambahkan)
├── README.md        # File ini
└── images/          # Folder untuk project images (opsional)
    ├── pancasila.jpg
    ├── programming.jpg
    └── website.jpg
```

## 🖼️ Setup Gambar

### Foto Profil
1. Simpan pasfoto Anda dengan nama `profil.jpg` di folder utama PortPancasila
2. Ukuran ideal: 300x300px atau lebih besar
3. Format: JPG, PNG, atau WebP

### Gambar Project
Placeholder images sudah tersedia di setiap project card. Untuk menambahkan gambar real:

1. Buat folder `images/` di folder utama
2. Tambahkan gambar untuk setiap project:
   - `pancasila.jpg` - Gambar project Pancasila
   - `programming.jpg` - Gambar project Game Matematika
   - `website.jpg` - Gambar project Detrades

3. Update `index.html` pada project cards:
   ```html
   <!-- Ganti dari placeholder -->
   <div class="placeholder-image">IMAGE PLACEHOLDER</div>
   
   <!-- Menjadi -->
   <img src="images/pancasila.jpg" alt="Proyek Pancasila" class="project-img">
   ```

## 🚀 Deploy ke Vercel

### Cara 1: Melalui GitHub (Recommended)
1. Push repository ini ke GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/username/portfolio.git
   git push -u origin main
   ```

2. Buka https://vercel.com
3. Login dengan GitHub account
4. Click "Add New..." > "Project"
5. Import repository dari GitHub
6. Deploy! Vercel akan otomatis detect settings

### Cara 2: Direct Upload
1. Buka https://vercel.com
2. Drag & drop folder `PortPancasila/` ke dashboard Vercel
3. Vercel akan otomatis generate URL untuk Anda

### Cara 3: Menggunakan Vercel CLI
```bash
npm i -g vercel
cd PortPancasila
vercel
```

## 📝 Catatan Penting

### Mengubah Konten
Semua konten berada di `index.html`. Edit sections berikut:

- **About Me**: Cari `<!-- About Me -->` section
- **Pendidikan**: Cari `.education-list`
- **Skills**: Cari `.skills-list`
- **Prestasi**: Cari `.achievements-list`
- **Projects**: Edit tab contents `#pancasila`, `#programming`, `#website`
- **Kontak**: Update email di contact section

### CSS Customization
Edit `style.css` untuk mengubah:
- Warna: Edit `:root` CSS variables
- Font: Ubah `font-family` di `body`
- Layout: Ubah `grid-template-columns` pada grid layouts

### Color Scheme (Optional)
Current colors di `style.css`:
```css
--primary-color: #1a1a2e;      /* Warna utama */
--secondary-color: #16213e;    /* Warna sekunder */
--accent-color: #0f3460;       /* Warna aksen */
--highlight-color: #e94560;    /* Warna highlight (merah) */
--text-light: #eaeaea;         /* Warna teks terang */
--text-muted: #a8a8a8;         /* Warna teks redup */
--bg-dark: #0f0f1e;            /* Warna background */
```

## 🔗 Update Links

Ganti placeholder links dengan URL real:
- Pancasila Blog: https://pancasilakelompok.blogspot.com/
- Podcast YouTube: Update di `project-links`
- Videografis YouTube: Update di `project-links`
- Proposal Pancasila: Update link
- Laporan Pancasila: Update link
- Detrades Website: https://detrades.id

## 💡 Fitur

✅ Responsive design (mobile, tablet, desktop)
✅ Smooth scrolling
✅ Tab switching untuk projects
✅ Hover effects dan animations
✅ Dark theme
✅ Fast loading
✅ SEO friendly

## 🎨 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📧 Kontak

Email: rhibatulloh5@gmail.com

---

**Dibuat untuk Pradita University** • Teknik Informatika
