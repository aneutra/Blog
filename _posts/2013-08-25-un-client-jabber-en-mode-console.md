---
layout: post
title: Un client jabber en mode console
tags:
- console
- jabber
- linux
- logiciel
status: publish
type: post
published: true
meta:
  _edit_last: '1'
  _thumbnail_id: '303'
  _yoast_wpseo_linkdex: '0'
---
J'utilise très souvent Jabber et pour cause, ma copine l'utilise aussi pour communiquer (comme quoi, ne vous inquiétez pas, tout n'est pas perdu). Pour avoir l'air d'un vrai puriste geek linuxien j'utilise bien évidemment un client en mode console: mcabber.  

##Présentation:

mcabber est un client jabber - et uniquement jabber - qui s'utilise en console - et uniquement en console - simple à configurer, personnalisable et simple à utiliser. Pour ce dernier point, c'est en partant du principe que vous êtes habitué aux applications consoles, puisque ce n'est pas forcément très intuitif pour les adeptes du clickodrome.

![](http://mcabber.com/screenshots/mcabber20060403.png)  

De base, le logiciel ressemble à peu prés à ça. Austère ? On ne peut pas le nier. L'écran est partagé en 4 zones ayant chacune une fonction bien définie : nous voyons à gauche la liste des contacts, a droite la conversation avec le contact sélectionné, puis en bas un buffer et encore en dessous la zone de saisie de texte.  

##Installation:

Sous archlinux l'installation est simple, il suffira d'un  
>pacman -S mcabber  
>cp /usr/share/mcabber/exemple/mcabberrc /home/user/.mcabberrc

Il vous faudra ensuite éditer le fichier de configuration .mcabberrc et y mettre vos informations de connexion aux endroits qui vont bien (les quelques premières lignes, ne vous inquiétez pas le fichier est bien documenté).

##Utilisation:

Après avoir édité le fichier de configuration il vous suffit de lancer le logiciel en tapant mcabber dans une console, ce qui aura pour effet de vous connecter. Il ne vous reste plus qu'à utiliser les touches "page précédente / page suivante" pour naviguer dans votre liste de contacts et parler.

##Petit tips bonus:

Pour rendre la chose un peu moins moche, vous pouvez changer les couleurs en modifiant ces quelques lignes dans votre fichier de configuration:

>set color_background = 234  
>set color_general = 244  
>set color_info = 240  
>set color_msgin = 166  
>set color_msgout = 64  
>set color_msghl = 136  
>set color_bgstatus = 235  
>set color_status = 166  
>set color_roster = 240  
>set color_bgrostersel = 235  
>set color_rostersel = 166  
>set color_rosterselmsg = 136  
>set color_rosternewmsg = 13
