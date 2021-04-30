# Validação por pontos de vista

## Introdução

<p style="text-indent: 20px; text-align: justify">
A análise e comparação utilizando a técnica de viewpoint é um processo informal proposto por Ross 'SADT e Mullery's CORE, eles são semelhantes ao que chamamos de "uso de verificação informal" e dependem fortemente de serem realizados por um bom analista de sistemas. Em suma, a técnica de ponto de vista é um processo que identifica discrepâncias entre duas diferentes visões, classifica e avalia essas discrepâncias e integra as soluções alternativas em uma única representação.
</p>

## Domínio

<p style="text-indent: 20px; text-align: justify">
O domínio utilizado para os dois pontos de vista é o próprio domínio geral da aplicação, tendo base todos os artefatos gerados.
</p>

## Perspectivas
<p style="text-indent: 20px; text-align: justify">
Dentro do contexto de uma <i>view</i> existem três perspectivas possiveis, somente uma delas será abordada nesse documento.
</p>

## *Viewpoint* A

```
Perspectiva de Processo:
    ((usuario =id-usuario =nome =numero-titulo)
     (titulo =numero-titulo =zona-eleitoral =secao)
     (justificativa =decriscao =eleicao)
     (documentos =certidao-nada-consta =certidao-quitacao =guia-debito-eleitoral)
     (autenticacao =qrcode =codigo-de-validacao)
     (notifacoes =noticias =horario-eleicao)
     (foto =url))


Hierarquia:
 (é um
       (objeto (titulo justificativa documentos autenticacao notificacoes foto))
       (agente (usuario)))
 
 (parte de
       (objeto (usuario id-usuario nome numero-titulo)
               (foto url))
       (objeto (titulo numero-titulo zona-eleitoral secao)
               (usuario id-usuario nome numero-titulo))
       (objeto (justificativa descricao eleicao)
               (usuario id-usuario nome numero-titulo))
       (objeto (documentos certidao-nada-consta certidao-quitacao guia-debito-eleitoral)
               (usuario id-usuario nome numero-titulo))
       (objeto (titulo numero-titulo zona-eleitoral secao)
               (autenticacao qrcode codigo-de-validacao))
       (objeto (documentos certidao-nada-consta certidao-quitacao guia-debito-eleitoral)
               (autenticacao qrcode codigo-de-validacao))
       (objeto (notificacoes noticias horario-eleicao)))
```

## *Viewpoint* B

```
Perspectiva de Processo:
    ((usuario =id-usuario =nome =numero-titulo =email =senha =cep =biometria)
     (titulo =numero-titulo =zona-eleitoral =secao)
     (justificativa =decriscao =eleicao)
     (documentos =certidao-nada-consta =certidao-quitacao =guia-debito-eleitoral)
     (autenticacao =qrcode =codigo-de-validacao)
     (mesario =id-mesario =nome =titulo)
     (notifacoes =noticias =horario-eleicao))

Hierarquia:
 (é um
       (objeto (titulo justificativa documentos autenticacao notificacoes))
       (agente (usuario mesario)))
 
 (parte de
       (objeto (titulo numero-titulo zona-eleitoral secao)
               (usuario id-usuario nome numero-titulo email senha cep biometria)
               (autenticacao qrcode codigo-de-validacao))
       (objeto (mesario id-mesario nome titulo)
               (usuario id-usuario nome numero-titulo email senha cep biometria)
               (titulo numero-titulo zona-eleitoral secao))
       (objeto (justificativa descricao eleicao)
               (usuario id-usuario nome numero-titulo email senha cep biometria))
       (objeto (documentos certidao-nada-consta certidao-quitacao guia-debito-eleitoral)
               (usuario id-usuario nome numero-titulo email senha cep biometria)
               (autenticacao qrcode codigo-de-validacao)))
```

## Identificação e Classificação

<p style="text-indent: 20px; text-align: justify">
Após a realização e definição das <i>views</i> identificamos em A e em B e listaremos a seguir as discrepâncias já classificadas.
</p>

### Inconsistências

#### Fatos em A

<p style="text-indent: 20px; text-align: justify">
Não há inconsistências em A.
</p>


#### Fatos em B

<p style="text-indent: 20px; text-align: justify">
Não há inconsistências em B.
</p>

### Fatos Errados

#### Fatos em A

- Faltam atributos no usuário.

#### Fatos em B

- O agente mesario tem atributo titulo e depois é definido que titulo faz parte do mesario.

### Fatos faltantes

#### Fatos em A

- Voluntariar-se (ação)
- Editar (ação)
- Local de votação (objeto)
- Ativar/desativar notificações (ação)

#### Fatos em B

- Foto (objeto)
- Voluntariar-se (ação)
- Editar (ação)
- Local de votação (objeto)
- Ativar/desativar notificações (ação)

## Avaliação

<p style="text-indent: 20px; text-align: justify">
Esta fase consiste em propor soluções alternativas para os pontos de vistas.
</p>

### Solução alternativa para A
<p style="text-indent: 20px; text-align: justify">
Inclusão dos fatos faltantes com seus respectivos atributos. Corrigir os fatos errados.
</p>

### Solução alternativa para B
<p style="text-indent: 20px; text-align: justify">
Inclusão dos fatos faltantes com seus respectivos atributos. Corrigir os fatos errados.
</p>

## Integração

<p style="text-indent: 20px; text-align: justify">
Nesta fase integramos as soluções propostas em uma solução conciliada de ambas os pontos de vista. </br>
</p>

<p style="text-indent: 20px; text-align: justify">
O ponto de vista B contém seus fatos, em grande maioria melhor definidos, que os fatos em A. Nota-se que há alguns fatos faltantes em ambos os pontos de vista, fatos do tipo de ação, e alguns do tipo objeto também não foram apresentados. É evidente que os agentes são coerentes com o domínio.
</p>


## Referências

> do Prado Leite, Julio Cesar Sampaio, and Peter Freeman. "Requirements validation through viewpoint resolution." IEEE Trans. Software Eng. 17.12 (1991): 1253-1269.

> Messaoudi, Mohammed. "Requirements Engineering Through Viewpoints." International Journal of Computing 2.2 (2013): 49-59.

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 15/04/2021 | Desenvolvimento da Validação por Viewpoint | João Pedro |
