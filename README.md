# Patliputra VinFast website (single-file version)

Saari images index.html ke andar hi embedded hain. Koi images folder nahi hai.

## GitHub par upload (folder drag nahi karna)
GitHub repo > Add file > Upload files > "choose your files" se ye files select karo:
index.html, vercel.json, package.json, robots.txt, banner-vf-mpv7.jpg (sirf WhatsApp/Google share preview ke liye)

## AI chat (optional)
1. GitHub repo > Add file > Create new file > naam box mein type karo: api/chat.js
2. api/chat.js ka code paste karke Commit karo.
3. Vercel > Settings > Environment Variables > ANTHROPIC_API_KEY add karo, phir redeploy.
Chat iske bina bhi chalti hai (ready-made answers + WhatsApp).

## Vercel
Framework preset: Other. Build command aur output directory khali rakho.
