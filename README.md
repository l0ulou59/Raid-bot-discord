# Raid-bot-discord
les commandes pour raid


Commands:
*Pour ajouter le bot, il faut les perms*

1) !nuke 
> Pour supprimer tous les salons.
- Vous avez besoin de la  'Manage Channels' Permission.


2) !spam 'nombre de channel' 'nom_de_la_channel'
> ça créait le nombre de channel indiqué avec le nom. 
- Vous avez besoin de la  'Manage Channels' Permission.
- !spam défauts= 10, 'get spammed'

	EXAMPLE:
!spam 100 "test" créer 100 channels nommer 'test')
!spam (créer 10 channels nommé 'get-spammed')


3) !ban 'target'
> Bans un joueur , bans everyone possible.
- Vous avez besoin de la 'Ban Members' Permission.
- Tu peux seulement ban un joueur avec un rôle inférieur à bot.

	EXEMPLE:
!ban "Exampletest123" (ça va ban un joueur qui s'appelle 'ExampleUser123')
!ban (bans everyone possible)


4) !kick 'target'
> Clone de !ban mais expulse au lieu de bannir le membre.
- Vous avez besoin de la  'Kick Members' Permission.
- Vous ne pouvez expulser que les membres dont le rôle est inférieur à celui du bot.

	EXEMPLE:
!kick "ExampleUser123" (va exclure le membre avec le nom 'ExampleUser123')
!kick (kicks everyone possible)


5) !droles
> Tente de supprimer tous les rôles.
-Vous avez besoin de la  'Manage Roles' Permission.


6) !sroles 'nombre de  roles' 'role_nom'
> Crée le nombre spécifié de rôles appelés par le nom donné.
- Clone de !spam mais juste avec les roles.
- Vous avez besoin de la  'Manage Roles' Permission.
- !sroles défauts = 10, 'spam'

	EXEMPLE:
!sroles 100 "test" créer 100 roles nomer 'test')
!sroles créer 10 roles nommer 'spam')


7) !alert 'message' 'time_spamming (nombre de second)'
> Spams le message donné pour le temps spécifié.
- Vous avez besoin de la 'Send Messages' Permission.
- !alert défauts= '@everyone', 10

	EXEMPLE:
!alert "SIUUUUUUUUUUUUUU" 12 (spams le message "SIUUUUUUUUUUUUUUUUUUU" for pour secondes)
!alert (spams le message '@everyone' pour 10 secondes)
