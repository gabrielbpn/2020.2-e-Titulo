## Introdução

<p style="text-indent: 20px; text-align: justify">
Um cenário é basicamente uma história sobre pessoas realizando uma
atividade (Rosson e Carroll, 2002), e a partir deste pretexto, vamos adotar a técnica para descrever os cenários que o e-Título tange e pode ser acessível para cada função.

</p>

## Objetivo

<p style="text-indent: 20px; text-align: justify">
Os cenários podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e avaliar se um produto satisfaz a necessidade dos seus usuários (Rosson e Carroll, 2002).
O objetivo da adoção da técnica neste projeto é tentar prever possíveis cenários que atinjam nossos casos de uso ou não, fazendo com que tenhamos a noção se nossa diagramação dos casos de uso tangem todos os casos que podem ser feitos em diferentes cenários pelos seu usuários, sendo uma técnica que requer menos custo e tempo quando comparados com modelos e protótipos complexos. Um cenário descreve o comportamento e a experiência de um ator(es).
</p>

## Cenários

### Realizar cadastro

|Cenário|Descrição|
|:---:|:---|
|Título|Realizar cadastro|
|Objetivo|Permitir que os usuários realizem cadastro no aplicativo.|
|Contexto|Local: Entrar a primeira vez no aplicativo. <br/> Pré-condição: Ter o app instalado, ter tirado o título de eleitor físico. <br/> Pós-condição: Usuário realiza a inscrição.|
|Atores|Usuário votante que deseja utilizar o aplicativo.|
|Recursos|Conexão de internet, aplicativo instalado, informações do título de eleitor físico.|
|Episódios|Usuário entra pela primeira vez no aplicativo. <br/> Usuário informa o nome completo, a data de nascimento, o número de inscrição do título de eleitor, o nome do pai e da mãe.|
|Exceção|Internet cair. <br/> Número de inscrição do título de eleitor inválido. <br/> Não possuir Título de Eleitor. |

### Fazer login

|Cenário|Descrição|
|:---:|:---|
|Título|Fazer login|
|Objetivo|Fazer login para pessoas cadastradas|
|Contexto|Entrar no aplicativo.<br/>Pré-condição: Ter o app instalado e acesso a internet.<br/>Pós-condição: Usuário realiza a inscrição.|
|Atores|Usuário votante que deseja utilizar o aplicativo.|
|Recursos| Aplicativo instalado e lembrar da senha ou ter configurado a biometria.|
|Episódios|Usuário já utilizou o aplicativo em uma eleição e vai tentar fazer login novamente|
|Exceção| Não possuir cadastro no e-Título. |

### Ver e-Título

|Cenário|Descrição|
|:---:|:---|
|Título|Ver e-Título|
|Objetivo|Visualizar o título de eleitor digital.|
|Contexto|Local: Local de votação, entrar no aplicativo.<br/>Tempo: Período eleitoral.<br/>Pré-condição: Usuário necessita ter o app instalado e cadastro realizado.<br/>Pós-condição: Usuário tem em mãos o título de eleitor digital, que substitui a necessidade do físico em caso de necessidade.|
|Atores|Usuário|
|Recursos| Aplicativo instalado e acesso ao aplicativo.|
|Episódios|Usuário já cadastrou-se no aplicativo.<br/>Usuário participa como eleitor de alguma eleição.<br/>Usuário realiza login.<br/>Usuário acessa o e-título na página inicial.|
|Exceção|Usuário não ter cadastro no aplicativo.|

### Verificar onde votar

|Cenário|Descrição|
|:---:|:---|
|Título| Verificar onde votar |
|Objetivo| Permitir que o ator possa visualizar o seu local de votação |
|Contexto| Local: Entrar no aplicativo. <br/>Pré-condição: ter o app instalado e cadastro realizado.<br/>Pós-condição: Usuário tem em mãos o local que ele precisa ir para votar <br/>|
|Atores| Usuário. |
|Recursos| Conexão de internet, aplicativo instalado e acesso ao aplicativo. |
|Episódios| Usuário já se cadastrou no aplicativo. <br/>Usuário participa como eleitor em alguma eleição.<br/>Usuário acessa a parte da localização e verifica seu local de votação|
|Exceção| Conexão de internet instável. <br/>Indisponibilidade do aplicativo.<br/> |

