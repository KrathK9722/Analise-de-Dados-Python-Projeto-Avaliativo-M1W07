# Analise de Dados com Python  MINI-Projeto Avaliativo  Módulo 01 Semana 07

Mini projeto elaborado no decorrer de aproximadamente 4 dias fazendo a análise exploratória dos dados da [Base Varejo](https://www.kaggle.com/datasets/namespaiva/base-varejo/data).

Trabalho feito por: Arthur Henrique Kochan

Turma SCTEC: Análise de Dados com Python - T6
Data de Entrega do trabalho: 2026/09/14


# NOTAS

Sobre o data frame limpo:
Durante minha análise exploratória utilizei principalmente 2 dataframes, 1 dataframe limpo principalmente para dados relacionados a compras e clientes unicos e 1 dataframe limpo com os itens separados 1 em cada linha assim como o dataframe original.
Por conta do tamanho do data frame de itens separados não foi possível fazer upload do mesmo no github.

Download Data Frame compras (Itens unidos em suas respectivas compras): [Link](https://drive.google.com/file/d/1zSaLdgTYFe-gmfMNWCnOtvP-y0GqLnKh/view?usp=sharing)
Download Data Frame itens separados por linha: [Link](https://drive.google.com/file/d/1xT3AHg4wqfsY8--Nx02tfot23mR67Cqw/view?usp=sharing)

[Link google COLAB](https://colab.research.google.com/drive/11dHcnosqvZFcxZgY-A6UTZruNc1c2GJc#scrollTo=Abw9Xsbtqg6e)





# INSIGHTS
 **1. Falha Sistêmica Crítica na Governança de Dados (Setembro/2022)**

A queda drástica nas vendas em setembro de 2022 afetou todas as categorias de produtos de maneira idêntica e simultânea. O gráfico comparativo anual prova que este comportamento não decorre de uma questão sazonal, e sim de um problema interno da empresa (como um apagão sistêmico nos registros dos caixas ou falha grave na exportação do banco de dados). Essa hipótese é reforçada pelo histórico de desorganização da base, que continha colunas vazias, duplicidades e registros sem nome.

 **2. Classe B como Motor do Volume de Vendas**

O segmento econômico B é o verdadeiro pilar de sustentação do faturamento em massa da organização. Ele concentra a grande maioria dos clientes únicos e o maior volume total de notas fiscais emitidas. Campanhas de marketing e ações de fidelidade devem priorizar este público para garantir a estabilidade do fluxo de caixa diário.

 **3. Classe A: Consumo de Alto Volume por Visita (Comportamento de Concentração)**

Embora os clientes da Classe A façam poucas compras no ano (baixo volume de notas fiscais), eles registram o maior ticket médio da empresa, chegando a quase 47 itens por carrinho no público feminino. Esse perfil indica um consumidor de alta renda que prefere concentrar as compras em grandes abastecimentos mensais em vez de fracioná-las. A estratégia ideal para este grupo é a oferta de kits e descontos por volume.

**4. Estabilidade Comportamental entre Gêneros e Estados Civis**

A média de itens por compra é muito parecida para quase todos os estados civis (ficando entre 44 e 45 itens). O grupo de viúvos apresenta uma média maior, chegando a quase 48 itens, porém esse é um grupo muito pequeno na base (apenas 28 clientes) para ditar uma tendência geral. No fim, a grande massa de consumidores compra praticamente a mesma quantidade de produtos para abastecer a casa, o que mostra que nenhum grupo especifico deve ser prioridade e sim táticas que atingam clientes de todos os grupos.

 **5. Presunto Cozido como Produto "Isca" e Giro de Estoque**

O ranking geral de produtos revelou que o Presunto Cozido possui um volume de saída isolado (12.719 unidades), vendendo quase o dobro do segundo colocado (Sardinha). Por ser um produto de altíssimo giro e apelo popular, ele funciona como um item "isca". A empresa deve utilizá-lo estrategicamente em promoções para atrair fluxo de pessoas para as lojas e garantir que nunca haja ruptura (falta) desse item no estoque.
