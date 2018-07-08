# css-FlexBox


# Aula_1
  ## Flex | Inline Flex | Container | Flex Itens
  ### Dislay flex e o relacionamento entre flex container e flex
  
  Quando declaramos o display do container||elemento pai como flex, ele se torna uma linha onde pega o conteudo em colunas no tamanho do su conteúdo e o espaço que sobra fica em branco.
  Com o display inline-flex, ele limita o tamanho pelo tamanho do conteúdo.
  Quando se declara um elemento como flex seus filhos IMEDIATOS se tornam flex-itens.

# Aula_2
  ## Flex Directions | Axis | Reverse
  ### Flex Directions:
  #### Row: É o comptamento padrão do flex box. Divide os flex itens em colunas, tornando o container em Linha.
  #### Column: Divide os flex-itens em linhas tornando o container em Coluna
  
  ### Axis
  #### É definido primariamente pela direção do Flex.
  #### Main Axis
        Row: Horizontal: da esquerda para a direira
        Column:  Vertical, cima baixo
  #### Cross Axis
        Row: Vertical, cima baixo
        Column: Horizontal: da esquerda para a direira
  ### Reverse
    Inverte o sentido do Main Axis
# Aula_3: Warp
  ## Warp: nowarp | warp
  ### nowarp
    Por padrão o warp do flex box é nowarp. 
    ouseje, quando a lagura de um flex item é declara de forma que criaria uma barra de rolagem, no flex box o nowarp vai esticar aou maximo a largura do flex item(s) RESPEITANDO O TAMANHO DA TELA!
  ### warp
    quando declarado o warp: warp o flex box vai atender o tamanho do flex-item respeitando o tamanho maximo da tela acumulando o maximo de colunar (flex-direction: row) que couber por linha

# Aula_4 Ordering

  ## Oreder
  ### A propriedade Order é dos flex-itens
    A propridedade order padrão do order tem valor 0, que implica que a ordem d flex será a de declaração dos ementos filhos declarados no html (1º, 2º, 3º, ...)
    Os elementos serão mostrados na tela em ordem crescente ao valor do Order com o critério de desempate a ordem de declaração do elemento.
    