### Acessar notificações

|Cenário|Descrição|
|:---:|:---|
|Título| Acessar notificações |
|Objetivo| Acessar informações e notícias que o aplicativo expõe ao usuário |
|Contexto| Local: Entrar no aplicativo. <br/> Pré-condição: Ter o app instalado, cadastro realizado. <br/> Pós-condição: O usuário é notificado com relação a mudança de local de votação, alertas sobre desinformações, e outros informações relevantes. |
|Atores| Usuário |
|Recursos| Conexão de internet, aplicativo instalado e acesso ao aplicativo. |
|Episódios| Usuário já se cadastrou no aplicativo. <br/> Usuário acessa a página de notificações. <br/> Usuário visualiza suas notificações. |
|Exceção| Sem conexão com a internet. <br/> Acessa a página mais não possui nenhuma notificação. |

### Emitir documentos eleitorais

|Cenário|Descrição|
|:---:|:---|
|Título| Emitir documentos eleitorais. |
|Objetivo| Disponibilizar o certificado de quitação eleitoral, certificado de nada consta criminal eleitoral e guias para pagamentos de débitos eleitorais. |
|Contexto| Entrar no aplicativo. <br/> Pré-condição: Possuir cadastro no aplicativo. <br/> Pós-condição: O documento é mostrado ao usuário. |
|Atores| Usuário |
|Recursos| Conexão de internet. |
|Episódios| Usuário acessa o aplicativo e-Título. <br/> Usuário seleciona a função Mais opções. <br/> Usuário seleciona a opção do documento que deseja possuir. |
|Exceção| Indisponibilidade do aplicativo.<br/> Conexão de internet instável.|

### Validar documentos

|Cenário|Descrição|
|:---:|:---|
|Título| Validar documentos eleitorais |
|Objetivo| Validar o certificado de nada consta. |
|Contexto| Entrar no aplicativo. <br/> Pré-condição: Ter um documento de nada consta já emitido, podendo ser falso ou não|
|Atores| Mesário ou usuário |
|Recursos| Conexão de internet, aplicativo instalado e acesso ao aplicativo. |
|Episódios| Usuário já se cadastrou no aplicativo. <br/>Usuário acessa parte de mais opções<br/> Usuário acessa a opção de verificação de certificado de nada consta |
|Exceção| Indisponibilidade do aplicativo.<br/> Conexão de internet instável.|

### Justificar ausência

|Cenário|Descrição|
|:---:|:---|
|Título|Justificar ausência|
|Objetivo|Justificar ausência de forma online.|
|Contexto| Local: Entrar no aplicativo. <br/> Tempo: Durante ou ao fim de um período eleitoral. <br/> Pré-condição: Possuir o app instalado, já ter realizado cadastro. <br/> Pós-condição: Usuário estar nos conformes com a justiça eleitoral.|
|Atores|- Usuário.|
|Recursos| Conexão de internet. |
|Episódios| Usuário já se cadastrou no aplicativo. <br/> Usuário acessa a parte de mais opções. <br/> Usuário acessa a opção de justificar ausência. |
|Exceção|Indisponibilidade do aplicativo. <br/> Conexão de internet instável.|

### Ver local de justificativa

|Cenário|Descrição|
|:---:|:---|
|Título|Ver local de justificativa|
|Objetivo|Verificar local para justificativa de ausência de forma presencial.|
|Contexto| Local: Entrar no aplicativo. <br/> Tempo: Durante ou ao fim de um período eleitoral. <br/> Pré-condição: Possuir o app instalado, já ter realizado cadastro. <br/> Pós-condição: Usuário estar nos conformes com a justiça eleitoral.|
|Atores|- Usuário.|
|Recursos| Conexão de internet. |
|Episódios| Usuário já se cadastrou no aplicativo. <br/> Usuário acessa a parte de mais opções. <br/> Usuário acessa a opção de verificar local de justificativa presencial. |
|Exceção|Indisponibilidade do aplicativo. <br/> Conexão de internet instável.|

