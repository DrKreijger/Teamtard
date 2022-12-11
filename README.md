# Teamtard-V1.4
TeamTard 300 mods

INSTRUCTIONS:

Pour DL le pack, allez dans releases à droite de cette page
Suivez les instructions d'installation dans releases et les instructions ci-dessous

A ajouter dans Curse Forge:
1) Aller dans settings
2) Minecraft
3) Régler la mémoire sur 4500MB si vous avez 8Go de RAM sur votre PC, si vous avez 16Go mettez 8000MB
3) Tout en bas là où il y a "arguments"
4) Copier/coller ceci:

-XX:+UseConcMarkSweepGC -XX:ParallelGCThreads=4 -XX:+DisableExplicitGC -XX:+CMSIncrementalMode -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:MaxGCPauseMillis=35
