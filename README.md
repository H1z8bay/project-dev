# project-dev
Bjr je m'appelle Noé et je veut être dev sur votre serveur entant que développeur 
const mangouste = require ( 'mangouste' ) ;

const warnSchema = mangouste . Schéma ( {
identifiant de guilde : {
saisi : Chaîne ,
requis : vrai ,
} ,
ID utilisateur : {
saisi : Chaîne ,
requis : vrai ,
} ,
avertissements : {
saisi : [ Objet ] ,
requis : vrai ,
} ,
maxAvertissements : {
saisi : Nombre ,
par défaut : '10' ,
} ,
action : {
saisi : Chaîne ,
par défaut : 'interdire' ,
} ,
} ) ;

module . exportations = mangouste . modèle ( 'avertissements' , warnSchema ) ;
