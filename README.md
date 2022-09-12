# pokedexApi
API en Symfony qui renvoie les infos des 151 premiers pokemon, une version en nodeJS est hebergé sur : https://mehdidex.herokuapp.com/


Utilisation de l'API

/pokemon  => renvoie la liste complete des pokemons et leurs infos


/pokemon/:id => renvoie le pokemon dont l'id correspond et ses infos ou :id est un id de 1 a 151


/images/pokemons/:pokemon => le lien de l'image du pokemon où :pokemon est le nom d'un pokemon en français (insensible majuscule/minuscule)


/images/types/:type => le lien de l'image du type où :type est le nom du type en français (insensible majuscule/minuscule)
