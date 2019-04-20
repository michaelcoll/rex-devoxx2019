### De Java 8 à Java 11 sur un gros projet : les pièges à éviter
- doc oracle : http://docs.oracle.com/en/java/javase/11/migrate
- evolution de java : http://github.com/marchof/java-almanac
- plugin maven/gradle pour définir les dépendances entre packages : deptective http://github.com/deptective
- possibilité de sortir un graphe de dépendances
- retour xp :
	* power mock -> fail
	* la lib reflections -> fail
	* build-helper-maven-plugin -> fail
	* weblogic -> fail