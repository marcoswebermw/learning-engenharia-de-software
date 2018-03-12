## Coesão
  
Ocorre quando uma classe tem apenas uma responsabilidade.
  
São mais simples de serem mantidas, tem menos código e maior reuso.
  
Uma classe sem coesão sempre está crescendo. Geralmente com muitos `ifs`.
  
É melhor trocar os `ifs` por classes separadas e menores.
  
Métodos são bons para dividir funcionalidades de um método maior. Mas se forem várias responsabilidades em um mesmo método, é melhor definir classes ao invés.
  
Se para uma mudança surtir efeito, ela requer alterações em vários pontos, provavelmente existe um problema de projeto das classes.
  
Métodos privados servem de apoio aos métodos públicos. Eles ajudam a melhorar a legibilidade do código. Se um método público muda muito então é melhor criar uma classe para ele.
  
