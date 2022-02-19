# ML_for_real_estate_classification. 

## Objectif : 
Caractériser le marché de l’immobilier à Paris à l'aide d'algorithmes de clustering et prédire le prix d'un actif immobilier.
La méthode utilisé pour la prédiction d'un actif immobilier est une régression Lasso.

## Dictionnaire des variables :  
id_mutation : Identifiant de mutation (non stable, sert à grouper les lignes).  
date_mutation : Date de la mutation au format ISO-8601 (YYYY-MM-DD).  
numero_disposition : Numéro de disposition.  
valeur_fonciere : Valeur foncière (séparateur décimal = point).  
adresse_numero : Numéro de l'adresse.  
adresse_suffixe : Suffixe du numéro de l'adresse (B, T, Q). 
adresse_code_voie : Code FANTOIR de la voie (4 caractères). 
adresse_nom_voie : Nom de la voie de l'adresse. 
code_postal : Code postal (5 caractères). 
code_commune : Code commune INSEE (5 caractères). nom_commune : Nom de la commune (accentué)
code_commune : Code commune INSEE (5 caractères).  
ancien_code_commune : Ancien code commune INSEE (si différent lors de la mutation)
ancien_nom_commune : Ancien nom de la commune (si différent lors de la mutation)
code_departement : Code département INSEE (2 ou 3 caractères)
id_parcelle : Identifiant de parcelle (14 caractères)
ancien_id_parcelle : Ancien identifiant de parcelle (si différent lors de la mutation)
numero_volume : Numéro de volume
lot_1_numero : Numéro du lot 1
lot_1_surface_carrez : Surface Carrez du lot 1
lot_2_numero : Numéro du lot 2
lot_2_surface_carrez : Surface Carrez du lot 2
lot_3_numero : Numéro du lot 3
lot_3_surface_carrez : Surface Carrez du lot 3
lot_4_numero : Numéro du lot 4
lot_4_surface_carrez : Surface Carrez du lot 4
lot_5_numero : Numéro du lot 5
lot_5_surface_carrez : Surface Carrez du lot 5
nombre_lots : Nombre de lots
code_type_local : Code de type de local
type_local : Libellé du type de local
surface_reelle_bati : Surface réelle du bâti
nombre_pieces_principales : Nombre de pièces principales
code_nature_culture : Code de nature de culture
nature_culture : Libellé de nature de culture
code_nature_culture_speciale : Code de nature de culture spéciale
nature_culture_speciale : Libellé de nature de culture spéciale
surface_terrain : Surface du terrain
longitude : Longitude du centre de la parcelle concernée (WGS-84)
latitude : Latitude du centre de la parcelle concernée (WGS
 
