# Marlin-Ender_3
Firmware Marlin personnalisé pour ma Ender 3

## Instructions pour Flashage Ender 3
1. Compiler ("Build") le firmware à l'aide du plugin VSCode "Auto Build Marlin" (choisir la version STM32F103RE_creality (512K) correspondant au contrôleur présent dans ma carte Creality 4.2.2)
2. Cliquer sur "Upload" à côté du firmware compilé
3. Copier le fichier .bin généré sur une carte SD (formatée de préférence et ne contenant rien d'autre)
4. Veiller à ce que l'imprimante soit éteinte puis insérer la carte SD dans le port SD de la Ender 3
5. Démarrer l'imprimante et attendre environ 10s que l'écran noir passe à l'écran de Marlin/Ender
    * **A noter :** Si le message "error EEPROM" s'affiche cliquer sur Ignore, sortir la SD, rédémarrer l'imprimante puis aller dans "Configuration > Advanced settings > Initialize EEPROM"
6. Couper l'imprimante et sortir la carte SD (puis supprimer le fichier .bin sur la carte ou la formater)
7. Allumer à nouveau l'imprimante
8. Et voilà le firmware à été mis à jour ! :)