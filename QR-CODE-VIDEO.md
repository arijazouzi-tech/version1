# Solution : quelqu’un scanne le QR code et voit la vidéo sur son téléphone

La vidéo affichée est **video_fabrication_miel.mp4** (étapes de fabrication du miel Bio Bee Énergie Doré).

---

## Quand le site est en ligne (hébergé)

Dès que le site est déployé avec une adresse du type `https://votre-site.com` :

- Le QR code pointe automatiquement vers cette adresse.
- **N’importe qui** peut scanner le QR code avec son téléphone et ouvrir la vidéo (une connexion internet suffit).
- Aucun réglage à faire.

---

## Quand le site tourne en local (sur votre PC)

Pour que **quelqu’un** (vous ou une autre personne) scanne le QR code avec un téléphone et voie la vidéo :

1. **PC et téléphone sur le même Wi‑Fi.**

2. **Trouver l’IP du PC**
   - Ouvrir **Invite de commandes**
   - Taper : `ipconfig`
   - Noter **Adresse IPv4** (ex. `192.168.1.10`)

3. **Sur la page Qualité du site** (sur le PC)
   - Sous le QR code, dans le champ **« IP de ce PC »**, entrer cette IP (ex. `192.168.1.10`).
   - Le QR code se met à jour : il pointe alors vers `http://192.168.1.10:5173/video-fabrication.html`.

4. **Sur le téléphone**
   - Ouvrir l’appareil photo ou une app de scan de QR code.
   - Scanner le QR code affiché sur l’écran du PC.
   - La page vidéo s’ouvre → toucher **« Lancer la vidéo »** pour regarder la vidéo.

**Remarque :** Si l’IP est détectée automatiquement par le navigateur, le champ peut être déjà rempli. Sinon, saisir l’IP à la main.

---

## Récapitulatif

| Situation   | Pour que le scan du QR code ouvre la vidéo sur le téléphone        |
|------------|---------------------------------------------------------------------|
| Site en ligne | Rien à faire, le QR code fonctionne pour tout le monde.          |
| Site en local  | Même Wi‑Fi + indiquer l’IP du PC dans le champ sous le QR code. |
