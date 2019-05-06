---
title: LOC110, um optoacoplador linear - Prazer em conhecê-lo!
updated: 2019-05-05 21:39
---

## O LOC110

Esse dispostivo é um optoacoplador linear capaz de isolar até 3750 $$V_{rms}$$ no qual o par óptico é composto de apenas um LED emissor, mas dois fotodiodos. É chamado linear pois as relações de corrente entre seus elementos são proporcionais entre si. 
Um desses diodos é chamado de **fotodiodo servo** (_servo photodiode_) e o outro de **fotodiodo de saída** (_output photodiode_).

![Diagrama do LOC110](/assets/posts/2019-05-05-LOC110-apresentacao/2019-05-05-LOC110-apresentacao.png){: .center-image }

#### output photodiode

Por esse diodo pode circular uma corrente relacionada ao fluxo luminoso do LED emissor ( $$I_{c_2}$$ ). Essa corrente se relaciona por uma constante $$K_2$$ com a corrente do LED emissor ($$I_f$$).  

$$I_{c_2} = K_2I_f$$

#### servo photodiode

Já esse outro diodo é utilizado para dar um _feedback_ que auxilia no controle do LED emissor. Ele tende a possuir caracaterísticas idênticas ao fotodiodo de saída. Ele portanto tende a responder ($$I_{c_1}$$) idêntica ao outro fotodiodo. Mas como nem tudo é perfeito, ele possui um constante de relação $$K_2$$

$$I_{c_1} = K_1I_f$$

Com esse tipo de construção é possível compensar características de resposta em frequência e variações por temperatura, já que o fotodiodo servo permite operar o circuito com em uma malha de realimentação virtual.

#### aplicações 

Umas das aplicações desse tipo de componente é em aparelhos de medição e teste industriais, sistemas de comunicação e médicos. Em geral, aplicações que requeiram lineariedade entre os sinais de entrada, além do isolamento galvânico entre eles.

### referências

1. [LOC110](http://www.ixysic.com/home/pdfs.nsf/www/LOC110.pdf/$file/LOC110.pdf)
2. [Application Note: AN-107 - LOC Series Linear Optocouplers](http://www.ixysic.com/home/pdfs.nsf/www/AN-107.pdf/$file/AN-107.pdf)		
3. [Application Note 50 - Designing Linear Amplifiers Using IL300 Optocoupler](https://www.vishay.com/docs/83708/appnote50.pdf)
