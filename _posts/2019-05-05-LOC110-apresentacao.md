---
title: LOC110 - Prazer em conhecê-lo!
updated: 2019-05-05 21:39
---

## O LOC110

Esse dispostivo é um optoacoplador linear no qual o par óptico é composto de apenas um LED emissor, mas dois fotodiodos. É chamado linear pois as relações de corrente entre seus elementos são proporcionais entre si. 
Um desses diodos é chamado de **fotodiodo servo** (_servo photodiode_) e o outro de **fotodiodo de saída** (_output photodiode_).

![Diagrama do LOC110](/assets/posts/2019-05-05-LOC110-apresentacao/2019-05-05-LOC110-apresentacao.png){: .center-image }

#### output photodiode

Por esse diodo pode circular uma corrente relacionada ao fluxo luminoso do LED emissor ( $$I_(c_2)$$ ). Essa corrente se relaciona por uma constante $$K_2$$ com a corrente do LED emissor ($$I_f$$).  

$$I_(c_2) = K_2I_f$$

#### servo photodiode

Já esse outro diodo é utilizado para dar um _feedback_ que auxilia no controle do LED emissor. Ele tende a possuir caracaterísticas idênticas ao fotodiodo de saída. Ele portanto tende a responder ( $$I_(c_1)$$ ) idêntica ao outro fotodiodo. Mas como nem tudo é perfeito, ele possui um constante de relação $$K_2$$

$$I_(c_1) = K_1I_f$$

# Artigo em produção... Luigi trabalhando...
