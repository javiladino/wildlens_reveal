# -------------------------------------------------------------------

## 1. Ouverture émotionnelle : pourquoi c’est crucial ?

**Message**

- Chaque heure, entre **3 et 4 espèces** disparaissent de la planète (IPBES 2023).
- Parallèlement, l’exploration de forêts tropicales et de fonds marins révèle encore **150 à 200 nouvelles espèces par an**.
- Sans données fiables, la science et la gestion de la biodiversité avancent « dans le brouillard ».

---

## 2. Le problème à résoudre

| Défi | Conséquence |
| --- | --- |
| **Érosion accélérée de la biodiversité** | Chaînes trophiques perturbées, perte de services écosystémiques. |
| **Suivi traditionnel coûteux et lent** | Équipes de terrain limitées ; données qui arrivent trop tard. |
| **Manque de participation citoyenne** | Faible couverture spatiale, sensibilisation limitée. |

> Anecdote : dans le Parc national de la Sierra de las Minas (Guatemala), il a fallu 6 mois et 40 pièges photographiques pour confirmer la présence d’un jaguarondi ; avec WildLens, quelques empreintes photographiées par gardes et randonneurs auraient suffi.
> 

---

## 3. La proposition WildLens

**Diapositive : schéma d’architecture**

- Frontend React ➜ ergonomique, multilingue, PWA hors-ligne.
- Backend Express ➜ orchestration, API REST ouverte.
- IA PyTorch ➜ identification > 90 % de fiabilité (transfer learning).
- PostgreSQL/PostGIS ➜ stockage géospatial prêt pour les cartes de chaleur.
- Apache + SSL ➜ sécurité et montée en charge.

**Valeur** : *de l’empreinte dans la boue à la carte mondiale en quelques secondes*.

---

## 4. Science collective : de la photo au savoir

> Diagramme simple : Utilisateur → IA → Bases de données ouvertes → Chercheurs → Politiques publiques
> 
- **Participation citoyenne** : tout promeneur peut contribuer.
- **Qualité** : validation croisée par les experts, système de réputation.
- **Données FAIR** : API publique sous licence CC-BY-SA.
- **Impact** : alertes précoces sur espèces invasives ou en danger critique.

---

## 5. Bénéfices concrets

| Acteur | Bénéfice |
| --- | --- |
| Biologistes | Inventaires rapides, géolocalisés, datés. |
| Parcs nationaux | Suivi continu à budget réduit. |
| Universitaires | Plus grand jeu de données d’empreintes |
| Citoyens | Apprentissage ludique et sentiment d’utilité. |
| Pouvoirs publics & ONG | Décisions fondées : corridors écologiques, zones de protection. |

---

## 6. Feuille de route

1. **IA multi-espèces** : passer de 20 à 200 espèces (few-shot learning).
2. **Capteurs LoRa** : empreintes + micro-climat pour l’éco-physiologie.
3. **Gamification** : challenges mensuels, badges écologiques.
4. **Tableau d’alerte** : détection auto des invasives.
5. **Interopérabilité** : export vers GBIF, iNaturalist, eBird.

---

## 7. Appel à l’action

> Slide finale avec une grande empreinte et le slogan
> 
> 
> « *Chaque pas que nous laissons sur la terre laisse une trace dans la science.* »
> 
- **Volontaires** : chargez vos photos, validez des enregistrements, partagez l’application.
- **Institutions** : ouvrez vos bases de données, pilotez WildLens dans vos réserves.
- **Financeurs** : 50 k USD couvrent serveurs GPU et déploiement dans trois parcs pilotes.
- **Développeurs** : forkez, proposez des PR ! Licence MIT.

---

## 8. Conclusion inspirante

> « Nous protégeons ce que nous aimons et nous aimons ce que nous connaissons.
> 
> 
> Avec WildLens, le savoir tient dans votre poche et la protection se déploie à l’échelle de la planète. »
>