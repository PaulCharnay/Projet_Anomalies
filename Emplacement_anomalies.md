# Emplacement des anomalies générées
Les informations ci-dessous peuvent être retrouvées en lisant le notebook `Fuel_Flow_and_Flight_Phase.ipynb`, stockés dans le NAS, à côté du présent document. Attention, ce notebook contient un tirage aléatoire sans graine, c'est-à-dire qu'il faut se contenter de le lire et ne pas le relancer. Sans quoi, les données générées seraient différentes de celles décrites ici.

20 anomalies ont été générées et incorporées dans 20 fichiers des 128 de l'échantillon de test.
Les anomalies sont des séquences de 55 points issues de la phase 6 des trois premiers vols de l'avion T019. On a donc simplement remplacé des séquences de points relatives à la phase 2 par d'autres issues de phases 6 de vols différents. Voici l'emplacement des anomalies dans l'ensemble de test :

- anomalie I :
-- TS 373 temps 200
-- TS 396 temps 300
-- TS 336 temps 400
-- TS 332 temps 300
-- TS 333 temps 200

- anomalie II :
-- TS 407 temps 600
-- TS 360 temps 400
-- TS 413 temps 400
-- TS 309 temps 200
-- TS 311 temps 300

- anomalie III :
-- TS 353 temps 400
-- TS 414 temps 400
-- TS 314 temps 500
-- TS 379 temps 400
-- TS 329 temps 300

- anomalie IV :
-- TS 327 temps 300
-- TS 421 temps 300
-- TS 305 temps 400
-- TS 389 temps 200
-- TS 399 temps 100
