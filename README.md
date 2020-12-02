# Projeto de Sistemas Mecatrônicos 1 (Português)

_Máquina dobradora de roupa_

<p align="center">
  <img src="Videos/folding_tshirt_example.gif" width="600">
</p>

## Exemplos

Durante a implementação do projeto, foram tomados como exemplos de tal produto já no mercado, as seguintes máquinas:

[_Speedy Tee T-Shirt - Chiossi e Cavazzuti_](https://www.youtube.com/watch?v=gGlLr4Ftdfc&feature=youtu.be)

<p align="center">
  <img src="Photos/Conceptual Project/speedytshirt.jpg" width="600">
</p>

[_FoldiMate_](https://www.youtube.com/watch?v=qHljT48dz-U&feature=emb_title)

<p align="center">
  <img src="Photos/Conceptual Project/FoldiMate.jpg" width="600">
</p>

Outro exemplo de máquina encontrado foi um da filosofia DIY (Do It Yourself) mostrada no seguinte [vídeo](https://www.youtube.com/watch?v=gzCHk0JZ2hY), utilizando marcenaria para tanto. O modo mais simples seria utilizar papelão e fazer como na imagem abaixo:

<p align="center">
  <img src="Photos/Conceptual Project/dyiFoldingTshirt.jpg" width="600">
</p>

## Lista de componentes

### Eletrônica

- Arduino Uno R3 ATmega328P Development Board With Boot Loader
- Módulo Bluetooth Low Energy - HC-08
- Duas (2x) PCBs ilhadas 5 x 10 cm
- 5 (5x) Transistores MOSFET IRFZ34 (NPN)
- Fonte Chaveada 12V
- Botão
- Conectores
- Resistores de 220Ω e 10kΩ
- Adaptadores
- Jumpers
- Cabos flexíveis de várias cores
- LEDs

### Estrutura Física e Mecanismos

- Engrenagens e catraca feitas utilizando impressão 3D
- Estrutura física do projeto e mecanimos utilizando MDF e madeiras compensadas
- Dobradiças metálicas
- Parafusos de madeira e parafusos Allen
- Borracha EVA
- Cola

### Motores

- Cinco (5x) Motores de Vidro Elétrico Universal Mabuchi

### Ferramentas

- Kit Solda (Ferro de Solda, Estanho para solda, Suporte para Ferro de Solda, Sugador de Solda)
- Furadeira de Bancada
- Furadeira
- Morsa
- Sargentos
- Brocas
- Fura-copo
- Arco de Serra
- Micro Retífica - DREMEL

## Histórico de Desenvolvimento

### Fase Conceitual

Inicialmente, cumprindo o cronograma da disciplina, o grupo focou seus esforços em pensar conceitualmente em como solucionar o problema de dobrar roupas objetivamente. Foram vistos vários estilos/métodos ortodoxos de dobrar roupas e verificada a inviabilidade de implementar alguns destes devido à complexidade de implementação. Um exemplo destes seria a seguinte maneira de dobrar uma camisa.

<p align="center">
  <img src="Videos/dobrar camiseta em 5 seg.gif" width="600">
</p>

O grupo optou, portanto, por seguir sua implementação na direção de uma solução padrão e parecida com a utilizada pela empresa Chiossi e Cavazzuti.

Ainda nesta fase do projeto, já se pensou a respeito dos mecanismos envolvidos para transformar o movimento rotativo de nosso motor para movimentar uma aba feita de madeira. Chegou-se a conclusão que um mecanismo de 4 barras como o ilustrado abaixo seria o suficiente para reproduzir o movimento de dobrar camisetas de manga curta. Pode-se considerar que a aba de dobrar roupas seria representada pela barra de cor azul, tendo um deslocamento de aproximadamente 90° ao longo de uma rotação completa do motor.

<p align="center">
  <img src="Videos/4 barras_animacao.gif" width="600">
</p>

Por fim, foi feito um modelo em CAD retratando de maneira ainda superficial a estrutura física da máquina. Como pode-se observar na imagem abaixo, a amplitude de movimento para dobrar camisas de manga longa superaria mais do que 90° e portanto não poderia ser utilizado um mecanismo de 4 barras para tal operação. Nesta fase do projeto, esta decisão ainda estava em aberto.

<p align="center">
  <img src="Photos/Conceptual Project/Dobrador furado_cotado.png" width="600">
</p>

### Projeto do Sistema

### Protótipo Mecânico

Verificada a maneira que gostaríamos de dobrar a roupas, o próximo passo seria fazer a estrutura física da máquina. Devido ao fato do projeto envolver a elaboração de um protótipo, o grupo optou por fazer a estrutura da máquina utilizando madeiras do tipo MDF, devido a sua versatilidade, fácil manuseio e rápida obtenção. Nesta fase do projeto, o grupo gostaria de agradecer imensamente à marcenaria da USP por toda a hospitabilidade e disponibilidade de nos ajudar a fazer todas as peças necessárias para o projeto. Gostaríamos de agradecer em especial ao Jeremias, responsável pela marcenaria, por toda a ajuda e contribuição para o projeto. Sem este apoio, o sucesso e a viabilidade do projeto teriam sido comprometidos significativamente. Muito obrigado!

<p align="center">
  <img src="Photos/Physical Structure/Marcenaria USP.jpg" width="500">
</p>

### Sistema Interface Homem-Máquina (IHM)

### Apresentação Final

# Project of Mechatronic Systems I (English)

_Laundry Folding Machine_

<p align="center">
  <img src="Videos/folding_tshirt_example.gif" width="600">
</p>

This project is the result of the discipline [Project of Mechatronic Systems 1](https://uspdigital.usp.br/jupiterweb/obterDisciplina?sgldis=SEM0541&codcur=18250&codhab=0) offered by the University of São Paulo, campus of São Carlos, to the [Mechatronic Engineering course](https://eesc.usp.br/graduacao/curso.php?id=18250). The proposed idea was to make a machine with the following requisites:

- Fold both short sleeve T-shirts, as well as long sleeve T-shirts or sweaters
- Be controlled using a cell phone

The project had the aim to challenge the the students to implement a real project using the knowledge acquired at that point of the graduation. To name a few:

- CAD Design
- Mechanisms
- Embedded Systems
- Electronics
- C/C++ Programming

## Examples

## Components - _Bill of Materials_

- Arduino Uno R3 ATmega328P Development Board With Boot Loader
- Bluetooth Low Energy Module - HC-08
- Metallic hinges
- Wood Screws
- PCB 5 x 10 cm
- Welding Kit
- Jumpers
- LEDs
- Protoboard
- MOSFET Transistors IRFZ34
- Gears made with 3D Printing
- Structure and mechanisms made with many kinds of plywood (Overlaid Plywood, Composite Wood, Hardboard, MDF)

## Development History

# Making the physical structure and mechanisms

# 3D Printing

# Handling the electronics involved

# Development of the cell phone app

_Final Product_

<p align="center">
  <img src="Photos/Final Product/machine.jpg" width="600">
</p>

## Desenvolvedores/Developers

- [Isaak Machado](https://github.com/Isaakns)
- [Leonardo Felipe L. S. dos Santos](https://github.com/qleonardolp)
- [Matheus de Souza Sereno](https://github.com/Sereno29)
- [Victor Tamassia Nopeney](https://github.com/Vtn21)

## Professores/Professors

- [Adriano Almeida Gonçalves Siqueira](http://www.sem.eesc.usp.br/index.php/pt/pessoal/docentes/adriano-almeida-goncalves-siqueira)
- [Rodrigo Nicoletti](http://www.sem.eesc.usp.br/index.php/pt/pessoal/docentes/rodrigo-nicoletti)
