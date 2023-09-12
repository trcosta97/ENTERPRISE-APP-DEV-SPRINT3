# HearMeOut - Enterprise Application Development - Sprint 3

## Sobre a solução  
O App "HearMeOut" resolveria o problema de acessibilidade para usuários com deficiência visual na plataforma da Plusoft, permitindo que eles possam interagir com os diversos segmentos da empresa (saúde, seguros, agronegócio, serviços, bens de consumo, educação, telecom, financeiro, utilities e varejo) de forma mais fácil e intuitiva por meio de um chatbot com funcionalidades de voz.
Com a criação de um chatbot em forma de áudio, essas pessoas terão a possibilidade de tirar suas dúvidas e receber informações de forma mais acessível e inclusiva. A iniciativa busca, portanto, promover a igualdade de oportunidades e o acesso à informação para pessoas com deficiência visual.
Nesse caso, a iniciativa também promove a inclusão e acessibilidade para um público mais amplo, ampliando o alcance e a utilidade do serviço oferecido. A acessibilidade deve ser uma preocupação de todos, e a inclusão de opções de áudio pode tornar o chatbot mais acessível e eficiente para diferentes públicos.

## Desenho de arquitetura  
![devops-sprint2](https://github.com/trcosta97/crud-user-hearmeout/assets/101136329/70150ebd-d7cc-47c3-b7d4-9655c9736b7e)

## Principais funcionalidades  
### Login  
<img src="https://github.com/trcosta97/ENTERPRISE-APP-DEV-SPRINT3/assets/101136329/d1b6d710-599f-4e34-8d1f-a03626a2a68a" alt="MicrosoftTeams-image (3)" width="300px">

#### 1-Verificação de Cadastro Existente:  

- O chat inicia uma interação questionando se o usuário já possui um cadastro no HerMeOut.  

#### 2-Login por Reconhecimento de Voz:  

- Caso o usuário prefira, ele pode fornecer suas informações de login através da fala.  
- Estas informações incluem o nome de usuário (CPF, CNPJ ou e-mail) e a senha.  

#### 3-Validação dos Dados:  

- O chat imediatamente valida as informações inseridas pelo usuário.  

#### 4-Tratamento de Dados Incorretos:  

- Se os dados estiverem incorretos, o chat identifica os erros e guia o usuário na correção.  

#### 5-Recuperação de Senha:  

- Adicionalmente, a opção "Esqueceu sua senha? clique aqui" está disponível para auxiliar usuários que tenham esquecido suas senhas.  
- O sistema orienta o usuário através do processo de recuperação de senha de maneira simplificada.  

#### 6-Alternativa de Registro:  

- Caso persistam problemas, o chat oferece a opção de criação de uma nova conta no aplicativo.  
- Essa alternativa é particularmente útil para usuários que ainda não possuem um cadastro no sistema.

### Cadastro
![MicrosoftTeams-image (1)](https://github.com/trcosta97/ENTERPRISE-APP-DEV-SPRINT3/assets/101136329/e01b21b6-0ed6-4813-9058-2a768e18c232)


#### 1-Introdução e Instruções Auditivas:  

- O chat inicia explicando o processo de registro por meio de instruções em áudio.  
- Orienta o usuário a seguir cada passo, prometendo assistência durante todo o processo.  

#### 2-Campo CPF/CNPJ:  

- Comandos de voz são utilizados para que o usuário insira o CPF ou CNPJ.  
- O chat oferece repetição do que foi registrado para confirmação.  

#### 3-Campo Nome Completo:  

- O chat guia o usuário para ditar o nome completo.  
- Oferece exemplos de formatação e repetir o nome para confirmação.  

#### 4-Campo Senha:  

- Instruções detalhadas são dadas para que o usuário crie uma senha segura.  
- Dicas sobre caracteres especiais, números, etc. São fornecidas em áudio.  

#### 5-Confirmação de Senha:  

- O chat pede ao usuário para repetir a senha escolhida.  
- Isso ajuda a evitar erros na confirmação.  

#### 6-Validação e Identificação de Erros:  

- O chat verifica imediatamente a validade dos dados inseridos.  
- Se algum dado estiver incorreto, uma mensagem de áudio é usada para destacar o campo específico.  

#### 7-Confirmação e Próximos Passos:  

- O chat destaca o botão de confirmação e orienta o usuário a ativá-lo.  
- Após a confirmação, mensagens de áudio parabenizam o usuário e oferecem orientações para a próxima etapa.  

#### 8-Apoio Contínuo:  

- Durante todo o processo, a opção de solicitar ajuda auditiva está disponível.  
- O chat está pronto para responder as perguntas e fornecer assistência adicional.

### Bate-Papo
![MicrosoftTeams-image (4)](https://github.com/trcosta97/ENTERPRISE-APP-DEV-SPRINT3/assets/101136329/bf9b9a9f-02a6-4dcb-b418-3be1a9a3488f)


#### 1-Iniciando o Bate-Papo:  

- O usuário inicia o bate-papo com um especialista selecionando a opção "Converse com Nossos Especialistas".  

#### 2-Identificação da Comunicação:  

- O aplicativo informa ao usuário que ele está em comunicação direta com um especialista.  
- Isso assegura que o usuário esteja ciente do tipo de interação em que está envolvido.  

#### 3-Opção de Comunicação em Áudio:  

- Ao digitar ou falar, o usuário pode escolher enviar mensagens em áudio para o especialista.  
- Essa opção está disponível tanto para usuários com deficiência visual quanto sem.  

#### 4-Interatividade Acessível:  

- Usuários com deficiência visual podem enviar mensagens em áudio como uma opção acessível.  
- Usuários sem deficiência visual também podem aproveitar essa funcionalidade.  

#### 5-Respostas em Áudio:  

- O especialista responde por meio de mensagens em áudio ou texto, dependendo da preferência do usuário.  
- Isso permite uma comunicação bidirecional flexível.  

#### 6-Conversas Claras e Objetivas:  

- As conversas podem abranger uma variedade de tópicos, permitindo aos usuários obter orientações, esclarecer dúvidas e receber suporte direto.  

#### 7-Encerrando a Conversa:  

- Ao concluir a interação com o especialista, o usuário pode encerrar a conversa de forma simples.  
- Um botão de encerramento estará visível na interface do chat, facilmente identificável.







