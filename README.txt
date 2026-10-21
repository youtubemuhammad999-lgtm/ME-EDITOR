ME EDITOR - APK banane ke steps (bina Android Studio ke)

1. github.com par free account banayein (agar nahi hai).
2. New repository banayein (naam: me-editor).
3. Is zip ke andar ki saari files repository mein upload karein
   (Add file > Upload files). Folder .github/workflows/build.yml bhi upload hona chahiye.
   Agar .github folder upload na ho to "Add file > Create new file" mein path likhein
   .github/workflows/build.yml aur build.yml ka text paste kar dein.
4. Repository ke "Actions" tab mein jayein > "Build APK" > "Run workflow".
5. 5 se 10 minute baad run complete hoga. Run kholein, neeche "Artifacts" se
   ME-EDITOR-apk download karein (zip hoga, usme app-debug.apk hai).
6. APK ko phone mein bhejein, install karein. "Unknown sources" ki ijazat dena pad sakti hai.

Note: yeh debug APK hai (personal use ke liye). Play Store ke liye signed release build chahiye.

Support: WhatsApp 0348 6496899 (app ke andar bhi button maujood hai).
Note: AI Script to Video ME EDITOR ke online (Claude) version mein chalta hai. APK mein AI ke liye alag server chahiye hota hai, isliye wahan Script wala box istemal hota hai.

=== AI APK mein chalane ke liye (ek baar ka kaam) ===
1. console.anthropic.com par account banayein, API key banayein aur thora credit daalein (AI ka kharcha yahin se katega).
2. dash.cloudflare.com par free account banayein > Workers & Pages > Create > "Hello World" Worker > Edit code,
   ai-server/worker.js ka saara code paste karein > Deploy.
3. Worker ki Settings > Variables and Secrets mein ANTHROPIC_API_KEY (secret) add karein. Chahein to APP_TOKEN bhi (koi bhi lamba password).
4. Worker ka link (https://....workers.dev) copy karein.
5. www/index.html ke script ke shuru mein const AI_URL='' mein yeh link likh dein (aur token ho to AI_TOKEN mein),
   phir GitHub par dobara upload karke APK banayein. Ya phone mein app ke "AI server settings" mein link paste kar dein.
Khabardar: link kisi ko na dein, warna log aapke credit kharch kar sakte hain.
