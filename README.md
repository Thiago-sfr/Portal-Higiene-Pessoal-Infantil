# Portal Higiene Pessoal Infantil

**Higiene Pessoal na Educação Infantil: Cuidar do Corpo é Cuidar da Saúde**

Portal web interativo sobre higiene pessoal para alunos do **6º ano do Ensino Fundamental**, desenvolvido dentro do projeto de extensão universitária **"Conexão Saúde na Escola: Integração Interdisciplinar para a Promoção do Bem-Estar"**, da **UNIFG – Campus Boa Vista**.

## Sobre o projeto

A higiene pessoal é um conjunto de hábitos fundamentais para a promoção da saúde, a prevenção de doenças e a qualidade de vida. Durante a infância e a adolescência, é importante estimular esses hábitos de forma educativa, acessível e participativa, para que os alunos entendam a importância de cuidar do próprio corpo.

A escola é um espaço de aprendizagem, convivência e formação de hábitos. Por isso, o projeto leva à sala de aula atitudes simples do dia a dia: lavar corretamente as mãos, fazer a higiene bucal, tomar banho, cuidar das unhas e dos cabelos, usar roupas limpas e manter a higiene antes e depois das refeições. O objetivo é incentivar a autonomia e a responsabilidade dos alunos com os cuidados individuais e coletivos.

O projeto une os cursos de saúde e tecnologia da UNIFG para trabalhar o tema de forma **lúdica, acessível e interdisciplinar**.

## Objetivos

**Objetivo geral:** promover a conscientização dos alunos sobre a importância da higiene pessoal, incentivando hábitos saudáveis e contribuindo para a prevenção de doenças e a promoção da saúde.

**Objetivos específicos:**

- Compreender o conceito de higiene pessoal e sua importância para a saúde
- Identificar os principais hábitos de higiene da rotina diária
- Orientar sobre a maneira adequada de higienizar as mãos
- Incentivar a prática adequada da higiene bucal
- Conscientizar sobre a importância do banho e do uso de roupas limpas
- Estimular os cuidados com unhas, cabelos, pele e demais partes do corpo
- Mostrar a relação entre higiene pessoal e prevenção de doenças
- Incentivar a autonomia dos alunos nos cuidados pessoais
- Promover responsabilidade individual e coletiva com a higiene
- Estimular a participação dos alunos por meio de atividades educativas e tecnológicas

## Público-alvo e aplicação

- **Público:** alunos do 6º ano do Ensino Fundamental, podendo envolver também professores e profissionais da escola
- **Data:** 04/11/2026 (quarta-feira), das 8h às 12h
- **Turmas atendidas:** 3

Em cada turma, a atividade segue quatro etapas:

1. Aula introdutória e levantamento do que os alunos já sabem sobre higiene
2. Exposição dos conteúdos: mãos, higiene bucal, banho, cabelos, unhas e roupas
3. Dinâmica com o jogo eletrônico 3D, transmitido na TV da sala por um notebook
4. Discussão final e encerramento

## O portal

Este repositório contém o portal web do projeto: uma página interativa organizada como um caderno de atividades, em que os alunos leem, jogam e testam o que aprenderam. Funciona no computador, no tablet e no celular.

### Capítulos

1. O que é higiene pessoal
2. Banho e cuidados com o corpo
3. Higiene bucal
4. Higiene das mãos
5. Cabelos, unhas, roupas e objetos pessoais
6. Higiene na adolescência e higiene menstrual
7. O que devemos evitar
8. Quiz
9. Meu compromisso

### Atividades interativas

| Capítulo | Atividade |
|---|---|
| Banho | Montar os passos do banho na ordem certa |
| Higiene bucal | Escovar o dente arrastando o dedo ou o mouse sobre as manchas de placa |
| Mãos | Cronômetro de 40 segundos que guia cada passo da lavagem, junto com o vídeo da OMS |
| Objetos pessoais | Jogo "Posso compartilhar?": decidir quais objetos podem ser emprestados |
| Adolescência | Cartas que viram ao tocar |
| Quiz | 7 perguntas, uma por vez, com explicação de cada resposta e nota final |
| Meu compromisso | O aluno escreve o nome, escolhe os hábitos e imprime um cartão |

Todas as atividades podem ser refeitas quantas vezes for preciso. No rodapé, o botão **"Reiniciar para o próximo visitante"** apaga todas as respostas e volta ao início. A página não salva nenhum dado dos alunos.

## O jogo eletrônico 3D

Além do portal, a equipe de Ciência da Computação desenvolveu um jogo eletrônico especialmente para a atividade. O jogador é um astronauta que percorre os corredores de uma nave espacial, com portas, salas e um labirinto, até chegar à sala de comando.

No caminho há criaturas alienígenas sujas. Se o astronauta entrar na sala errada, precisa enfrentá-las sem se sujar. Se ficar sujo, deve encontrar a sala de limpeza e fazer a higiene pessoal para baixar o nível de sujeira, mostrado por uma barra na tela. **A porta da sala de comando só abre se o astronauta estiver limpo.**

Em sala, alguns alunos são escolhidos para jogar enquanto a turma acompanha na TV e ajuda o jogador a tomar as decisões em tempo real.

## Como abrir o portal

Não precisa instalar nada.

- **Mais simples:** baixe o repositório e abra o arquivo `index.html` no navegador.
- **Recomendado:** abra a pasta no VS Code e use a extensão **Live Server** (botão "Go Live"). Assim o vídeo do YouTube funciona normalmente. Abrindo o arquivo direto do computador, o YouTube pode bloquear o vídeo.

É preciso internet para o vídeo e para as fontes. O restante funciona offline. Para apresentar, use **F11** e deixe o navegador em tela cheia.

### Estrutura

```
index.html              página completa (HTML, CSS e JavaScript)
Imagens/
  ilustracoes/          ilustrações de cada capítulo
  unifg.png             logo da UNIFG
```

### Tecnologias

- HTML, CSS e JavaScript puro, sem frameworks ou bibliotecas
- Layout responsivo para computador, tablet e celular
- Fontes Bricolage Grotesque e Atkinson Hyperlegible (Google Fonts)

## Equipe

Equipe multidisciplinar dos cursos de saúde e tecnologia da UNIFG – Campus Boa Vista:

- **Ciência da Computação** (desenvolvimento do jogo 3D e aplicação da dinâmica com os alunos): Bruno Ferreira, José Diógenes, Fabio José, Fábio Henrique, Thiago Rodrigues e Luiz Ricardo
- **Enfermagem** (orientação sobre higiene pessoal e promoção da saúde): Maria Vitória, Deyse Vieira e Paula G.
- **Terapia Ocupacional** (condução das atividades práticas e adaptação da dinâmica ao público-alvo): Robson Carlos e Gabriele Mendonça
- **Nutrição** (hábitos de higiene associados à alimentação): Armando F.
- **Apoio geral** na organização e execução: Jéssica F. e Catherine Nogueira

**Orientação:** Profª Karla Pires Moura Barbosa (UNIFG)

## Créditos

- Vídeo "Como lavar as mãos": Organização Mundial da Saúde (OMS)

## Licença

Distribuído sob a licença MIT. Veja o arquivo [LICENSE](LICENSE).
