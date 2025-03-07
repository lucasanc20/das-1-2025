# das-1-2025

# Aula 26/02/2025

[bloquinho Walter](https://bloquinho.app/waltercoan)

[Livro Eng Soft Moderna - Cap 7](https://engsoftmoderna.info/cap7.html)

## DIA 27/02/25
INTERFACE FORMA DE COMUNICAÇÃO ENTRE COMPONENTES DE SOFTWARE 
Refere-se a um ponto de interação entre diferentes sistemas ou componentes. 
No contexto de software, pode ser a forma como diferentes módulos se comunicam. 
Em programação orientada a objetos, uma interface define um conjunto de métodos 
que uma classe deve implementar, mas não fornece a implementação desses métodos.

COMPONENTES - PARTES QUE PODE REUTILIZAR
São partes modulares de um sistema ou software, que podem ser desenvolvidas, 
testadas e implantadas de forma independente. Cada componente tem uma função 
específica e pode interagir com outros componentes para formar o sistema completo.

PACOTES - PASTAS
São agrupamentos de classes, funções ou módulos relacionados, geralmente usados 
para organizar o código de forma estruturada. No contexto de linguagens de 
programação como Java, Python, ou C#, pacotes ajudam a organizar o código e a 
evitar conflitos de nome.

MODULOS - SISTEMAS GRANDES SAO SEPARADOS EM MODULOS PARA NÃO MISTURAR SETORES
Um módulo é uma unidade de funcionalidade em um sistema de software. Em algumas 
linguagens de programação, como Python ou JavaScript, os módulos ajudam a dividir 
o código em partes menores, mais fáceis de gerenciar e reutilizar.

CAMADAS - SEPARAR RESPONSABILIDADES (FRONT / BACK / DB)
No contexto de software ou sistemas, "setores" podem se referir a diferentes áreas 
ou departamentos que lidam com diferentes partes de um projeto. Isso pode se referir 
a diferentes áreas de negócio ou domínios de aplicação (ex: finanças, RH, TI).

SERVIÇOS -
Refere-se a unidades de funcionalidade oferecidas por um sistema. Em uma arquitetura 
de microsserviços, por exemplo, um serviço é uma unidade independente que executa uma 
tarefa específica e se comunica com outros serviços para realizar operações complexas. 
No contexto de software, pode também se referir a APIs ou serviços web.


MODEL-VIEW-CONTROLLER 

uma arquitetura de software 
model
  dados que vao aparecer na tela

view 
  tela/interface 

controller
  controla(intermedia) onde vai os dados na interface

entidade classe que representa os dados processados e armazenados no banco

model classe que representa os dados que chegam do banco e apresenta na tela

mapping:
var clientEnt = new ClienteEnt()
var clientModel = new ClientModel()
clientEnt.setNome(clientModel.getNom)


monolito
  tdo no mesmo lugar, repositorio unico de codigo
  uso de uma unica tecnologia padrao
  compilado, testado e gera um unico pacote
  feito deploy como um unico sistema
  ele roda executado como um unio processo no sistema operacional
  unico banco de dados, ou repositorio.


## Aula 05/03/2025
Padrão arquitetural = solução para um problema específico

MVC - separa as responsabilidades (Model(dados) - View(tela) - Control(comportamento))
Estilo arquitetura = organização do projeto

Arquitetura em camadas

Divisão de responsabilidade
Performance
Segurança
Manutenibilidade
Camada de apresentação
Requisitos próprios
Camada de lógica de negócio (aplicação)
local central para definição e atualização das regras
escalar o backend suportar as requisições
Camada de persistência
Banco de dados relacional - consolidada
Resolve problemas de concorrência
Permite compartilhamento de dados

## Aula 06/03/2025

Who Needs an Architect?
O que é arquitetura?
Qual o comportamento do arquiteto da "Matrix"?
Qual o comportamento do arquiteto ideal?
