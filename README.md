# 🌸 Birthday Website

## Folder Structure

```
birthday-site/
├── index.html              ← Main website file
├── netlify.toml            ← Netlify config (don't edit)
├── images/
│   ├── gallery/            ← 📸 Add 12-30 photos here (gallery section)
│   │     photo-1.jpg
│   │     photo-2.jpg
│   │     ...
│   ├── love/               ← 💕 Add 6 photos here (Things I Love About You)
│   │     love-1.jpg
│   │     love-2.jpg
│   │     ...
│   ├── moments/            ← 🌸 Add 3 photos here (Moments section)
│   │     moment-1.jpg
│   │     moment-2.jpg
│   │     moment-3.jpg
│   └── hero/               ← Optional: hero background image
└── music/
      song.mp3              ← 🎵 Add your music file here
```

## How to Add Images

1. Add your photos to the correct folder (see above)
2. In `index.html`, search for `<!-- ✏️ EDIT` comments
3. Replace `images/gallery/photo-1.jpg` etc. with your actual filenames

## Deploy to Netlify

1. Push this entire folder to a GitHub repo
2. Go to [netlify.com](https://netlify.com) → New site from Git
3. Select your repo → Deploy site
4. Done! 🎉

## Editing Text

All editable text is marked with `<!-- ✏️ EDIT -->` comments in index.html.
