# Module de Capteurs Suiveur de Ligne (10x TCRT5000)

Ce projet contient les fichiers de conception pour un module PCB incurvé conçu pour le suivi de ligne, intégrant 10 capteurs infrarouges TCRT5000.

## Schéma Électrique
Le circuit est composé de 10 capteurs optiques (U1 à U10), chacun accompagné d'une résistance de 220 ohms pour la LED émettrice et d'une résistance de pull-up de 10k ohms pour le phototransistor récepteur[cite: 1]. Les signaux (SIG_S1 à SIG_S10) sont regroupés sur un connecteur central à 12 broches avec l'alimentation (VCC) et la masse (GND).

<img width="605" height="281" alt="Capture d&#39;écran 2026-08-31 190306" src="https://github.com/user-attachments/assets/1760c6fd-49ba-4908-8bea-f04b2a5ec575" />


## Routage du PCB
Le routage a été optimisé sur un circuit imprimé de forme incurvée pour s'adapter à l'avant d'un robot, avec deux trous de montage (H1 et H2).

<img width="470" height="244" alt="Capture d&#39;écran 2026-08-31 190145" src="https://github.com/user-attachments/assets/6e4339e1-6754-4a78-8150-a56f21d6803d" />

## Vues 3D

### Face Supérieure (Composants)
La face supérieure accueille l'ensemble des résistances traversantes, le condensateur de découplage, et le connecteur principal J1.

<img width="466" height="213" alt="Capture d&#39;écran 2026-08-31 190154" src="https://github.com/user-attachments/assets/c969bcfb-8b48-4c1a-a7b0-073ce538ef53" />

### Face Inférieure (Capteurs)
La face inférieure est dédiée exclusivement aux 10 capteurs infrarouges TCRT5000 orientés vers le sol pour la détection de ligne.

<img width="544" height="242" alt="Capture d&#39;écran 2026-08-31 190209" src="https://github.com/user-attachments/assets/8db0fbdc-fb65-4c1d-9324-805374e3f081" />
