# local_planner_student

Le but de ce TP est coder un local planner sur la base de ce template.

Pour piloter le robot, 2 services (au choix):
- un Goal
- un Path

Pour évaluer le déplacement, 2 topic en écoute:
- /scan pour vérifier qu'il n'y ai pas d'obstacle
- /odom pour connaitre la position relative du robot par rapport à la tf odom

En sortie, un topic en publication:
- /cmd_vel_mux/input/navi de type twist pour piloter le robot en vitesse

Complétez le template. Des commentaires "TODO" indique dans les grandes lignes ce qu'il faut faire.
Commencez par déplacer le robot pour 1 seul Target ajoutez la fonctionnalité du Path
