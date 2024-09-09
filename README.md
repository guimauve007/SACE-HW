# SACE-HW
Répertoire contenant 2 cartes pour machine SACE:

## Getting started
- Installer la dernière version de KiCad ici: https://www.kicad.org/download/
- Cloner ce répertoire sur votre ordinateur local:

```
git clone https://github.com/guimauve007/SACE-HW.git
```


## carte_controle (V1)
Module de contrôle versatile avec les fonctionnalités suivantes:
- 2 connecteurs BNC pour lecture de tension & de courant des électrodes (à l'oscilloscope)
- 8 GPIO/ADC 12 bits 5V
- 2 sorties 0-5V analog (DAC)
- 2 sorties 0-10V analog (DAC)
- 8 sorties 5V haute vitesse (pour stepper drive)
- 2 relais NO 125VAC-10Amp
- 4 Mosfet Open Drain pour load 12V 5.7Amp Max
- Lecture de tension + courant des électrodes jusqu'à 200kSPS avec résolution 12 bits
- Possibilité d'enregistrer un log de données via carte SD
- Interface web utilisateur avec communication MQTT via ESP32
- Connecteurs I2C (x2) pour accessoires auxiliaires  


## interface_piezzos (V1)
- Amplificateur de signal via OP-Amp en mode comparateur (sortie 0-5V)
