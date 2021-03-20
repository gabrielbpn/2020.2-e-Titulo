# Priorização baseada em valor, custo e risco

## Introdução

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

## Motivação para a escolha dessa técnica

<p style="text-indent: 20px; text-align: justify">
Optamos por realizar a técnica de priorização baseada em valor, custo e risco, pois com ela conseguiríamos criar um panorama com a técnica MoSCoW, pois a técnica de priorização baseada em valor, custo e risco é uma técnica analítica que pode comprovar matemáticamente a priorização dos requisitos, enquanto que na técnica MoSCoW, a priorização é feita a partir das experiências e deduções que temos a respeito do aplicativo e-Título, suas funções e utilizações.
</p>


## Priorização

### Requisitos funcionais

<div style="display: flex; justify-content: center">
    <style type="text/css">
    .tg  {border-collapse:collapse;border-spacing:0;}
    .tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
    overflow:hidden;padding:10px 5px;word-break:normal;}
    .tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
    font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
    .tg .tg-hsqc{background-color:#006EFF;color:#FFF;font-weight:bold;text-align:center;vertical-align:middle}
    .tg .tg-f4yw{background-color:#FFF;text-align:center;vertical-align:middle}
    .tg .tg-nrix{text-align:center;vertical-align:middle}
    </style>
    <table class="tg">
    <thead>
    <tr>
        <th class="tg-hsqc">Requisitos</th>
        <th class="tg-hsqc">Prioridade</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td class="tg-f4yw">Oferecer tutorial no primeiro uso do app</td>
        <td class="tg-nrix">1,74341</td>
    </tr>
    <tr>
        <td class="tg-f4yw">Verificar autenticidade de documentos</td>
        <td class="tg-nrix">0,80308</td>
    </tr>
    <tr>
        <td class="tg-nrix">Receber notícias da eleição</td>
        <td class="tg-nrix">0,41233</td>
    </tr>
    <tr>
        <td class="tg-nrix">Acessar a área sobre o e-Título</td>
        <td class="tg-nrix">0,38263</td>
    </tr>
    <tr>
        <td class="tg-nrix">Poder voluntariar-se como mesária</td>
        <td class="tg-nrix">0,35675</td>
    </tr>
    <tr>
        <td class="tg-f4yw">Aumentar a acessibilidade para usuários com dificuldades</td>
        <td class="tg-nrix">0,30174</td>
    </tr>
    <tr>
        <td class="tg-nrix">Emitir o guia para o pagamentos de débitos pagamentos</td>
        <td class="tg-nrix">0,28533</td>
    </tr>
    <tr>
        <td class="tg-nrix">Emitir nada consta criminal eleitoral</td>
        <td class="tg-nrix">0,28533</td>
    </tr>
    <tr>
        <td class="tg-nrix">Alterar CEP pelo E-Título</td>
        <td class="tg-nrix">0,26845</td>
    </tr>
    <tr>
        <td class="tg-nrix">Emitir certidão de quitação eleitoral</td>
        <td class="tg-nrix">0,25176</td>
    </tr>
    <tr>
        <td class="tg-nrix">Ativar e desativar notificações</td>
        <td class="tg-nrix">0,23841</td>
    </tr>
    <tr>
        <td class="tg-nrix">Desativar conta no E-Título</td>
        <td class="tg-nrix">0,20464</td>
    </tr>
    <tr>
        <td class="tg-nrix">Enviar feedback</td>
        <td class="tg-nrix">0,19212</td>
    </tr>
    <tr>
        <td class="tg-nrix">Ativar modo escuro</td>
        <td class="tg-nrix">0,09566</td>
    </tr>
    <tr>
        <td class="tg-nrix">Poder acessar o aplicativo por biometria/digital</td>
        <td class="tg-nrix">0,07055</td>
    </tr>
    </tbody>
    </table>
</div>

### Requisitos não funcionais

<div style="display: flex; justify-content: center">
    <style type="text/css">
    .tg  {border-collapse:collapse;border-spacing:0;}
    .tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
    overflow:hidden;padding:10px 5px;word-break:normal;}
    .tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
    font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
    .tg .tg-hsqc{background-color:#006EFF;color:#FFF;font-weight:bold;text-align:center;vertical-align:middle}
    .tg .tg-nrix{text-align:center;vertical-align:middle}
    </style>
    <table class="tg">
    <thead>
    <tr>
        <th class="tg-hsqc">Requisitos</th>
        <th class="tg-hsqc">Prioridade</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td class="tg-nrix">As&nbsp;&nbsp;&nbsp;notícias sobre a eleição deverão ser imparciais</td>
        <td class="tg-nrix">1,18321</td>
    </tr>
    <tr>
        <td class="tg-nrix">Sistema ser enxuto</td>
        <td class="tg-nrix">0,63711</td>
    </tr>
    <tr>
        <td class="tg-nrix">Demonstrar como as funcionalidades acontecem</td>
        <td class="tg-nrix">0,44529</td>
    </tr>
    <tr>
        <td class="tg-nrix">O aplicativo deverá ter um design intuitivo</td>
        <td class="tg-nrix">0,42303</td>
    </tr>
    <tr>
        <td class="tg-nrix">As funções do aplicativo não devem ser cansativas</td>
        <td class="tg-nrix">0,37405</td>
    </tr>
    <tr>
        <td class="tg-nrix">Sistema funcionar fora do Brasil</td>
        <td class="tg-nrix">0,26718</td>
    </tr>
    </tbody>
    </table>
</div>

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 11/03/2021 | Explicação e motivo pela escolha da técnica valor, custo e risco | Ian |
| 1.0 | 11/03/2021 | Priorização pela técnica baseada em valor, custo e risco | Gabriel, Guilherme, Ian, Ítalo, João Pedro |
| 1.0.1 | 18/03/2021 | Revisão gramatical | Ian |