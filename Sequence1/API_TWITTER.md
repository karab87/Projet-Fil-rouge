# Activitée Fil rouge - Sequence 1 #

###On retrouve 15 principaux operateur de recherche twitter exprimé comme suit:###

- "médias sociaux"					Les guillemets   permettent d'obtenir l'expression exacte.
- facebook OR twitter					Des tweets avec
soit « facebook » soit « twitter », ou les deux.
- médias -sociaux						Des tweets contenant « médias » sans « sociaux ».
- #seo								Vous trouvez des tweets contenant le hashtag #seo.
- from:yagraphic						Des tweets envoyés par l'utilisateur @yagraphic.
- to:yagraphic						Des tweets que les utilisateurs ont envoyé à @yagraphic.
- @yagraphic							Fait référence à une personne.
- "rédaction web" near:"marseille"	Tweets avec l'expression exacte « rédaction web » et envoyés près de Marseille.
- near:marseille within:50mi			Des tweets localisés à 50 kilomètres de Marseille.
- référencement since:2011-03-01		Tweets avec « référencement » et envoyés depuis la date (année-mois-jour).
- référencement until:2007-01-01		Tweets qui mentionnent « référencement » et envoyés jusqu'à la date.
- référencement -naturel :)			Tweets positifs qui contiennent le mot « référencement » sans « naturel ».
- référencement :(					Tweets d'utilisateurs déçus et qui mentionnent le terme « référencement ».
- référencement ?						Tweets avec le mot « référencement » et qui posent une question.
- surprenant filter:links				Tweets avec le mot « surprenant » et qui partagent un ou plusieurs liens (URLs).
- paris source:twitterfeed			Tweets avec le nom de la ville qui proviennent de la source Twitterfeed.


### Requête  pour trouver les derniers tweets contenant les mots "Afrika" ET "code" ###

	https://api.twitter.com/1.1/search/tweets.json?q=%23Africa&code&result_type=recent



### Utilisation journalistique de cette API ###

 
De par ses operateur de recherche, l'API Twitter est un bon moyen d’anticiper des informations ou evenement importantes. Il permet donc  aux journaliste de gagner du temps et à affiner la qualité de l’information recueillie.  
C'est  un bon moyen pour se  tenir au courant des sujets porteurs ou des cas buzz et d’être à jour 
facilement et de manière qualitative en temps réel.