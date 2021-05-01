## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
Essa é uma técnica de priorização analítica que após identificados os requisitos essenciais ao produto a ser entregue, pode ser utilizada para classificar a importância relativa dos requisitos restantes. Para estimar essa prioridade relativa dos requisitos, adota-se conceitos do QFD (Quality Function Deployment), na qual é distribuído um conjunto de classificações, que são: 
</p>

- **Valor** que o cliente atribui para o benefício fornecido a um requisito específico que seja incorporado;
- Uma **penalidade** caso o requisito esteja ausente;
- O **Valor total**;
- O **Custo relativo**;
- O **Risco relativo**;
- E a **Prioridade** que é obtida através das outras classificações.

<p style="text-indent: 20px; text-align: justify">
A importância de um requisito é diretamente proporcional ao valor que ele agrega e inversamente proporcional ao seu custo e riscos associados à sua implementação.
</p>

## 2. Motivação para a escolha dessa técnica

<p style="text-indent: 20px; text-align: justify">
Optamos por realizar a técnica de priorização baseada em valor, custo e risco, pois com ela conseguiríamos criar um panorama com a técnica MoSCoW, pois a técnica de priorização baseada em valor, custo e risco é uma técnica analítica que pode comprovar matemáticamente a priorização dos requisitos, enquanto que na técnica MoSCoW, a priorização é feita a partir das experiências e deduções que temos a respeito do aplicativo e-Título, suas funções e utilizações.
</p>

## 3. Priorização

### 3.1 Requisitos funcionais

<center>

| Requisito | Descrição | Prioridade |
|:--:|:--:|:--:|
| RF02 | Oferecer tutorial no primeiro uso do app | 1,74341 |
| RF09 | Verificar autenticidade de documentos | 0,80308 |
| RF20 | Receber notícias da eleição | 0,41233 |
| RF24 | Acessar a área sobre o e-Título | 0,38263 |
| RF12 | Poder voluntariar-se como mesário | 0,35675 |
| RF22 | Emitir o guia para o pagamentos de débitos eleitorais | 0,28533 |
| RF27 | Emitir nada consta criminal eleitoral | 0,28533 |
| RF34 | Alterar CEP pelo e-Título | 0,26845 |
| RF26 | Emitir certidão de quitação eleitoral | 0,25176 |
| RF31 | Ativar e desativar notificações | 0,23841 |
| RF32 | Desativar conta no e-Título | 0,20464 |
| RF33 | Enviar feedback | 0,19212 |
| RF30 | Ativar modo escuro | 0,09566 |
| RF16 | Poder acessar o aplicativo por biometria/digital | 0,07055 |

<figcaption>Tabela 1 - Requisitos funcionais e suas prioridades</figcaption>

</center>

### 3.2 Requisitos não funcionais

<center>

| Requisito | Descrição | Prioridade |
|:--:|:--:|:--:|
| RNF12 | Notícias sobre a eleição deverão ser imparciais | 1,18321 |
| RNF04 | Sistema ser enxuto | 0,63711 |
| RNF02 | Demonstrar como as funcionalidades acontecem | 0,44529 |
| RNF13 | O aplicativo deverá ter um design intuitivo | 0,42303 |
| RNF11 | As funções do aplicativo não devem ser cansativas | 0,37405 |
| RNF06 | Sistema funcionar fora do Brasil | 0,26718 |

<figcaption>Tabela 2 - Requisitos não funcionais e suas prioridades</figcaption>

</center>

## Referências e Bibliografias

>WIEGERS, Karl; BEATTY, Joy. "Software Requirements". Microsoft Press, 2013.

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 11/03/2021 | Explicação e motivo pela escolha da técnica valor, custo e risco | Ian |
| 1.0 | 11/03/2021 | Priorização pela técnica baseada em valor, custo e risco | Gabriel, Guilherme, Ian, Ítalo, João Pedro |
| 1.0.1 | 18/03/2021 | Revisão gramatical | Ian |
| 2.0 | 30/04/2021 | Padronização e inserção de legendas nas tabelas | Gabriel |