### Contexte et objectifs

L’outil doit répondre aux problématiques du Parc national des Écrins :

* comprendre et visualiser les interactions entre sports de nature et biodiversité
* observer et analyser la fréquentation (notamment lacs, sentiers, zones sensibles)
* croiser les données internes et externes (écocompteurs, pièges photo, refuges, Strava, Outdoorvision, météo…)
* appuyer la gestion, la prévention et la sensibilisation du public

### Proposition détaillée de l’outil
Structuration d'une base de données simple et générique pour importer les données brutes de fréquentation et de biodiversité dans le Parc national des Ecrins. Elle comporterait : les observations de biodiversité, les habitats (zone humide), les objets de comptage. Ces données sont agrégées par mailles et zonages. 

**\*\*1. Maillage spatial
**
* grille homogène (grille 100m ou 250m) couvrant tout le Parc national
* chaque maille agrège : biodiversité, fréquentation, habitats, réglementation, météo, etc.
* permet d’identifier automatiquement les zones à forts enjeux (« points chauds »)

**2. Dashboard gestionnaires**

* synthèse des données de fréquentation : sentiers, écocompteurs, refuges, données mobiles, traces GPS volontaires
* synthèse des données de biodiversité : espèces sensibles/à statut, habitats naturels, observations GeoNature
* zones : cœur de parc, aire d'adhésion
* alertes automatiques : grand volume de fréquentation, intéractions potentielles, périodes sensibles
* outils de comparaison temporelle (année N/N-1, avant/après événement)

**3. Dashboard grand public**

* visualisation simple des zones à enjeux : faune sensible, habitats fragiles, réglementations
* conditions de visite : météo, enneigement, fréquentation estimée
* bonnes pratiques + alternatives d’itinéraires
* intégration possible dans Geotrek ou Destination Écrins

**4. Analyses avancées**

* prédiction d’affluence (modèle météo + historique de fréquentation)
* visualisation des dynamiques hors zones équipées (“trous dans la raquette”)
* corrélation biodiversité ↔ sports de nature (ex : proximité espèces patrimoniales / randonneurs)

**5. Sources de données**

* connecteurs API : GeoNature, Geotrek, Biodiv’Sports, Outdoorvision
* import des données externes : Strava, Inaturalist
* import des données internes : zone humide, cartographie des habitats delphine, GeoNature
* export pour rapports et suivis annuels

* **6. Outils**

