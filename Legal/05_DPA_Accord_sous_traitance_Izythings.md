# Accord de traitement des données (DPA) — IZYTHINGS

> **À compléter avant signature** (supprimer ce bloc ensuite)
> - [ ] SIREN exact — [ ] Régions exactes des sous-traitants (Annexe 2) — [ ] Mesures de sécurité réelles (Annexe 3)
> *Annexe aux CGV et au Contrat de bêta-test. Conforme à l'article 28 du RGPD.*

Entre **IZYTHINGS** (SASU, capital 500,00 €, RCS Bobigny **106 000 318**, siège 145 rue de Noisy-le-Sec, CS 20008, 93260 Les Lilas), ci-après le « **Sous-traitant** »,
et le **Client** identifié au bon de commande ou au contrat principal, ci-après le « **Responsable de traitement** ».

## 1. Objet et hiérarchie

Le présent Accord encadre les traitements de données à caractère personnel réalisés par le Sous-traitant pour le compte du Responsable de traitement dans le cadre de la fourniture des services (KarayCRM, Scovi ou autre produit Izythings). En cas de contradiction sur la protection des données, le présent Accord prévaut sur les CGV.

## 2. Description du traitement (Annexe 1)

- **Nature et finalité** : hébergement et exploitation d'un logiciel SaaS de gestion (relation client, interventions, devis/factures, planification, fonctionnalités assistées par IA) pour le compte du Responsable de traitement.
- **Durée** : durée du contrat principal, prolongée le temps nécessaire à la restitution/suppression.
- **Catégories de personnes** : clients et prospects du Responsable de traitement, ses salariés/utilisateurs, ses contacts.
- **Catégories de données** : identité, coordonnées, données professionnelles, données de connexion, contenus métier (interventions, contrats, documents), données de facturation. **Pas de données sensibles requises** ; le Responsable s'engage à ne pas en injecter sans accord préalable.

## 3. Obligations du Sous-traitant

Le Sous-traitant s'engage à :

1. **Traiter sur instruction documentée** du Responsable, y compris pour les transferts hors UE ; informer le Responsable si une instruction lui paraît contraire au RGPD.
2. Garantir la **confidentialité** : seules les personnes habilitées et soumises à une obligation de confidentialité accèdent aux données.
3. Mettre en œuvre les **mesures de sécurité** de l'article 32 (Annexe 3).
4. Respecter les conditions de recours aux **sous-traitants ultérieurs** (article 4).
5. **Assister** le Responsable pour répondre aux demandes d'exercice de droits des personnes, et pour ses obligations de sécurité, notification de violation, analyses d'impact (art. 32 à 36).
6. **Notifier** au Responsable toute violation de données dans les **72 heures** suivant sa connaissance, avec les éléments utiles.
7. Au choix du Responsable, **supprimer ou restituer** les données en fin de prestation, et détruire les copies sauf obligation légale de conservation.
8. Tenir à disposition les informations nécessaires pour démontrer sa conformité et permettre des **audits** raisonnables (1/an, préavis 30 j, sur site ou documentaire).

## 4. Sous-traitants ultérieurs

Le Responsable autorise le recours aux sous-traitants ultérieurs listés en **Annexe 2**. Le Sous-traitant impose à ces tiers des obligations équivalentes au présent Accord et reste responsable de leur exécution. Tout ajout ou remplacement est notifié au Responsable, qui peut s'y opposer pour motif légitime relatif à la protection des données dans un délai de **15 jours**.

## 5. Transferts hors Union européenne

Certains traitements impliquent des sous-traitants ultérieurs établis hors UE, notamment **Anthropic, PBC (États-Unis)** pour les fonctionnalités d'IA. Ces transferts sont encadrés par les **clauses contractuelles types** de la Commission européenne et des mesures complémentaires appropriées. Les données transmises via l'API Anthropic **ne sont pas utilisées pour entraîner ses modèles** et sont limitées au nécessaire.

## 6. Responsabilité et durée

Le présent Accord s'applique pendant toute la durée du contrat principal. La responsabilité au titre du présent Accord s'inscrit dans les limites prévues par le contrat principal, sous réserve des dispositions impératives du RGPD.

---

### Annexe 1 — Détail du traitement
Voir article 2 (à préciser au bon de commande si besoin).

### Annexe 2 — Liste des sous-traitants ultérieurs

| Sous-traitant | Service | Localisation | Transfert hors UE |
| --- | --- | --- | --- |
| Supabase | BDD, auth, stockage | UE *(région à confirmer)* | Non / encadré |
| Vercel | Hébergement, diffusion | UE + US | Oui — CCT |
| Hetzner | Automatisation (VPS) | Allemagne (UE) | Non |
| Anthropic (Claude) | IA | États-Unis | Oui — CCT |
| [Emailing] | Emails | [à confirmer] | [à confirmer] |

### Annexe 3 — Mesures de sécurité (art. 32) — à adapter au réel
Chiffrement en transit (HTTPS/TLS) · contrôle d'accès et authentification · cloisonnement par locataire (RLS Supabase) · journalisation des accès · sauvegardes régulières · gestion des habilitations · politique de mots de passe · revue des sous-traitants.

---

**Signatures**

| Pour le Sous-traitant (Izythings) | Pour le Responsable de traitement (Client) |
| --- | --- |
| M. Pablo Wallace ZOBDA — Président<br>Date :<br>Signature : | [Nom, qualité]<br>Date :<br>Signature : |
