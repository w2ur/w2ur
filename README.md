# William Revah

Head of Digital & Data — Large Customers @ ENGIE S&EM. Paris.

Je construis pour comprendre. C'est la seule méthode que je connaisse
pour savoir ce qu'une technologie change vraiment, plutôt que ce
qu'on en dit. J'ai appris Ruby et Python en autodidacte, écrit mon
premier outil professionnel en 2017, et je n'ai jamais été
développeur. L'IA a levé la contrainte : ce qui prenait des mois
prend des soirées.

Ici, des projets construits pour de vrai — pas des démonstrations.
Ils tournent, et quelqu'un s'en sert (parfois moi seul, ce qui reste
un utilisateur difficile à satisfaire).

## Applications

**[midas](https://github.com/w2ur/midas)** — Dix agents IA gèrent dix
portefeuilles, en public, tous les jours. Un portefeuille fantôme tiré
à pile ou face tourne en parallèle : c'est ce qui transforme « talent
ou chance ? » en question qu'on peut trancher plutôt qu'en sujet de
conversation. Le moteur est ouvert —
[midas-core](https://github.com/w2ur/midas-core), MIT.
[En direct ici](https://midas.revah.paris).

**[Untilt](https://untilt.app)** — Des outils pour penser droit, parce
que notre cerveau nous ment et qu'il vaut mieux le savoir. Le premier,
Doxa, passe une décision au crible de 61 biais cognitifs et rend un
rapport plutôt qu'une note. Les sources sont citées, et vérifiées :
153 références, dont 138 retrouvées une à une dans Crossref. Le second
est Elenchus, juste en dessous.

**[Elenchus](https://chromewebstore.google.com/detail/elenchus/bodfmokjnmkkdobfcnfbplnbplgdbfgl)** —
Extension Chrome qui analyse la qualité du raisonnement d'une page :
21 types de sophismes, citations exactes à l'appui. Elle ne vérifie
pas si c'est vrai, seulement si ça tient debout, et la distinction est
tout l'intérêt. 21 analyses gratuites par jour, sans clé API.
[Présentation ici](https://elenchus.untilt.app).

**[my-tsundoku](https://github.com/w2ur/my-tsundoku)** — Application
web bilingue et hors-ligne pour tenir sa pile à lire sur un tableau
kanban. Un Tsundoku n'est pas une dette, c'est une réserve de
surprises. TypeScript. [En ligne ici](https://www.my-tsundoku.app).

**[pogofish](https://github.com/w2ur/pogofish)** — Entraîner une IA à
un jeu de plateau oublié, puis mesurer ce qu'elle vaut vraiment. La
mesure s'est révélée la partie difficile : la première ne tenait pas,
il a fallu tout refaire avec des critères posés à l'avance. AlphaZero
en Rust. [Le récit, et la partie jouable](https://william.revah.paris/stories/pogofish/).

**[drift](https://github.com/w2ur/drift)** — Jeu 3D en raymarching
dans un seul fichier HTML, sous les 200 lignes et sans aucune
dépendance. [Jouable ici](https://william.revah.paris/drift.html).

## Paquets et outillage

**[free-image-source](https://www.npmjs.com/package/free-image-source)** —
Trouver sur Wikimedia une image qu'on a réellement le droit de
republier, avec l'attribution qui va avec. Chercher est la partie
facile ; la partie difficile est que Wikimedia héberge quantité
d'images qu'on ne peut pas réutiliser, et qu'elles ne se présentent
pas comme telles. Six licences en liste blanche, zéro dépendance.
`npm i free-image-source`

**[french-sentences](https://www.npmjs.com/package/french-sentences)** —
Découper un texte français en phrases sans buter sur `M. Dupont`,
`av. J.-C.` ou un dialogue entre guillemets — ce qu'`Intl.Segmenter`
ne sait pas faire. 35 abréviations, zéro dépendance.
`npm i french-sentences`

**[claude-code-setup](https://github.com/w2ur/claude-code-setup)** —
Les hooks, agents et commandes qui font tourner une dizaine
d'applications personnelles. Je ne relis pas chaque diff : des
garde-fous s'en chargent (relecture automatique, tests, un build qui
bloque la mise en ligne s'il casse), et je lis ce qu'ils trouvent.
L'atelier plutôt que le meuble. MIT.

## Ailleurs

- [william.revah.paris](https://william.revah.paris) — les projets, et les récits qui vont avec
- [LinkedIn](https://linkedin.com/in/williamrevah)
- [W ou la lettre d'un adulte](https://steady.page/fr/w-ou-la-lettre-dun-adulte/posts) — mon infolettre : lectures, expositions, IA, biais cognitifs, et le reste. Écrite à la main.
