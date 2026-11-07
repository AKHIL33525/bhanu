# Anniversary Museum — full reference-inspired version
This React/Vite project rebuilds the full sequence of screens visible in the supplied video: opening letter/gift, flower transition, romantic intro, heart message, anniversary tree, dark museum door, photo exhibit, photo grid, note wall, envelope letter, promise checklist, and anniversary final card.

## Local development
```bash
npm install
npm run dev
```

## Personalize
Edit `src/main.jsx` data object at the top: sender, recipient, anniversary date, days together, promises, quotes.

## Add your photos
Place images into `public/images/` with filenames:
`photo1.jpg`, `photo2.jpg`, `photo3.jpg`, `photo4.jpg`, `photo5.jpg`, `photo6.jpg`.
Replace the photo placeholder assets with your own photos. The gallery is configured to use these filenames.

## Deploy
Push to GitHub, then import the repository into Vercel:
- Framework: Vite
- Build command: `npm run build`
- Output directory: `dist`
