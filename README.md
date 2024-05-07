# SENAI Fullstack [Education]

## Resolução dos exercícios da Semana 01 - Módulo 02

### M2S01 | Roteiro do mini projeto da semana

Iremos, ao longo dessa semana, criar um projetinho simples imitando um questionário online para você criar.

Nesse primeiro momento, criaremos a estrutura html e o css básico de um formulário com 8 perguntas já pré-determinadas, que estão listadas abaixo. Cada pergunta irá receber um tipo específico de input com opções também pré-selecionadas (indicado pela descrição “**Tipo de reposta**” no arquivo).

Pergunta: 1) Como se define um estilo inline em HTML?
Tipo de reposta: campo de texto

Pergunta: 2) Qual é a tag usada para criar uma lista ordenada em HTML?
Tipo de reposta: resposta única com as seguintes opções: ol, ul, li, order-list.

Pergunta: 3) Qual propriedade CSS é usada para alterar a cor do texto?
Tipo de reposta: resposta única com as seguintes opções: font-color, color, background-color, text-color

Pergunta: 4) Como se referencia um arquivo CSS externo em um documento HTML?
Tipo de reposta: campo de texto

Pergunta: 5) Font-size é a propriedade CSS usada para alterar o tamanho da fonte de um texto?
Tipo de reposta: resposta única com as seguintes opções: sim, não.

Pergunta: 6) Qual é a propriedade CSS usada para definir a largura de um elemento?
Tipo de reposta: multiplas respostas com as seguintes opções: height, size, width, max-width.

Pergunta: 7) Como se cria um comentário em CSS?
Tipo de reposta: multiplas respostas com as seguintes opções: <!-- -->, //, /\* \*/.

Pergunta: 8) Qual é a propriedade CSS usada para definir a altura de um elemento?
Tipo de reposta: multiplas respostas com as seguintes opções: height, size, min-height, max-height.

### M2S01 | Ex 1 - Início do projeto (LabQuiz)

Em um arquivo html crie a estrutura base do HTML5 e adicione a importação de um arquivo **CSS externo**.

### M2S01 | Ex 2 - Treinando HTML (LabQuiz)

Para iniciarmos nosso mini projeto, utilizando as tags corretas, crie um cabeçalho onde nele terá:

1.  o título da aplicação (**LabQuiz**);
2.  uma breve descrição explicando sobre a dinâmica do quiz;
3.  um campo de texto para capturar o nome do jogador;
4.  um botão escrito iniciar.

### M2S01 | Ex 3 - Treinando o CSS (LabQuiz)

Para a estilização do cabeçalho, adicione uma cor de fundo que tenha contraste com a cor da fonte que será escolhida por você (só não pode ser preta). Todo o texto deve ser centralizado [ao meio], incluindo o campo e o botão.

Além disso, faça o uso também de uma fonte diferente da que vem por padrão (pode ser **Arial)**. Para a descrição, coloque o tamanho de fonte 24 pixels e, para o título, 40 pixels. A estilização do botão deverá ser semelhante ao print abaixo.

normal:

![RFoOrPUQxVCynwmHXaWmORp1-LBwszWMPMiwW_vPR59tSr4Mc1CTnaFcZBEPFVr464OjgzmleShWlkMeSo2Rcxo05_MGyF7P2ogP0RImY6KUBg9d6PXw0IpdvonKF6_uwOsveQdbkoO97QuVlDZSTuc](https://lh7-us.googleusercontent.com/RFoOrPUQxVCynwmHXaWmORp1-LBwszWMPMiwW_vPR59tSr4Mc1CTnaFcZBEPFVr464OjgzmleShWlkMeSo2Rcxo05_MGyF7P2ogP0RImY6KUBg9d6PXw0IpdvonKF6_uwOsveQdbkoO97QuVlDZSTuc)

efeito hover:

![T9tMGjT4yBupMRxfi0tBVDvYquNDcr9uLcEqwbGtaNbRSOoqn-ilvRpm36R5UEJIOCy8agWb8PubBW2CU4-V-b-jEiaCVitgGkOQpJNwYBPEq7j42_JwXBEvhIbQTWzSKcD4KYfD_qTgr_bv9U74wVw](https://lh7-us.googleusercontent.com/T9tMGjT4yBupMRxfi0tBVDvYquNDcr9uLcEqwbGtaNbRSOoqn-ilvRpm36R5UEJIOCy8agWb8PubBW2CU4-V-b-jEiaCVitgGkOQpJNwYBPEq7j42_JwXBEvhIbQTWzSKcD4KYfD_qTgr_bv9U74wVw)

**OBS: as cores devem ser diferentes da do exemplo.**

### M2S01 | Ex 4 - Treinando HTML (LabQuiz)

Mais abaixo da página, com algum tipo de separador, divida o cabeçalho da aplicação do corpo do quiz.

Feito isso, em uma tag main, adicione os campos do quiz: a ideia é que seja feito o uso das tags corretas para capturar as respostas de cada pergunta, dependendo do que foi passado no campo **Tipo de resposta** de cada pergunta.

### M2S01 | Ex 5 - Treinando CSS (LabQuiz)

Para a estilização dos campos de input do tipo texto, crie um design semelhante ou igual ao exemplo em anexo.

normal:

![fpBc5qhc9FGsoGqSgaidoHweLirSxFRLdps5UGOlgYir5v9Mo0ALrUknBCaid1inf212o4abXyZ7Q08hoyUHyPOTiUtBYels9t8_O8e6-3uC8Zf3_X86Q832rqVdi6tgCaM3mwDGv5_SBidLu_yCehw](https://lh7-us.googleusercontent.com/fpBc5qhc9FGsoGqSgaidoHweLirSxFRLdps5UGOlgYir5v9Mo0ALrUknBCaid1inf212o4abXyZ7Q08hoyUHyPOTiUtBYels9t8_O8e6-3uC8Zf3_X86Q832rqVdi6tgCaM3mwDGv5_SBidLu_yCehw)

efeito foco:

![oiOwmMt5IO0Ef76yhzK7lpBRw9vfymVkXdFEPWt5xglJswo5r2wh_YsRCcSKa2MAM8wfdteG2f1UbqOaq5cWw67q4WmxzMA7YIqCSqW6ymWRP-PFYk97-hjvBED-LZV9pmxRpXL9l_Lq8A3VsQD-_Ho](https://lh7-us.googleusercontent.com/oiOwmMt5IO0Ef76yhzK7lpBRw9vfymVkXdFEPWt5xglJswo5r2wh_YsRCcSKa2MAM8wfdteG2f1UbqOaq5cWw67q4WmxzMA7YIqCSqW6ymWRP-PFYk97-hjvBED-LZV9pmxRpXL9l_Lq8A3VsQD-_Ho)

OBS: pode até parecer que o campo no efeito normal possui uma borda mas ele não tem; mas, adicione uma sombra para poder marcar o limite do campo.

### M2S01 | Ex 6 - Rodapé (LabQuiz)

Para finalizar o projeto, crie um rodapé com a tag footer, indicando que foi você que fez aquela plataforma; ao clicar no seu nome, o site deve redirecionar para o seu perfil no github. Existe um tag html apropriada para isso: faça o seu uso.
