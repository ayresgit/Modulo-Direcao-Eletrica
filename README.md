# Direção Elétrica para Embarcação Solar

Instituto Federal de Educação, Ciência e Tecnologia de Santa Catarina - Campus Florianópolis

Departamento Acadêmico de Eletrônica Curso de Engenharia Eletrônica

Projeto Integrador III

Aluno:

* Gabriel Ayres Rodrigues

# Sumário

1. [Introdução](#introdução)
2. [Concepção](#concepção)
3. [Design](#design)
4. [Implementação](#implementação)
5. [Operação](#operação)
6. [Considerações Finais](#considerações)
7. [Bibliografia](#bibliografia)

# Introdução

Esse módulo tem como objetivo controlar a direção da rabeta da embarcação Guarapuvu II, da equipe Zênite Solar do IFSC.

É inspirado pelo sistema atualmente implementado, desenvolvido por Cesar Dias Parente. Os arquivos do projeto podem ser encontrados [aqui](https://github.com/ZeniteSolar/MDE18/tree/main).

A embarcação da equipe Zênite é operada em competições de barcos solares, onde são exigidas alta performance e robustez. A equipe obteve êxito em diversos anos de competição, a direção elétrica contribuindo para isso especialmente em provas de manobras como o Slalom.

O sistema eletrônico atual foi danificado após a competição em março de 2022, o que é um motivador para sua atualização. 

# Concepção

Pensando em um sistema de direção, a escolha de utilizar uma direção elétrica pode trazer maior responsividade mesmo tendo uma fração do peso de um sistema mecânico.[referência]. Além disso, sistemas mecânicos podem pedir esforço físco do motorista e uma necessidade maior de manutenção. Por essas razões

Abaixo está o diagrama representando um sistema de direção elétrica e suas partes. 
![Diagrama concepção](https://github.com/ayresgit/Modulo-Direcao-Eletrica/blob/4bd646044cc3c0f56f176853dbc235b8130db225/Imagens/Diagrama%20de%20blocos%20da%20dire%C3%A7%C3%A3o%20el%C3%A9trica.PNG)

Levando em contas os elementos acima, os seguintes problemas devem ser confrontados:
- Sistemas eletrônicos em veículos devem possuir alta robustez devido às vibrações ao qual são expostos. No caso da embarcação em alta velocidade, especialmente para operações marítimas, os impactos são um grande problema (além da oxidação dos circuitos).
- Como o veículo alvo é utilizado em competições cujo foco, e portanto o desafio, está na geração e consumo de energia, a solução deve ser tão eficiente quando possível para garantir o sucesso da equipe.
- Um ambiente competitivo entre veículos requer alta performance dessa direção, não apenas para alcançar a vitória mas garantir a segurança de todos. Portanto, a funcionalidade deve ser atendida tão bem quanto os outros parâmetros.

Para implementar o todo é preciso definir os requisitos das partes, feito em seguida.

* ## Sensores
Precisão. Robustez.

*vantagens de sensor sem contato: Menos desgaste por envelhecimento, menos histerese, menos problemas com dislocamento do eixo
Levando em conta o preço reduzido da alternativa e sua confiabilidade... 

Potênciometro comum: equacionamento e precisão. (vale lembrar que a rabeta não gira 360)
opções de potênciometro?

* ## Controlador
Capacidade de processamento. Tempo de resposta. Consumo. Portas disponíveis. Protocolos disponíveis (CAN seria interessante). Robustez.

* ## Potência
PONTE H
Eficiência, parâmetros elétricos de operação (tecnologia do mosfet; driver?) [parâmetros do motor, alimentação do circuito]. Robustez.


 
* ## Requisitos
|| Sensores | Controlador | Potência |
|-----------|-----------|-----------|-----------|
| X | x | x | x |


# Design


# Implementação


# Operação

# Considerações

# Bibliografia