### Ver local de terceiros

|Cenário|Descrição|
|:---:|:---|
|Título| Ver local de terceiros. |
|Objetivo| Visualizar o local de votação de uma pessoa que não possui o aplicativo. |
|Contexto| Entrar no aplicativo. <br/> Pré-condição: Possuir cadastro no aplicativo. <br/> Pós-condição: Visualizar o local de votação de um terceiro. |
|Atores| Usuário <br/> Pessoa sem o aplicativo  |
|Recursos| Conexão de internet. |
|Episódios| Usuário acessa o aplicativo e-Título. <br/> Usuário seleciona a função Mais opções. <br/> Usuário seleciona a opção de local de votação de terceiros <br/> Informa a data de nascimento, nome da mãe, e os dados de um tipo de documento (CPF, número do título ou nome da pessoa), da pessoa que o usuário queira ver o local da votação. |
|Exceção| Indisponibilidade do aplicativo.<br/> Dados incorretos da pessoa que o usuário deseja ver o local de votação <br/> Sem conexão de internet.|

### Ver perguntas e respostas frequentes

|Cenário|Descrição|
|:---:|:---|
|Título| Ver perguntas e respostas frequentes. |
|Objetivo| Visualizar as perguntas e respostas para dúvidas que o usuário possa ter. |
|Contexto| Entrar no aplicativo. <br/> Pré-condição: Possuir cadastro no aplicativo. <br/> Pós-condição: Visualizar as respostas. |
|Atores| Usuário |
|Recursos| Plataforma mobile. |
|Episódios| Usuário acessa o aplicativo e-Título. <br/> Usuário seleciona a função Mais opções. <br/> Usuário seleciona a opção de Perguntas e respostas. <br/> Usuário seleciona a pergunta sugerida que deseja obter resposta. |
|Exceção| Indisponibilidade do aplicativo. |

### Saber mais sobre aplicativo

|Cenário|Descrição|
|:---:|:---|
|Título| Saber mais sobre o aplicativo. |
|Objetivo| Ver mais informações sobre o aplicativo. |
|Contexto| Entrar no aplicativo. <br/> Pré-condição: Possuir cadastro no aplicativo. <br/> Pós-condição: Visualizar informações sobre o e-Título. |
|Atores| Usuário |
|Recursos| Plataforma mobile. |
|Episódios| Usuário acessa o aplicativo e-Título. <br/> Usuário seleciona a função Mais opções. <br/> Usuário seleciona a opção Sobre o e-Título. |
|Exceção| Indisponibilidade do aplicativo. |

### Consultar os termos de uso do aplicativo

|Cenário|Descrição|
|:---:|:---|
|Título| Consultar os termos de uso do aplicativo. |
|Objetivo| Visualizar os termos de uso e política de privacidade do aplicativo. |
|Contexto| Entrar no aplicativo. <br/> Pré-condição: Possuir cadastro no aplicativo. <br/> Pós-condição: Visualizar os termos de uso. |
|Atores| Usuário |
|Recursos| Plataforma mobile. |
|Episódios| Usuário acessa o aplicativo e-Título. <br/> Usuário seleciona a função Mais opções. <br/> Usuário seleciona a opção Termos de uso. |
|Exceção| Indisponibilidade do aplicativo. |

### Trocar senha para acesso

|Cenário|Descrição|
|:---:|:---|
|Título| Trocar senha de acesso ao aplicativo. |
|Objetivo| Trocar senha do seu login no aplicativo. |
|Contexto| Entrar no aplicativo. <br/> Pré-condição: Possuir cadastro no aplicativo. <br/> Pós-condição: Senha trocada com sucesso. |
|Atores| Usuário |
|Recursos| Conexão de internet. |
|Episódios| Usuário acessa o aplicativo e-Título. <br/> Usuário seleciona a função Mais opções. <br/> Usuário seleciona a opção Trocar senha. <br/> Usuário digita nova senha. |
|Exceção| Indisponibilidade do aplicativo. |


## Referências

>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação.

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 19/03/2021 | Criação do cenários | Todos os integrantes |