## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
A especificação suplementar é um documento em linguagem natural que tem o objetivo de descrever os requisitos não funcionais que não foram suficientemente atingidos pelas outras técnicas de modelagem, como o Casos de Uso.
</p>

<p style="text-indent: 20px; text-align: justify">
Sendo assim, o objetivo deste documento é listar os requisitos não funcionais de forma mais detalhada do aplicativo e-Título, que é objeto do nosso projeto de levantamento de requisitos.
</p>

## 2. Documento

### 2.1 Introdução

<p style="text-indent: 20px; text-align: justify">
Este documento captura os requisitos de sistema que não foram identificados nos Casos de Uso do Modelo de Casos de Uso e também nos Léxicos criados. Os quais são listados na área de Elicitação de requisito e também priorização, temos como foco listar requisitos que não tangiam as técnicas utilizadas.
</p>

#### 2.1.1 Finalidade

<p style="text-indent: 20px; text-align: justify">
Definir requisitos não funcionais que os outros métodos não conseguiram definir.
</p>

#### 2.1.2 Referências Bibliográficas

<p style="text-indent: 20px; text-align: justify">
Nos baseamos nas tarefas anteriores e também nas funcionalidades que o aplicativo oferece.
</p>

#### 2.1.3 Escopo

<p style="text-indent: 20px; text-align: justify">
O e-Título é um aplicativo estatal que tem o objetivo de ser uma via digital do documento título de eleitor, podendo neste também ter acesso às informações e declarações mais importantes que fazem parte da Justiça Eleitoral.
</p>

### 2.2 Funcionalidade

#### 2.2.1 Especificações do equipamento (Hardware) e Suportabilidade

<p style="text-indent: 20px; text-align: justify">
O hardware que suporte este aplicativo deve ser: </p>
</p>

- Dispositivo portátil dotado de sistema operacional Android 6.0 ou superior ou iOS 11.0 ou superior;
- Possuir sensor de câmera especificação superior a 2 megapixels;
- Possuir sensor de localização;
- Possuir conexão com a Internet, de forma a ser possível estabelecer a comunicação aplicativo - servidor de dados;
- O sistema deve funcionar fora do Brasil;
- O aplicativo deverá funcionar nos sistemas operacionais mobile Android (superior a 6.0) e iOS (superior a 11.0);
- O aplicativo deve relacionar as rotas e localizações com os principais aplicativos da categoria presente no mercado: Google Maps, Waze, Uber e Apple Maps;
- O aplicativo deve possuir diálogo com as funções de notificação dos diferentes sistemas operacionais suportados.

### 2.3 Usabilidade

- Apresentar as funcionalidades de uma forma mais visual;
- Demonstrar como as funcionalidades acontecem;
- Aumentar a acessibilidade para usuários com dificuldades;
- As funções do aplicativo não devem ser cansativas;
- O aplicativo deverá ter um design intuitivo.

### 2.4 Confiabilidade

- O aplicativo deverá manter os dados do usuário seguros;
- Tenha alguma forma de autenticação para utilizar o sistema, que garanta segurança;
- As notícias sobre a eleição deverão ser imparciais.


### 2.5 Desempenho

- O sistema deve ser responsivo e cada comando não deve demorar mais que 5 segundos;
- O sistema não deve executar funções que necessitem processamento exagerado;
- O sistema deverá notificar o usuário sem falhas.

### 2.6 Restrições de Design

<p style="text-indent: 20px; text-align: justify">
Esta seção reúne as decisões quanto ao design estabelecido e aplicado no e-Título, refletindo o padrão adotado para o uso em diferentes plataformas e a adaptação às alterações conforme o formato de exibição de informações, caracterizando a forma de utilização e o grau de contato entre o usuário e o aplicativo.
</p>

- A aplicação devera ter uma acessibilidade maior, não só para deficientes visuais, mas também para analfabetos tecnológicos.

### 2.7 Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line

<p style="text-indent: 20px; text-align: justify">
O aplicativo deve possuir dentro de sua própria interface um manual, em formato de perguntas e respostas frequentes que auxiliem ou introduzem o usuário inexperiente ou menor capacitado a utilizar as suas de forma igualitária.
</p>

### 2.8 Interfaces

#### 2.8.1 Interfaces do Usuário

<p style="text-indent: 20px; text-align: justify">
O aplicativo deve possuir uma interface gráfica que suporte telas sensíveis ao toque. Essa mesma interface deve ser seu design construído a partir de informações em texto e ícones.
</p>
<p style="text-indent: 20px; text-align: justify">
O mesmo deve possuir barra de navegação inferior, que categorize as funções do aplicativos em acessos diretos simplificados.
</p>

#### 2.8.2 Interfaces de Hardware

<p style="text-indent: 20px; text-align: justify">
O hardware deve ser capaz de executar as operações computacionais de forma suficiente a se enquadrar no requisito de desempenho relativo a executar as funções em menos de 5 segundos. Deve possuir tela sensível ao toque, para interação com o sistema, captar QR Code por meio de sensor, assim como a localização do usuário, e por último, ser capaz de conectar-se com a internet. 
</p>


#### 2.8.3 Interfaces de Software

<p style="text-indent: 20px; text-align: justify">
Para ajudar na manutenção e viabilizar a eficiência no desenvolvimento, a plataforma deve usufruir de linguagens e frameworks que satisfaçam esses quesitos.
</p>

#### 2.8.4 Interfaces de Comunicação

<p style="text-indent: 20px; text-align: justify">
A plataforma deve possuir uma interface de comunicação compatível em suportar as diversas requisições de dados do sistema de forma a manter a integridade de todos os dados. Além de comunicação por meio de micro serviço que possibilitará o registro de contas e armazenamento de mídias na biblioteca do aplicativo.
</p>

## Referências e Bibliografias

> Cin-UFPE; Exemplo: Especificação Complementar; 2001; Disponível em <https://www.cin.ufpe.br/~gta/rup-vc/extend.formal_resources/guidances/examples/resources/supplspec_v1.htm>. Acesso em: 16/03/2020

> Vazquez, Carlos Eduardo; Simões, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. BRASPORT. 1ª edição (2016)

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 19/03/2021 | Elaboração da documentação de especificação suplementar | Todos os integrantes |
| 2.0 | 30/04/2021 | Enumeração dos tópicos e reorganização do documento | Gabriel e Ítalo |