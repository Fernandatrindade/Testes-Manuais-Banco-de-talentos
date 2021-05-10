## Bugs Encontrados
Segue abaixo os bugs encontrados nos testes manuais e testes automatizados, qual quer duvida estou a disposição.


### [Bug 01] - Quando está na tela de cadastro do currículo e clica no botão  Cadastre - se em nosso banco de talentos e apresenta a mensagem “ Sucesso Aplicação realizada com sucesso no banco de talentos.”

#### Funcionalidade: 
Cadastre - se em nosso banco de talentos
#### Cenário: 
Cadastre-se em nosso banco de talentos

#### BDD
1. Um novo usuário irá cadastrar seu currículo na base de talentos
2. Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
3. E clicar no botão Cadastre - se em nosso banco de talentos
4. Então o sistema apresenta a mensagem “ Sucesso Aplicação realizada com sucesso no banco de talentos.”

#### Resultado Atual:  
Quando está na tela de cadastro do currículo e clica no botão  Cadastre - se em nosso banco de talentos e apresenta a mensagem “ Sucesso Aplicação realizada com sucesso no banco de talentos.”, conforme a evidência em anexo.

![Bug1](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%201%5D.png)

#### Resultado Esperado: 
O botão Cadastre - se em nosso banco de talentos ser removido ou escondido da tela de cadastro do currículo para o usuário não clicar no mesmo. 

### [BUG 02] -  Ao selecionar um País  X e clicar novamente para selecionar outro país, o  sistema não mostra os demais países para serem selecionados e apresenta somente o último país que foi selecionado caso não tenha selecionado nenhum apresenta o primeiro cadastrado.

#### Funcionalidade: 
Cadastrar Currículo
#### Cenário: 
Cadastrar um novo/editar currículo 

#### Pré condições: 
1. Ter logado no sistema

#### BDD
1. Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
2. Quando preencher o telefone 
3. E selecionar Sim no radio button caso o número do telefone for o mesmo do WhatsApp 
4. Quando o número do telefone for diferente do WhatsApp selecionar  Não no radio button
5. E  preencher o numero do WhatsApp
6. E  preencher o Email
7. E preencher o Email novamente
8. E preencher o Nome completo
9. E selecionar o Gênero
10. E preencher o Nascimento
11. E selecionar o Status civil
12. E selecionar a Senioridade
13. E preencher a Pretensão salarial
14. E scroller a página até o Endereço
15. E selecionar/preencher o País
16. E clicar em no País para selecionar 
17. Então o sistema traz só um países

#### Resultado Atual: 
Ao selecionar um País  X e clicar novamente para selecionar outro país, o  sistema não mostra os demais países para serem selecionados e apresenta somente o último país que foi selecionado caso não tenha selecionado nenhum apresenta o primeiro cadastrado.
  
##### Obs: Esse comportamento está acontecendo nas telas de Idioma e Habilidade.

![Bug2](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%202%5D.png)
#### Resultado Esperado: 
O sistema apresentar todos os pais para selecionar
 

### [BUG 03] - [Usabilidade] -  Falta a Label informar Nível de escolaridade

#### Funcionalidade:
Cadastrar Formação
#### Cenário: 
Adicionar uma ou mais formações
#### Pré condições: 
1. Ter logado no sistema
2. Ter executado o Caso de Teste 3 (CT03)

#### BDD
1. Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
2. Quando scroller na página curriculum para acessar o campo de Formação 
3. E preencher  o Curso 
4. E  preencher a Instituição
5. E  selecionar o Nível escolar
6. E selecionar o Nível de escolaridade

#### Resultado Atual:  
Falta a Label Informar Nível de escolaridade
![Bug 3](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%2003%5D.png)

#### Resultado Esperado: 
Ter uma Label informando qual o Nível de escolaridade para o usuário selecionar


### [BUG 04] - Ao selecionar estou cursando no momento, está apresentando a frase o momento, informar uma frase usual para o usuário.
  
#### Funcionalidade: Cadastrar Formação
#### Cenário: Cadastrar Formação

#### BDD
1. Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
2. Quando scroller na página curriculum para acessar o campo de Formação 
3. E preencher  o Curso 
4. E  preencher a Instituição
5. E  selecionar o Nível escolar
6. E verificar na tela as palavras De e Ate
7. E clicar em Estou cursando no momento


#### Resultado Atual: 
Ao selecionar estou cursando no momento, está apresentando a frase o momento, informar uma frase usual para o usuário, por exemplo: Cursando no momento.

##### Obs: O mesmo erro está acontecendo em Experiência 

![Bug 04 ](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%2004%5D.png)
#### Resultado Esperado: 
Ao selecionar estou cursando no momento, apresentar uma frase usual para o usuário, por exemplo: Cursando no momento.



### [BUG 5] - Na opção de selecionar uma habilidade existem umas palavras que não são compatíveis com habilidades
  
#### Funcionalidade:
Cadastrar Habilidades
#### Cenário: 
Cadastrar Habilidades

#### BDD
1. Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
Q2. uando scroller na página curriculum para acessar o campo de Habilidades
3. E selecionar uma  Habilidade
4. E verificar quais habilidade estão no sistema


#### Resultado Atual:  
Nas opções de selecionar uma habilidade existem palavras que não são compatíveis com habilidades, conforme os exemplos abaixo:
+++++++
teste de habilidade
teste Jack
![Bug 5](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%205%5D.png)

