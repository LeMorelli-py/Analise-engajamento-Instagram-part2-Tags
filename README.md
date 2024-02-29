# Analisando o engajamento do Instagram - Parte 2: TAGS

### O que queremos responder?
- Qual a tag mais engaja nessas publicações?
    - Agora queremos olhar apenas tags
<br><br>
- Ele também dá alguns direcionamentos:
    - Podem ignorar a coluna visualizações, queremos entender apenas curtidas, comentários e interações
    - Tags vazias é que realmente não possuem tag (favor tratar como vazio)
 
### Para conseguir analisar separadamente as tags, podemos dividir linhas com 2 tags em 2 linhas
- Para isso primeiro vamos usar o split para separar em uma lista com as tags
- Depois vamos usar o explode para transformar as listas com 2 tags em 2 linhas diferentes

- Tudo que estiver em lista será separado em 1 linha por elemento da lista
- Se não tiver na lista, o elemento será mantido
- Listas vazias vão ter o valor de `NaN`
<br><br>
- Para as outras colunas, elas irão repetir os seus valores
- Inclusive o índice também irá repetir
- **Postagens de promoções são as que mais engajam**
- **Além de promoções, datas comemorativas e trends também possuem um bom engajamento**

## Conclusões
- **Ter o rosto de outras pessoas é fundamental para um bom engajamento na publicação**
    - Em todas as tags, quando havia o rosto, o resultado foi muito melhor
- **Criar campanhas ajuda muito na divulgação da marca**
- **Promoções tiveram um desempenho absurdamente maior que qualquer outra tag**
    - Porém é uma tag que pode ter custo para a loja, o que deve ser analisado
- **Usar conteúdos que estão em trend também ajudam na divulgação da marca, mesmo a trend sendo de outros nichos**
- **A melhor maneira de mostrar produtos é através de outras pessoas utilizando-os, e se possível em campanhas de datas especiais**
- **Para novos produtos a inclusão de pessoas é mais crítica ainda, sendo quase o dobro quando há um rosto junto ao produto**
- **Não podemos afirmar que a tag `Loja` é ruim até testarmos essa tag incluindo pessoas ou em uma campanha. Vale o teste para verificar**
- **Continuaremos a monitorar as postagens para encontrar novos padrões dado que ainda temos poucas informações da base**
