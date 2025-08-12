# Job Board App

Job Board App adalah platform web yang menghubungkan pencari kerja dengan perusahaan.  
Aplikasi ini menyediakan fitur untuk posting lowongan, melamar pekerjaan, membuat CV otomatis, melakukan penilaian skill, dan berlangganan fitur premium.


---

## Fitur Utama

- **Job Listing** – Perusahaan dapat membuat, mengedit, dan menghapus lowongan.
- **Job Application** – Pencari kerja dapat melamar pekerjaan secara langsung.
- **CV Generator** – Membuat CV otomatis dengan template profesional.
- **Skill Assessment** – Uji kemampuan untuk meningkatkan profil kandidat.
- **Subscription Premium** – Akses fitur eksklusif dengan sistem berlangganan.
- **Company Review** – Penilaian perusahaan oleh kandidat.

---

## Tech Stack

**Frontend**
- Next.js 14
- Tailwind CSS
- Axios

**Backend**
- Express.js
- PostgreSQL + Prisma ORM
- JWT Authentication

**Deployment**
- Frontend: Vercel
- Backend: Render / Railway
- Database: Supabase / Neon

---

## Struktur Folder

```

job-board/
│
├── backend/         # API server
│   ├── src/
│   ├── prisma/
│   ├── package.json
│
├── frontend/        # Next.js app
│   ├── src/
│   ├── public/
│   ├── package.json
│
├── README.md
└── docs/images/     # Screenshot, demo gif

````

---

## Cara Menjalankan

### 1. Clone Repo
```bash
git clone https://github.com/adlinoor/job-board.git
cd job-board
````

### 2. Jalankan Backend

```bash
cd backend
npm install
npx prisma migrate dev
npm run dev
```

### 3. Jalankan Frontend

```bash
cd frontend
npm install
npm run dev
```

Aplikasi frontend berjalan di `http://localhost:3000`
Backend berjalan di `http://localhost:5000`

---


## Catatan

Proyek ini diadaptasi dari [Final Project API](https://github.com/Vzan99/Final-Project-API) & [Final Project Web](https://github.com/Vzan99/Final-Project-Web) yang dikerjakan secara kolaboratif.
Repo ini digunakan untuk **portofolio pribadi** dan penyesuaian struktur.

---

## Kontributor Asli

* [Prasetyo Aji](https://github.com/Vzan99)
* [Adli Noor](https://github.com/adlinoor)
* [Dewa Bagus](https://github.com/kusuma446)