#### Resultado Esperado: Nas opções de selecionar uma habilidade constar apenas habilidades.


### [Bug 6] - Quando está na tela de cadastro do currículo e observar a página o Olá está atrás do nome abreviado. 

#### Funcionalidade: 
Cadastre - se em nosso banco de talentos
#### Cenário: 
Um novo usuário irá cadastrar seu currículo na base de talentos

#### BDD
1. Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
2. E observar a página 

#### Resultado Atual:
Quando está na tela de cadastro do currículo e observar a página o Olá está atrás do nome abreviado. 
![Bug 6](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%206%5D.png)

#### Resultado Esperado:
O Olá visível para o usuário 

### [Bug 7] - Estrutural
Erro de estrutura do projeto, foi utilizado o mesmo ID para várias TAGS e conforme a descrição abaixo, o ID e para ser utilizado apenas em uma TAG ou seja o ID e um elemento único, sendo de uso exclusivo da mesmo:

O atributo global id define um identificador exclusivo (ID) que deve ser único por todo o documento. Seu objetivo é identificar o elemento ao navegar por âncoras (usando um identificador de fragmento), quando utilizar scripts ou estilizando (com CSS). Caso precise dar o mesmo nome para uma estrutura de TAGS é recomendado utilizar o name ou o class.

![Bug 7]https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%207%5D.png)


### [Bug 8] - Estrutural
Erro de estrutura do projeto quando se tem uma lista selecionável e uma boa prática utilizar a TAG SELECT do HTML assim ficará mais fácil fazer os testes automatizados em cima da tag utilizando o Selenium.
![Bug 8](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%208%5D.png)

### Atomação de Teste 
1. Erro ao selecionar uma lista de valores exemplo: Genero, Estado civil etc. No Selenium existe a possibilidade de selecionar uma lista que está dentro de uma tag do tipo Select do HTML porém no projeto não tem essa tag ai o Selenium não consegue selecionar um valor.
![Bug Auto1](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%208%5D.png)

2. O chat bot da Sólides Jobs esta na frente do botão  Salvar dados e ir para próxima etapa, por tanto imposibilitando o teste automatizado clicar no botão, foi feito uma tentantiva de clicar no botão fechar do chat bot porém o mesmo não fechar.
![Bug Auto2](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BBug%20Auto2%5D.png)

## Melhorias Encontradas

#### [Melhorias 01] - Colocar uma Margem na box da Nayara Corporation para separar o conteúdo da box das Vagas

#### Funcionalidade: Home Page

Dado ao acessar a url https://nayaracorporation.solides.jobs/
E observar a grid principal
Então a box das vagas abertas está grudado com a box da Nayara Corporation

#### Resultado Esperado: 
Colocar uma Margem na box da Nayara Corporation para separar o conteúdo da box das Vagas
![Melhoria 1](https://github.com/Fernandatrindade/Testes-Manuais-Banco-de-talentos/blob/main/%5BMelhoria%2001%5D.png)

## [Melhorias 02] - Melhorar a frase abaixo, apresentando quais campos obrigatórios que não foram preenchidos. “Atenção Existem campos obrigatórios que não foram preenchidos”

#### Funcionalidade: 
Cadastrar currículo

Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
Quando preencher o telefone 
E selecionar Sim no radio button caso o número do telefone for o mesmo do WhatsApp 
Quando o número do telefone for diferente do WhatsApp selecionar  Não no radio button
E  preencher o numero do WhatsApp
E  preencher o Email
E preencher o Email novamente
E preencher o Nome completo
E selecionar o Gênero
E clicar no botão Salvar dados e ir para próxima etapa
Então o sistema mostra a frase de atenção


#### Resultado Esperado:
Melhorar a frase abaixo, apresentando quais campos obrigatórios que não foram preenchidos. “Atenção Existem campos obrigatórios que não foram preenchidos”


### [Melhorias 03] - Melhoria de usabilidade do sistema, colocar um asterisco vermelho (*) para preencher os campos obrigatórios

#### Funcionalidade: 
Cadastrar currículo

1. Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
2. Quando preencher o telefone 
3. E selecionar Sim no radio button caso o número do telefone for o mesmo do WhatsApp 
4. Quando o número do telefone for diferente do WhatsApp selecionar  Não no radio button
5. E  preencher o numero do WhatsApp
6. E  preencher o Email
7. E preencher o Email novamente
8. E preencher o Nome completo
9. E selecionar o Gênero
10. E clicar no botão Salvar dados e ir para próxima etapa
11. Então o sistema mostra a frase de atenção

#### Resultado Esperado: Melhoria de usabilidade do sistema, colocar um asterisco vermelho (*) para preencher os campos obrigatórios.

### [Melhorias 04] - Melhoria de usabilidade do sistema, colocar uma frase de salve com sucesso, no cadastro e na edição.

#### Funcionalidade: 
Cadastrar currículo

1. Dado ao acessar o site https://nayaracorporation.solides.jobs/curriculum
2. Quando preencher o telefone 
3. E cadastrar/editar um currículo 
4. Então o sistema salva e aparece carregando.

#### Resultado Esperado:
Colocar uma frase de salve com sucesso, no cadastro e na edição do currículo.

### [Melhorias 05] - Melhoria se possivel na estrutura HTML do projeto para ficar mais facil nos testes automatizados. 

