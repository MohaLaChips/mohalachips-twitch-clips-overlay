ZARTOQUE TWITCH CLIPS — OVERLAY OBS
====================================

FONCTIONNEMENT
- Charge jusqu'à 100 clips Twitch aléatoires.
- Joue les clips automatiquement et en boucle.
- Quand les 100 ont été lus, le même lot est remélangé puis recommence.
- Un REROLL recharge une nouvelle sélection aléatoire.
- Bouton SUIVANT pour passer un clip.
- Chaque rechargement complet de la source OBS effectue aussi un reroll.

URL
L'overlay est conçu pour être hébergé en HTTPS (ex. GitHub Pages).
Une fois hébergé :
https://TON-DOMAINE/index.html?channel=TON_PSEUDO_TWITCH

Exemple :
https://TON-DOMAINE/index.html?channel=Zartoque

PARAMÈTRES OPTIONNELS
&count=100   nombre de clips, maximum 100
&info=1      affiche temporairement titre/date/vues (0 pour désactiver)
&muted=0     son actif au démarrage (1 pour muet)

OBS
1. Sources > + > Navigateur.
2. Coller l'URL HTTPS.
3. Largeur 1920, hauteur 1080.
4. Cocher "Contrôler l'audio via OBS" si disponible.
5. Recommandé : "Arrêter la source lorsqu'elle n'est pas visible".

REROLL
- Méthode rapide : clic droit sur la source > Interagir > survoler le coin supérieur droit > REROLL 100.
- Touche R dans la fenêtre Interagir = reroll.
- Touche N ou flèche droite = clip suivant.
- Recharger la source = reroll aussi.

DÉPENDANCE
La liste des clips est obtenue via la passerelle publique twitchapi.teklynk.com.
La lecture elle-même utilise l'embed officiel Twitch clips.twitch.tv.
