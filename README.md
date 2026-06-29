# LE RAT — boutique t-shirt (v2)

Boutique d'un seul fichier : **`index.html`** (image, styles et scripts inclus, ~450 Ko). Rien à installer.

## Ce qui a changé depuis la v1
- **T-shirt réaliste** : tissu avec texture, plis, lumière de studio. La couleur est appliquée par fusion (la vraie technique des mockups), donc le visuel imprimé reste net sur chaque coloris.
- **8 coloris** cliquables : noir, blanc, rouge, vert, jaune, bleu marine, gris chiné, sable. Le grand t-shirt change en direct, plus une galerie « tous les coloris » et des vignettes.
- **Zoom** : clique le t-shirt (ou « Zoomer ») → molette / pince pour agrandir, glisse pour déplacer, double-clic pour réinitialiser.
- **Quantité** +/− avec **Réinitialiser**, **Ajouter au panier**, **Acheter maintenant**.
- **Panier** : modifie les quantités, retire un article, **vide le panier**, livraison offerte dès 60 €.
- **Paiement** : page de paiement complète (récap + carte) qui confirme la commande. Démo front-end pour l'instant.
- Animations : apparition au scroll, header qui se réduit, bandeau défilant, micro-interactions.

## Mettre en ligne sur GitHub Pages
1. Crée un dépôt, dépose `index.html` à la racine.
2. **Settings → Pages** → branche `main`, dossier `/ (root)` → **Save**.
3. En ligne sur `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## À personnaliser (dans le `<script>`, en haut)
- `ORDER_EMAIL` : ton e-mail de contact.
- `COLORS` : ajoute/retire des coloris (clé, nom, couleur hex, intensité reflet/tissage).
- `PRICE`, `SHIP_FREE`, `SHIP_COST` : prix et règles de livraison.

## Encaisser pour de vrai
Le paiement est aujourd'hui une démonstration (aucune carte n'est débitée).
Pour encaisser, branche **Stripe** (lien de paiement ou Stripe Checkout) sur le bouton « Payer » — toute l'interface est déjà prête. Dis-moi quand tu veux, je te le câble.
