Z V11.1 - CODE COMPLET FINAL
===========================
Marque: Z seulement, bleu #0047BB / rouge #E30613 / noir #0E0D08, griffures tigre
Features:
- Mur Z (X/Twitter) posts/comments miroir profil
- LA ZONE (remplace PK) contrôle territorial
- Arène Plato 8 jeux gagnent vrai ZIA
- Modes Fantôme 100 perles/24h, Agressif 250 perles/2h niv15+ KICK 50 MUTE 30 GEL RUGIR 20
- Gel Alpha Bronze niv25 30min 100 perles Argent niv50 1h30 500 Or niv80 3h 2000 vérifié
- Prison Glace, Tribunal Jungle, Bourse, ZIA BANK
- 12 animaux 3D Pixar: Rex renard Luna loup Shadow panthère Miel abeille Kuro corbeau Aya axolotl Simba lion Tora tigre Bao panda Momo ours Bandit raton Koko koala
- Z-CORE Labo IA: API Externe / Prompt Studio / Fichier Local, niveau min pour tchater, déblocage perles, intégrée dans Meute comme 13e profil
- Live vérifié streamer inscription 5 étapes
- Monnaie ZIA=perles 1 ZIA=100 perles=0.01€
- Chat messages , photo video story

FICHIERS:
- index.html = APP COMPLÈTE (React + Tailwind + Framer Motion + base de données intégrée)
- manifest.json + sw.js + icon-*.png = PWA pour App Store
- 01-Icon-1024.png = icône App Store officielle 1024x1024
- 02-Mur-Z-AppStore.png etc = captures App Store 1290x2796

DEPLOIEMENT:
- Vercel: glisse index.html sur vercel.com > Deploy > URL live en 10 sec
- App Store: va sur pwabuilder.com > colle URL Vercel > Package For Stores > iOS > IPA gratuit
- Median: alternative payante mais plus rapide

BASE DE DONNÉES:
- Collections: z_posts, z_core_messages, z_core, z_v8_mur, z_v10_transactions etc
- Tout en localStorage + IndexedDB simulé, prêt pour vrai backend Firebase/Supabase

Pour Next.js:
- Le fichier index.html contient tout le React, tu peux le mettre dans app/page.tsx avec <iframe> ou extraire le code React.
