# cap-02

Aviso: Não vou enfiar equações e fórmulas aqui. Sem saco nenhum de mexer com latex ou algo do tipo. Agradeço se alguém quiser contribuir. Beijos de luz do Arthur.  

FTRD = Função de Transferência de Ramo Direto  
Compensação em série (ou cascata)  
Compensação em paralelo (ou por realimentação)

## Tipos de compensadores

### Avanço de Fase

*A resposta em regime permanente a uma excitação senoidal apresenta um avanço
da fase.* Tá, mas que porra é essa?  
Eu acredito que quando você colocar uma senoide na criança, depois de infinito tempo, a resposta vai sair avançada de fase/ângulo.  
Pelo visto, você acaba:

1) Adicionando zeros a FTMA do sistema e desloca o SR para a Esquerda
2) Tornando a "acomodação" (seja lá que diabo isso seja) mais rápida.
3) Adiciona um controle derivativo PD (que eu já esqueci em AMSD) ao sistema
4) Querendo sair no soco com o professor.

**Ainda tá nada claro essa parada, mas vamos seguir em frente**

### Atraso de Fase

*Se você enfiar uma senoide no sistema e esperar um tempão, verá que a saída estará com a fase/ângulo atrasada*

Colocando um compensador de atraso de fase, você acaba:

1) Desloca o LR para a direita
2) Ainda querer sair no soco com o professor
3) Você adiciona pólos agora.
4) Torna a resposta de acomodação (????) mais **lenta**
5) Adiciona um controle integral PI ao sistema (ai ai, lembro mais de nada :'( )

### Atraso e avanço de fase

A resposta em regime permanente um atraso em frequências baixinhas e e um avanço de fase nas de alta frequências. **Mas eu não tenho ideia do que isso significa por agora, siga tristemente em frente.**

#### Resuminho/Ideia chave

Avanço de fase -> Quando o seu sistema tiver uma porcaria com a resposta transitória, você enfia um compensador de avanço de fase para poder corrigir isso  

Atraso de fase -> Você olha o sistema e fala: "po, tá um lixo essa resposta a longo prazo". Aí você aprende que tem que enfiar um compensador de atraso de fase para poder corrigir.  

Tome um descanso, daqui pra frente, o que já estava ruim, agora vai piorar.  

### Compensações e adições de fase

Vamos ver umas três combinações, pelo menos:

1) Compensação em Série por avanço de fase
2) Compensação em Série por atraso de fase
3) Compensação em Paralelo

Se você tinha alguma esperança na matéria, pode-se considerar um guerreiro. Daqui pra baixo é gravar receita de bolo e fazer exercício, como sempre.

#### Compensação em Série por avanço de fase



#### Compensação em Série por atraso de fase

#### Compensação em Paralelo
