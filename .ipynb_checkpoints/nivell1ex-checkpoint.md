# Spring framework  

## Funcionalitats clau  

* Gestió de la configuració basada en JavaBeans, aplicant-hi principis d'Inversió de Control, més específicament usant la tècnica d'Injecció de Dependència. Això ajuda a reduir les dependències de components, en implementacions específiques, sobre altres components.  
  
* Una factoria de Beans central, que és usada globalment.  

* Capa genèrica d'abstracció per la gestió de transaccions de la base de dades.  

* Estratègies preincorporades per la JTA i un sol DataSource de JDBC. Això elimina la dependència en un entorn Java EE pel suport a les transaccions  

* Integració amb entorns de persistència com Hibernate, JDO, iBatis i db4o.  

Aquest entorn proveeix solucions per diversos reptes
 tècnics encarats per desenvolupadors **Java**
 i organitzacions que volen crear ```aplicacions basades en la Plataforma``` **Java**.
 Donada la clara amplitud de la funcionalitat que s'hi ofereix, pot fer-se complicat distingir entre els blocs
 principals que componen el marc de treball.
``` Spring Framework``` **NO** està lligat *exclusivament* a **Java** EE, 
encara que la seva prou aconseguida integració en aquesta àrea és una raó important
 per la seva popularitat.


```java
class HelloWorld {
	public static void main(String[] args){
		system.out.println("Hello, World!");
	}
}
```
