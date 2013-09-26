---
coding: UTF-8
layout: post
published: true
comments: true
title: Ubuntu et les problèmes logiciels détectés
---
Je suis repassé sur Ubuntu pour voir un peu l'évolution depuis ma dernière utilisation (je n'y ai pas touché depuis le passage à unity, grosso-modo).  
Déjà je dois dire que cette distribution est plutôt bien foutue, contre toute attente. Prise en main ultra simple, interface graphique tape à l'œil, tout est plutôt bien intégré... Je déplore un peu le fait qu'Amazon soit présent dés l'installation, faisant vraiment penser à ces logiciels merdiques installés de base sur le Windows présent sur les pc's achetés en grande surface.   
Bref, globalement je ne suis pas mécontent de cette distro pour le moment. Néanmoins je repasserai sûrement à une distribution plus *hardcore* un jour ou l'autre. Quand ça "juste marche", je m'ennuie.

Un petit problème néanmoins, rapidement rencontré, c'est celui des fenêtres "Problème logiciel détecté" qui apparaissent parfois sans crier gare et sans souci apparent. L'astuce pour les désactiver c'est d'aller bidouiller dans le fichier */etc/default/apport"* et de passer la variable *enabled* à 0. Au reboot il n'y paraîtra plus.

Simple as fuck.
