## observerPattern

### O Observe Pattern funciona a partir da definição de um **modelo** e outras _dependências_ (**observadores**) nesse modelo, de modo que, sempre que o estado do modelo for alterado, todas as dependências sejam notificadas da mudança.

--- 

Neste projeto foi desenvolvida uma página com um botão **"Incrementar"**, sempre que o botão for pressionado um número será incrementado e uma cor será escolhida aleatóriamente. 

---

No exemplo utilizado, o número e a cor são os **modelos** ``(NumberModel.js)`` e a cada alteração de estado do modelo, ou seja, a cada incremento, os **observadores** ``(ConsoleObserver.js, ElementObserver.js e HistoryObserver.js)`` são notificados através da função _notifyObservers()_ e realizam uma ação.
  

