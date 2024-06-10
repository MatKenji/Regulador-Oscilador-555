# Regulador-Oscilador-555
Este projeto descreve a criação de um circuito oscilador regulador utilizando o temporizador LM555.
O LM555 é um CI versátil e amplamente utilizado em projetos de temporização, geração de pulsos e oscilação. Neste projeto, o objetivo é projetar e implementar um circuito oscilador cuja frequência pode ser regulada, montado em uma placa de circuito impresso (PCB).

Objetivos
Desenvolver um circuito oscilador usando o LM555.
Permitir a regulação da frequência do oscilador.
Projetar a PCB para montagem do circuito.
Fornecer todos os arquivos necessários para a fabricação da PCB.

Componentes Necessários
1 x LM555
2 x Capacitores 
2 x Resistores 
1 x Potenciômetro 
1 x Fonte de alimentação 
Conectores e headers para entrada e saída

Esquema do Circuito
O circuito básico de um oscilador com o LM555 pode ser configurado no modo astável. A frequência do oscilador é determinada pelos componentes R1, R2 (resistores) e C1 (capacitor). Para permitir a regulação da frequência, um potenciômetro pode ser adicionado no lugar de um dos resistores fixos.
![esquematico](https://github.com/MatKenji/Regulador-Oscilador-555/assets/169562589/2ec66411-8f27-4b97-a106-90ccdf5f5e25)


Fórmula para a Frequência
A frequência de oscilação 𝑓 é dada por:
𝑓=1.44/(R1+2*R2)*C1
