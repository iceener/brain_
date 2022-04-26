## Definicja

[[Wiedza/💻 Programowanie/JavaScript/Fundamenty/Constructor Functions]] to funkcja zwracająca nowy obiekt, wywołana z pomocą słowa kluczowego **new**. Jej nazwę zapisujemy z wielkiej litery. Rolą constructora jest utworzenie nowej instancji klasy, do której jest przypisany. 

> ⚠️ Słowo kluczowe **new** sprawia, że JavaScript tworzy nowy obiekt, przypisuje do niego słowo kluczowe [[this (JavaScript)]] oraz zwraca go z tej funkcji.

**Mówiąc inaczej:** 
Każda klasa posiada constructor. Obiekt utworzony na podstawie tej klasy to tzw. instancja. 

```
const User = function(name) { // Klasa / Constrcutor
  this.name = name;
}

const user = new User('Adam'); // Instancja klasy
```


## Constructor vs Factory
Zarówno constructory jak i factory functions mają na celu tworzenie nowych obiektów.a

Różnica pomiędzy constructorem a [[Wiedza/💻 Programowanie/JavaScript/Programowanie funkcyjne/Factory Functions]], polega na sposobie wywołania. Dodatkowo Constructor wymaga słowa kluczowego **new**, zamienia zachowanie [[this (JavaScript)]], niejawnie zmienia zwracaną wartość oraz ustawia prototyp. 

## Wyjaśnienie
<iframe width="560" height="315" src="https://www.youtube.com/embed/oowjlU-867M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>