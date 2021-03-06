## Definicja

[[Wiedza/馃捇 Programowanie/JavaScript/Fundamenty/Constructor Functions]] to funkcja zwracaj膮ca nowy obiekt, wywo艂ana z pomoc膮 s艂owa kluczowego **new**. Jej nazw臋 zapisujemy z wielkiej litery. Rol膮 constructora jest utworzenie nowej instancji klasy, do kt贸rej jest przypisany. 

> 鈿狅笍 S艂owo kluczowe **new** sprawia, 偶e JavaScript tworzy nowy obiekt, przypisuje do niego s艂owo kluczowe [[this (JavaScript)]] oraz zwraca go z tej funkcji.

**M贸wi膮c inaczej:** 
Ka偶da klasa posiada constructor. Obiekt utworzony na podstawie tej klasy to tzw. instancja. 

```
const User = function(name) { // Klasa / Constrcutor
  this.name = name;
}

const user = new User('Adam'); // Instancja klasy
```


## Constructor vs Factory
Zar贸wno constructory jak i factory functions maj膮 na celu tworzenie nowych obiekt贸w.a

R贸偶nica pomi臋dzy constructorem a [[Wiedza/馃捇 Programowanie/JavaScript/Programowanie funkcyjne/Factory Functions]], polega na sposobie wywo艂ania. Dodatkowo Constructor wymaga s艂owa kluczowego **new**, zamienia zachowanie [[this (JavaScript)]], niejawnie zmienia zwracan膮 warto艣膰 oraz ustawia prototyp. 

## Wyja艣nienie
<iframe width="560" height="315" src="https://www.youtube.com/embed/oowjlU-867M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>