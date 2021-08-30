# JavaScript - Stocker les informations avec les variables

# Le [support du cours](http://ens-info.irem.univ-mrs.fr/wp-content/uploads/05_javascript_debut.pdf) est disponible sur l'ENT.  

## Afficher un morceau de code en Javacript
Pour afficher un morceau de code en javascript, nous utilisons la syntaxe suivante :
````
```javascript
function createParagraph() {
  let para = document.createElement('p');
  para.textContent = 'Vous avez cliqué !';
  document.body.appendChild(para);
}
```
````
Pour afficher un morceau de code en HTML, nous utilisons la syntaxe suivante :

````
```html
<button onclick="createParagraph()">Cliquez-moi!</button>
```
````
Et voici l'interface dans la console tech.io.

```javascript

function createParagraph() {
  let para = document.createElement('p');
  para.textContent = 'Vous avez cliqué !';
  document.body.appendChild(para);
}
```
```html 
<button onclick="createParagraph()">Cliquez-moi!</button>
</div>
```

test

```html runnable
function createParagraph() {
  let para = document.createElement('p');
  para.textContent = 'Vous avez cliqué !';
  document.body.appendChild(para);
}
<button onclick="createParagraph()">Cliquez-moi!</button>
</div>

```
La méthode __console.log()__ envoie un message à la console Web. Le message peut être une chaîne unique  ou il peut s'agir d'un ou plusieurs objets JavaScript.

```javascript 
console.log('Hello World!');
```
Pour une utilisation de base, vous pouvez rendre un simple morceau de code exécutable. Pour cela, vous devez ajouter lemot - clé : `runnable`

````
```javascript runnable
console.log('Hello World!');
```
````

```javascript runnable
console.log('Hello World!');
```
## Déclaration des variables

Voici un morceau de code avec la déclaration de variables

```javascript 
var a = 2;
var b = 6;
console.log(a+b);
```

Dans l'exercice ci-dessous vous devez créer les variables suivantes : 
- __num__ qui contient le nombre 255  
- __txt__ qui contient la chaîne de caractère *255*  
- __bin__ qui contient la valeur booléenne *vraie*  
- __flt__ qui contient la valeur 7,23  

@[Créez les variables demandées ci-dessus]({ "stubs": ["variables01.js"], "command": "node_modules/mocha/bin/mocha test_variables01.js --reporter list" })

## Opération sur les variables
