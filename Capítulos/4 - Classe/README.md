<style>
table {
    margin: auto;
}
</style>

# Capítulo 4 - Classes
Classe é o que representa o papel do seu personagem. É como sua especialidade dentro da profissão de aventureiro.
Ela indica o treinamento que o personagem recebeu e através disso, as habilidades que ele possui e que vai possuir caso continue exercitando o que foi ensinado.

Toda classe possúi seis informações iniciais:</br>
**Pontos de Vida:** Vida base da classe e o incremento de níveis acima do primeiro.</br>
**Pontos de Energia:** Quantidade de energia ganha por nível.</br>
**Perícias:** Uma perícia obrigatória e uma quantidade de perícias extras para escolha.</br>
**Salvaguardas:** Salvaguardas em dois atributos.</br>
**Acesso à Magia:** Caso a classe conceda acesso à algum tipo de magia o tipo será descrito nesse campo.</br>
**Proficiências:** Conhecimentos que a classe disponibiliza.</br>
**Habilidade Nativa:** Habilidade que o personagem ganha ao iniciar o primeiro nível desta classe

Ao criar o personagem, o jogador deverá escolher uma classe e adicionar os seis pontos específicos (descritos acima) desta classe na sua ficha.
Ao acumular experiência de aventura o personagem avança de nível, isso permite que ele adiquira um novo nível de uma classe. O jogador é livre para escolher evoluir na mesma classe ou optar por escolher uma nova classe, esta segunda opção é conhecida como multiclasse e será descrita abaixo.
Ao evoluir em uma classe o jogador basicamente incrementará seus pontos de vida e energia de acordo com a classe e poderá escolher uma nova habilidade da lista da classe.
Seguem as classes básicas do sistema:

| Classe                                   |                                        Descrição                                        |
| ---------------------------------------- | :-------------------------------------------------------------------------------------: |
| [Bárbaro](./barbaro/README.md)           |   Combatente primitivo que luta com seus instintos através de um fúria incontrolável    |
| [Bardo](./bardo/README.md)               |   Aventureiro especializado em lídar com multidões através de performances artísticas   |
| [Bruxo](./bruxo/README.md)               | Usuário de magia ocultista que acessa seus poderes através de um pacto com uma entidade |
| [Caçador](./cacador/README.md)           |                         Combatente focado em espreitar um alvo                          |
| [Clérigo](./clerigo/README.md/README.md) |                   Usuário de magia divina que é fiel a uma divindade                    |
| [Druida](./druida/README.md)             |                  Protetor da natureza especializado em magias primais                   |
| [Feiticeiro](./feiticeiro/README.md)     |          Usuário de magia que acessa seus poderes herdados de seus ancestrais           |
| [Guerreiro](./guerreiro/README.md)       |                  Combatente habilidoso em técnicas avanças de batalha                   |
| [Intendente](./intendente/README.md)     |    Combatente que representa o grupo e forma estratégias para auxiliá-los em combate    |
| [Ladino](./ladino/README.md)             |       Especialista em perícias que foca em atacar inimigos em seus pontos fracos        |
| [Lutador](./lutador/README.md)           |                         Combatente focado em combate desarmado                          |
| [Mago](./mago/README.md)                 |      Usuário de magias arcanas que acessa seus poderes através do estudo da magia       |
| [Paladino](./paladino/README.md)         |               Combatente determinado que vive a vida em prol de uma causa               |

## Multiclasses

Caso o jogador tenha optado por fazer multiclasse, ele precisará recalcular seus pontos de vida iniciais com base em uma média entre a soma dos pontos de vida iniciais de cada classe.
A energia apenas adiciona a quantidade de acordo com o nível dessa classe nova.
As proficiências serão cumulativas entre as classes.
Para perícias, é necessário verificar qual das classes possui a maior quantidade de treinamentos, este número base deve ser levado em conta pois será o máximo de perícias que o personagem será treinado. Cada classe possui uma pericia obrigatória, então ao adiquirir multiclasse você terá mais de uma obrigatória, essas deverão sempre constar e o restante do valor total poderão ser escolhidas de quaisquer das classes que o personagem possua.
O jogador deverá escolher duas salvaguardas disponíveis na lista das duas classes.
As habilidades nativas também serão cumulativas, porém, para os cálculos do seu funcionamento apenas o nível da classe específica e não do personagem.

Para explicar melhor vamos exemplificar: Joojanthal é um bárbaro nível 1 e decide pegar um level de mago no seu nível 2 de personagem.
Ao fazer isso seus pontos de vida deixam de ser 26 (24 + 2 de constituição), e passam a ser 18 (16 + 2 de constituição). Esse número 18 é referente a 24 do Barbaro somados a 8 do mago, dividido por 2 e incrementando 2 de modificador de constituição ao seu final.
Sua energia sai de 3 para 9.
Suas proficiências continuam as mesmas, Armas marciais e escudos, já que o mago não incrementa nesse ponto.
Suas perícias serão alteradas. Joojanthal possuia Atletismo e Acrobacia. Seu novo nível de mago lhe permite ter um total de 4 perícias ao invés de 2.
Sendo assim, suas duas obrigatórias passam a ser Atletismo e Misticismo, e duas novas da lista das duas classes podem ser escolhidas. Joojanthal optou por escolher dedução e história, o que fez ele desaprender acrobacia.
Das salvaguardas ele optou por permanescer com Constituição e ganhar destreza.