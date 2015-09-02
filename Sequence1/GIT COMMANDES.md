## Principales Commandes Git ##







	
	
		git init --initialiser le versionning
	
	
		git help config -- obtenir de l'aide à la configuration
		
			git config --global user.name //definir le login
			git config --global user.email //definir l' email
			git config --global color.ui true //definir les couleurs 
			git config --list // avoir la liste toutes les autres commandes git
			
		
		git status  -- etat de votre serveur
		
			
			
			git add fichier  //ajouter le fichier au depot
			git commit  //commiter mais dans ce cas il faudra indiquer un message apres validation
			ou git commit -m "message de commit" // commit avec message de validation
			git commit -a -m "message de commit" //commit et ajout au depot en ligne
		
			
		creer un fichier .gitignore pour ignorer certains fichier lors du comit
				
					 
					 
		git log // creer un log
			 
			
		git diff  --motre les derniers modification
			
			
		REVENIR EN ARRIERE
		
			git log --online   //determiner l'endroit du commit
			
			git checkout PID fichier  //ramener le fichier à un etat anterieur
			
			git revert PID //defaire un commit 

			
			
		BRANCHES
		
			git branch redisign //creer une nouvelle branche
			git checkout redesign --se placer sur la branche
			git checkput master //retourner sur la branche master 
			
			git merge redisign // fusionner la  branche redisign eavec  la branche master
			git branch -d redisign  -- suppression
			
			
			git commit -amend //revenir sur le commit precedent
			
			git rebase master --envoie les commit sur master
			
			
		REMOTE
		
			
			git branch -r  //ensemble des branches  a distance
			git push //envoyer les modifications
			git push origin master
			git push master --delete test //supprimer test à distance
			git pull origin master //recuperer les modif faite
			git clone chemin dossier-local //faire un clone dans sons dossier local
			
			
		git clone chemin --depth 1 //preciser la profondeur des commit
			
			
		git branch -a  //lister des branch
