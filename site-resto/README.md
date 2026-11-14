# Site restaurant à vendre

Un modèle de site vitrine pour restaurant, bistrot ou café, contenu dans un seul fichier : `index.html`.
Le restaurant de la démo (Garance) est fictif.

## Adapter le site pour un client (environ 30 minutes)

1. Copie `index.html` dans un nouveau dossier au nom du client.
2. Ouvre le fichier et modifie uniquement le bloc `CONFIG` : nom, carte, prix, horaires, adresse, téléphone, avis, textes.
3. Mets `demo: false` pour retirer le bandeau jaune.
4. Change aussi la balise `<title>` et la `<meta name="description">` en haut du fichier (utile pour Google).
5. Remplace les avis par de vrais avis du client (Google, TripAdvisor), jamais par des avis inventés.
6. Les couleurs sont en haut du `<style>` (`--slate`, `--brass`, etc.). Tu peux les accorder à la devanture.

### Recevoir les réservations par e-mail
Crée un formulaire gratuit sur formspree.io avec l'e-mail du restaurant, puis colle l'URL dans `formEndpoint`.
Chaque réservation arrive alors directement dans la boîte mail du restaurant.

## Mettre en ligne (gratuit)
- **Netlify** (le plus simple) : app.netlify.com, puis « Deploy manually », puis glisser-déposer le dossier.
- Nom de domaine (`bistrot-xxx.fr`) : environ 8 à 12 €/an chez OVH ou Gandi, à refacturer au client.

## Tarifs conseillés
| Offre | Prix |
|---|---|
| Création du site + mise en ligne + domaine la 1re année | 450 à 690 € |
| Maintenance (mises à jour de la carte, de l'ardoise, des horaires) | 20 à 30 €/mois |
| Fiche Google Business optimisée (option) | 80 à 150 € |

Deux clients suffisent pour atteindre 1000 €. Avec un abonnement de maintenance, tu as aussi un revenu récurrent.

## Trouver des clients
1. Sur Google Maps, cherche « restaurant » dans ton quartier. Repère ceux qui n'ont **pas de site**, ou un site vieux, lent, ou illisible sur téléphone.
2. Adapte la démo avec **leur** nom, **leur** carte (souvent sur la vitrine ou leurs photos Google) et leurs horaires. Garde `demo: true`.
3. Passe les voir entre 15 h et 17 h, quand le service est calme. Montre le site **sur ton téléphone** : c'est ce qui convainc.
4. Ce que tu peux dire : « J'ai fait une maquette de site pour votre restaurant. Vos clients peuvent voir la carte, les horaires et réserver depuis leur téléphone. Je vous la montre ? Deux minutes. »
5. Demande 30 à 50 % d'acompte à la commande, et le reste à la mise en ligne.

Fais-le aussi pour les boulangeries, coiffeurs, garages et artisans : la même structure s'adapte facilement.

## Côté administratif
Pour facturer légalement, crée une micro-entreprise : c'est gratuit, sur formalites.entreprises.gouv.fr.
