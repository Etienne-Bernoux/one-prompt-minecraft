# one-prompt-minecraft

Le prompt 

Crée un clone Minecraft jouable dans le navigateur en Three.js, tout en un seul fichier HTML.
Terrain voxel généré procéduralement (bruit simplex), placement/destruction de blocs au clic, textures procédurales pixel-art, éclairage directionnel avec ombres, brouillard atmosphérique.
Contrôles clavier AZERTY français : utilise e.key (pas e.code) pour les touches — Z=avancer, S=reculer, Q=gauche, D=droite, Espace=sauter. Pour la caméra : pointer lock obligatoire avec fallback sur delta souris (movementX/Y) — ne jamais utiliser la position absolue de la souris. Vérifier que Q tourne à gauche et D à droite.
Rendu : DoubleSide sur tous les matériaux pour éviter les faces transparentes. Reconstruire les chunks voisins quand un nouveau chunk charge.
