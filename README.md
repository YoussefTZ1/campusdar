# CampusDar MVP

Student housing marketplace for Tunisia.

## One-click Vercel deployment

### Option A — Vercel Drop (no GitHub required)

1. Open https://vercel.com/drop
2. Drag the entire project folder or `campusdar-mvp-vercel.zip` into the page.
3. Vercel detects the Vite project and builds it.
4. Click Deploy.
5. Vercel gives you a live `.vercel.app` URL.

### Option B — GitHub + Vercel

1. Create a GitHub repository.
2. Upload this project.
3. In Vercel choose Add New → Project.
4. Import the repository.
5. Framework: Vite (auto-detected).
6. Build command: `npm run build`
7. Output directory: `dist`
8. Click Deploy.

## Local

```bash
npm install
npm run dev
```

The current MVP uses demo data. Supabase should be connected next for real authentication, database, storage, and messaging.
