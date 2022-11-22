# Marlin-Ender_3
Marlin personalisé pour ma Ender 3

## Instructions pour Flashage Ender 3
1. Compiler ("Build") le firmware à l'aide du plugin VSCode "Auto Build Marlin" (choisir la version STM32F103RC_creality (256K))
2. Cliquer sur "Upload" à côté du firmware compilé
3. Copier le fichier .bin généré sur une carte SD (formatée et ne contenant rien d'autre)
4. Veiller à ce que l'imprimante soit éteinte puis insérer la carte SD dans le port SD de la Ender 3
5. Démarrer l'imprimante et attendre environ 10s que l'écran noir passe à l'écran de Marlin/Ender (si le message "error EEPROM" s'affiche cliquer sur Ignore, sortir la SD, rédémarrer l'imprimante puis aller dans "Configuration > Advanced settings > Initialize EEPROM"
6. Et voilà le firmware à été mis à jour ! :)