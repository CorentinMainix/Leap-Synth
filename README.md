# Leap-Synth

1.1 Énoncé

synthétiseur contrôlée par le Leap Motion

1.2 Description

Le but de ce programme est de permettre a l’artiste de contrôler par le biais de sa main, il pourra contrôler la hauteur le grain et la puissance sonore. La synthèse sonore sera créé par Pure Data, le système sera polyphonique. Le contrôle des autres paramètres ce sera par Touch OSC de sorte à sortir complètement l'ordinateur est à avoir une interface graphique plus pratique.

1.3 Analyse des besoins

Leap Motion : système d’analyse
Pure Data : système audio 
Touch OSC : système graphique 

1.4 Acquisition de connaissances

Recherche sur la création d’un synthétiseur numérique polyphonique dans Pure Data
Comprendre comment l'analyse des mouvements de la main est effectuée par le Leap Motion
Apprendre à créer une interface graphique compréhensible fonctionnel sur Touch OSC

1.5 Modèle


1.6 Méthodes

Une patch Pure Data contiendra le synthétiseur avec de multiples effets. Une autre patch servira de Show controle, elle recevra les données du Leap Motion ainsi que de Touch OSC. C'est données seront interprétés puis envoyer au contrôleur adéquate.
