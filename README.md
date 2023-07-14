# Projeto Fonte-de-tensao

Projeto realizado no primeiro semestre do curso de Bacharelado em Ciências de Computação, para a disciplina de "Eletrônica Digital", ministrada pelo professor Eduardo do Valle Simões, da Universidade de São Paulo (USP) - Campus de São Carlos.

### Objetivo do Projeto
O projeto consiste no desenvolvimento de uma fonte de tensão ajustável de 3V á 12V com capacidade de 100mA.

## Diagrama da Fonte de Tensão
[Circuito-Falstad.txt](https://github.com/J-carvalho17/Fonte-de-tensao/files/12051662/Circuito-Falstad.txt)
Link da fonte: https://tinyurl.com/24qld2v9

## Componentes Utilizados
| Componentes | Quantidade | Valor |
| -------- | -------- | -------- | 
| Transformador |1|Utilizado transformador do laboratório|
| Ponte de Diodos |1|R$7,76 |
| Capacitor 1mF |1|R$0,49 |
| Diodo Zener 13V |1|R$0,47 |
| Potenciômetro |1|R$6,79 |
| LED |1|R$0,49|
| Fusível 1A|1|R$1,07|
| Resistência 1.5k |1|R$0,70|
| Resistência 3.3k |1|R$0,70|
| Resistência 4.7k |2|R$0,70 |
| Resistência 100 ohms |1|R$0,70 |
| Transistor NPN |1|R$1,55 |
| Fio macho-macho |2|R$13,58|
| Valor Total||R$38,18 |

## Função dos componentes

- Fonte de corrente alternada: Simula a tensão da rede elétrica com 127V, 60Hz e 180V de pico.

- Transformador: Reduz a tensão da rede para uma faixa de 3V a 12V, conforme necessário.

- Ponte Retificadora: Converte corrente alternada em corrente contínua para alimentar o circuito.

- Capacitor: Armazena carga elétrica durante os ciclos da corrente alternada, fornecendo corrente quando necessário.

- Diodo Zener: Regula a tensão do circuito, conduzindo corrente apenas quando a tensão atinge um determinado valor (13V).
  
- Potenciômetro: Resistor ajustável que controla a tensão dentro do circuito entre 3V e 12V.
  
- Transistor: Amplifica ou interrompe a corrente elétrica, podendo funcionar como um amplificador ou interruptor.
  
- Resistores: Limitam a passagem de corrente em locais específicos do circuito.
  
- LED: Componente que emite luz quando uma corrente elétrica passa por ele, utilizado como indicador luminoso.
  
- Fio macho-macho: Utilizado para conectar dispositivos eletrônicos com portas do mesmo tipo.

## Projeto esquemático do PCB desenvolvido no ambiente Software Eagle


## Vídeo do Falstad

## Alunos

| Nome                      | Nº USP     |
|---------------------------|------------|
| Julia de Almeida Carvalho | 13713184   |
| Kaylaine Bessa da Silva   | 14747506   |
| Giovanna Lopes de Andrade | 14574772   |

