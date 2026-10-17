# HIKE — suivi en direct

Page publique ouverte par le lien « Partager ma position en direct » de l'appli HIKE
(`https://mariehike.github.io/hike-suivi/?t=<jeton>`).

- La page n'affiche une position qu'avec un jeton valide, pendant 24 h au plus.
- Elle n'utilise que la clé *publishable* de Supabase (publique par nature) et la
  fonction `suivi_en_direct`, la seule ouverte aux visiteurs sans compte.
- Source : `docs/suivi.html` du projet `hike` (modèle : `outils/suivi_modele.html`).
  Après une modification là-bas, recopier le fichier ici sous le nom `index.html`.

Sources : Plan IGN (Géoplateforme) · Leaflet (BSD-2) · police Archivo (OFL, `polices/OFL.txt`).
