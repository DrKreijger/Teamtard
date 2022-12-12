# Teamtard INSTRUCTIONS:

Pour DL le pack, allez dans releases à droite de cette page

Suivez les instructions d'installation dans releases et les instructions ci-dessous
Pour installer:
1) Télécharger Curse Forge
2) Create a custom profile
3) Import:
https://github.com/DrKreijger/Teamtard/blob/main/Teamtard%20V1.5.zip

A ajouter dans Curse Forge:
1) Aller dans settings
2) Minecraft
3) Régler la mémoire sur 4500MB si vous avez 8Go de RAM sur votre PC, si vous avez 16Go ou plus mettez 8000MB MAX pour éviter les lags
3) Tout en bas là où il y a "arguments"
4) Copier/coller ceci:

-XX:+UseConcMarkSweepGC -XX:ParallelGCThreads=4 -XX:+DisableExplicitGC -XX:+CMSIncrementalMode -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:MaxGCPauseMillis=35

Pour plus de FPS, après avoir lancé le pack, fermez Overwolf dans votre barre des tâches, voir les icones cachés.
Ca fermera Curse Forge également mais pas Minecraft.
