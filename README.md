# relogio-anologico

Projeto de um relógio Analógico criado em JavaScript durante a semana de projetos práticos da B7Web.
No qual consiste em criar um relógio. Muitos projetos ensinam a fazer relógio digital, mas nesse projeto, foi inovador pois ensinou a fazer a manipulação de forma pratica em componentes da interface do relógio analógico.

```javascript
JavaScript
```
~~~javascript
 let sDeg = ((360 / 60) * second) - 90;
 let mDeg = ((360 / 60) * minute) - 90;
 let hDeg = ((360 / 12) * hour) - 90;

 sElement.style.transform = `rotate(${sDeg}deg)`;
 mElement.style.transform = `rotate(${mDeg}deg)`;
 hElement.style.transform = `rotate(${hDeg}deg)`;
  ~~~
