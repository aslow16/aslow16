# Vérification du drapeau du Népal — 23 octobre 2026

**Aucune source documentaire n'a pu être consultée avec succès pendant cette tentative.**
Ce fichier décrit des résultats réseau ; ce n'est pas une preuve factuelle et il ne doit pas alimenter les champs `sources` ou `verified_claims` de l'épisode.

## Résultats observés

- Candidat PDF : <https://giwmscdnone.gov.np/media/pdf_upload/Constitution%20of%20Nepal%20%282%29_1igzcvh.pdf>.
  Le tunnel HTTPS a été établi (`HTTP/1.1 200`), puis la requête a reçu `HTTP/2 503`, type `text/plain`, 91 octets. Corps : `upstream connect error or disconnect/reset before headers. reset reason: connection timeout`.
  Le chemin du document était un candidat et son existence n'est pas confirmée. Aucun PDF n'a été obtenu.
- <https://lawcommission.gov.np/> : erreur curl 22, HTTP cible non obtenu (`000`), réponse 403 avant établissement de la requête HTTPS au site.
- Candidat <https://www.mof.gov.np/uploads/document/file/Constitution%20of%20Nepal_20160202071333.pdf> : même refus 403 avant réponse HTTP cible. Existence du fichier non confirmée.
- Candidat <https://mofa.gov.np/wp-content/uploads/2018/02/Constitution-of-Nepal.pdf> : même refus 403 avant réponse HTTP cible. Existence du fichier non confirmée.
- Candidat <https://www.constituteproject.org/constitution/Nepal_2015.pdf> : même refus 403 avant réponse HTTP cible. Le document n'a pas été lu.
  Une nouvelle tentative après la sauvegarde d'une demande d'autorisation réseau pour ce domaine a produit le même résultat ; la sauvegarde du brouillon n'établit pas une application immédiate au réseau de cette instance.

Toutes les requêtes ont conservé la vérification TLS et suivi les redirections normalement. Aucun contournement réseau ni changement de politique n'a été appliqué. Aucun contenu GitHub n'a été utilisé.

## Points à vérifier avant publication

Le texte de l'épisode reste un brouillon. Les quatre points à vérifier sont :

1. La forme composée de deux triangles ou fanions.
2. Le fond cramoisi et la bordure bleue.
3. La lune blanche en haut et le soleil blanc en bas.
4. Les instructions géométriques de construction dans la Constitution népalaise.

Lorsque le texte officiel sera accessible, relever les passages exacts et les numéros de page/article/annexe, enregistrer le document obtenu et son URL finale, puis seulement renseigner une date de consultation et les affirmations effectivement vérifiées.

## Recommandations pour le rendu

- Conserver `status: "draft"`, `sources: []` et `verified_claims: []` tant que la vérification documentaire n'a pas abouti.
- Ne pas utiliser les formulations « seul drapeau non rectangulaire au monde » ou une explication historique des symboles sans source précise.
- Présenter les animations comme des schémas simplifiés : elles ne sont pas une reproduction officielle géométriquement exacte du drapeau.
- Ne pas publier automatiquement le premier rendu de travail non vérifié.
