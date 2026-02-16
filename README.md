# Portal Cabang - Sistem Pengendalian Operasional Multi Outlet

Aplikasi web modern untuk mengelola operasional multi-outlet restoran dengan fitur dashboard, jadwal kerja, tugas harian, manajemen inventori, dan checklist operasional.

## Fitur Utama

- **Dashboard** - Ringkasan KPI outlet real-time (tugas, checklist, reject, rating)
- **Jadwal Kerja** - Manajemen jadwal staff dengan view per shift
- **Tugas Harian** - Penugasan dan tracking completion status
- **Preparation** - Tracking persiapan bahan baku
- **Checklist Operasional** - Link ke Google Forms untuk Pra Opening, During, After Closing
- **Catatan Reject** - Pencatatan barang reject dengan kategori
- **Inventori FIFO/FEFO** - Manajemen stock dengan tracking expiry
- **Log Book** - Komunikasi antar shift
- **Customer Feedback** - Tracking feedback pelanggan dengan rating

## Role & Permission

- **Admin** - Akses penuh semua fitur dan outlet
- **Head Office** - Monitoring multi-outlet, export report
- **Area Manager** - Monitoring area, read-only untuk beberapa fitur
- **Kepala Cabang** - Manajemen single outlet
- **Staff Outlet** - Input data operasional daily

## Multi-Outlet Selection

- Admin/Head Office/Area Manager dapat memilih multiple outlet
- Fitur pencarian outlet untuk memudahkan selection
- Data dashboard dan report dapat di-aggregate per outlet

## Mobile Responsive

- Sidebar collapse/expand untuk mobile/tablet
- Touch-friendly buttons dan forms
- Optimized layout untuk berbagai ukuran layar

## Teknologi

- HTML5 + CSS3 (Tailwind CSS)
- Vanilla JavaScript (ES6+)
- jsPDF untuk export PDF
- Font Awesome Icons
- Google Forms Integration
- LocalStorage untuk data persistence

## Deployment

Deploy ke GitHub Pages atau hosting lainnya. Pastikan:
1. File `index.html` ter-upload ke root folder
2. GitHub Pages enabled di repository settings
3. Service Worker dan manifest berfungsi untuk PWA support

## Setup Local Development

1. Clone repository
2. Open `index.html` di browser
3. Gunakan Dev Tools Console untuk debugging
4. Data disimpan di LocalStorage browser

## License

Proprietary - All rights reserved
