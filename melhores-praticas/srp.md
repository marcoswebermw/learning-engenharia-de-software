## SRP - Single Responsibility Principle
  
O SRP leva á coesão. Ele indica que temos que ter uma única responsabilidade por classe.
  
Se a classe é alterada constantemente, faz muitas coisas, tem muitos ifs, sempre está crescendo, alterações nela tem efeitos colaterais refletidos em outras classes, tudo isso é indicativo que o SRP não está aplicado nela.
  
Como consequência essa classe não será coesa.
  
Os ifs geralmente serão bem-vindos em classes muito simples, que os problemas são resolvidos muito facilmente. Aí não vale a pena criar classes muito complexas somente para atingir a coesão.