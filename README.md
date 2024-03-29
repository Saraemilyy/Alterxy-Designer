<img src="./SRC/Alterxy-Logo.png">

# <a href="https://help.alteryx.com/pt-br/20231/designer/workflows">Alterxy 🎲📊</a>

## Links 📍 
<br>

- <a href="https://github.com/Saraemilyy/Alterxy-Dicionario#comandos-"> Comandos 📝 </a>
- <a href="https://github.com/Saraemilyy/Alterxy-Dicionario#integrando-alteryx-com-python"> Integrando Alteryx com Python</a>
- <a href="https://www.alteryx.com/pt-br"> Site Alterxy Oficial</a>
- <a href="https://community.alteryx.com/?category.id=external-pt-br"> Site Comunidade Alterxy </a>
- <a href="https://help.alteryx.com/pt-br/20231/designer/workflows"> Site Documentação Alterxy </a>
<br>

<hr>

## Comandos 📝
<br>

### Input Data - Dados de Entrada 🗂️
 - Primeiro passo para iniciar o fluxo de dados e configurar a fonte de dados (Única base de dados ou múltiplas)

- Importar várias bases de dados do mesmo tipo. (Ex: 5 planilhas no formato .xlsx)

- Caractere Curinga para importar todos os arquivos da pasta ou com um nome que todos contenham. (Ex: *.xlsx ou se todos tiverem um nome em comum como “abril”, abril *.xlsx)

- Para combinas dados é preciso que os arquivos estejam no mesmo diretório, possuam a mesma quantidade de colunas, ter os mesmos dados, estar na mesma ordem e possuir os mesmos tipos de dados.

- Caso deseje ver de qual arquivo os dados vêm, use a opção "Gerar campo com o nome do arquivo" na configuração da ferramenta Dados de Entrada.
<hr>

### Text Input - Entrada de Texto 📃
- Inserir dados de forma manual, criando  uma tabela no próprio alterxy
<hr>

### Tipos de dados 🎲
- String - Texto
- Number - Número
- Bool - Booleano (True or False)
- Data Time - Data e Hora
- Objetos Geográficos
<hr>

### Comentando dentro das fórmulas

> Inicie colocando // antes do texto a ser comentado .
### Select - Selecionar 🖱️
- Reodernação de dados

- Renomeação de linhas

- Descartar colunas 
<hr>

### Navegation - Navegar 
- Visualizar os dados de uma ferramenta conectada, assim como informações de perfil de dados, mapas, fragmentos de relatório e informações de análise comportamental  nos dados.
<hr>

### Data Cleansing - Limpeza de Dados 🧼
- Remove todas as linhas que apresentam um valor nulo em todas as colunas

- Remova linhas com valores nulos (a ferramenta não remove linhas com cadeias de caracteres vazias).

- Remove apenas as linhas que apresentam um valor nulo em todas as colunas do conjunto.
<hr>

### Unique - Exclusivo❌
- Use a ferramenta Exclusivo para distinguir se um registro é único ou uma duplicata agrupando os dados com base em um ou mais campos especificados e, depois, classificando esses campos.
<hr>

### Filter - Filtro 🗃️
- Aplicar filtros que retornam true e false a depender da condição
<hr>

### Sample - Amostra 📋
- A ferramenta oferece opções para você separar uma parte do seus dados para analisar.

- Selecione  uma das opções de configuração e em seguida defina um valor para N. A saída da ferramenta Amostra inclui apenas os dados especificados e descarta o restante.

<hr>

### Texto para colunas  
- Divide o texto de um campo em linhas ou colunas separadas.

- Se os valores estiverem separados por um delimitador, a ferramenta é uma maneira rápida de realizar essa tarefa.
<hr>

### Exclusivo 
- Separe dados exclusivos e duplicados com base nas colunas selecionadas.

- A ferramenta separa os conjuntos de dados em valores únicos e duplicados.
<hr>

### AutoField - Campo Automático ⌨️
- Organiza seus meta dados automaticamente com base nas informações contida neles (Caso queira mudar manualmente, selecione alguma ferramenta que contenha o Select Tool)
<hr>

### Sort - Ordenar 🗂️
- Organize seus dados com base nos valores de uma ou mais colunas.

- Organize grandes conjuntos de dados classificando as informações em ordem crescente ou descrecente.

<hr>

### Record Id - Id de Registro 🆔
- Ela pode ser utilizada para ordenação, reorganizar o conjunto de dados, e diversos outros usos.

- Caso a ferramenta seja configurada com o tipo String, ela irá completar seus dados com um “0” a esquerda e caso o valor ultrapasse o tamanho máximo, o valor será truncado, como no exemplo abaixo.
<hr>

### Transpose - Transpor 📑
- Gira a orientação dos dados em uma tabela movendo dados verticais para um eixo horizontal e sumarizando os dados selecionados.

- Alterar o layout do seus dados é outra função importante do Designer. Transformar colunas em linhas e linhas em novas colunas pode ser muito útil para gerar novas ideias ou para usar uma ferramenta específica.

- A ferramenta *Transpor* tranforma linhas em colunas, enquanto a ferramenta *Tabela de referência Cruzada* transforma colunas em linhas. 
<hr>

### Localizar e Substituir 🔎
- Procure por dados em uma coluna de um fluxo de dados e o substitua especificando uma coluna de outro fluxo. Semelhante  a um VlookUp do Excel.

- Essa ferramenta tem duas âncoras de entrada, uma para o conjunto de dados em que os valores devem ser encontrados (Âncora F, do inglês "Find") e outra para a lista de consulta que contém os valores para a substituição (Âncora R, do inglês "Replace").

<hr>

### Tile - Bloco  🗒️
- Use a ferramenta Tile para atribuir um valor (bloco) com base em intervalos nos dados. Cada intervalo de dados em seu DataSet é um bloco. Estas telhas podem ser agrupadas. Você pode selecionar um dos seguintes métodos de agrupamento: soma igual, registros iguais, bloco inteligente, valor exclusivo e bloco manual.

- A ferramenta Tile acrescenta duas colunas aos dados. Número de mosaico é o mosaico atribuído do registo ou linha. Número de sequência de mosaico é o número de registo da posição da linha dentro do mosaico. Cada linha é considerada um registro.

<hr>

### Funções 
- O Designer possui uma biblioteca de funções que é categorizada para ajudá-lo a encontrar o que você precisa, algumas funções só funcionam com um tipo de dado específico, mas outras podem ser aplicadas a qualquer tipo de dados.
<hr>

### Tipos de Funções 
- Expressões Condicionais;

- Valores nulos e vazios

- Cadeia de Caracteres

- Valores Numéricos

- Valores Data/Hora

<hr>

### Summarize - Sumarizar 🔢
- Sumarize dados por meio do agrupamento, soma, contagem, processamento de objetos geográficos, concatenação de cadeias de caracteres e muito mais. A saída contém apenas o resultado do cálculo.
<hr>

### Formule - Fórmula 🧪
- Cria ou atualize colunas usando uma ou mais expressões para executar uma ampla variedade de cálculos e/ou operações.

- Com ela você pode utilizar valores de outras colunas para fazer cálculos, categorizar, converter tipos de dados, formatar valores e muito mais.

- A única limitação é que os valores da expressão estão limitados à linha atual que está sendo processada, ou seja, não é possível fazer relação com valores em linhas anteriores ou posteriores. 

- Uma das principais vantagens da ferramenta Fórmula é que você pode escrever várias expressões usando uma única ferramenta.
<hr>

### Agrupar Campos 
- Adicione os campos de uma entrada de origem a cada registro de uma entrada alvo.

- Cada registro da entrada alvo será duplicado para cada registro na entrada de origem.
<hr>

### Join - Junção ➕
- Combine dois ou mais fluxos de dados com base em campos comuns ou posição dos registros. 

- Na saída combinada (J) cada linha conterá os dados das duas entradas. 
<hr>

### Union - União 🔀
- União de bases de dados
- Combine dois ou mais fluxos de dados em função dos nomes ou posições dos campos. Na 
saída, cada coluna conterá os dados de todas as entradas e os registro serão 
"empilhados" verticalmente.
<hr>

### Output - Dados de Saída 🛑
- Envie o arquivo de um fluxo de trabalho para um arquivo ou base de dados.

- A ferramenta pode gravar vários arquivos com uma única ferramenta.

- Pode gerar os dados no formato de arquivo da sua escolha.
<hr>

## Integrando Alteryx com Python 

### Primeiros passos para implementar Python no  Fluxo
> No fluxo de trabalho, procure na barra de pesquisa a ferramenta chamada "Python" ou vá até a aba chamada "Desenvolvedor" e arraste ela até seu fluxo de trabalho.

> Ligue sua fonte de dados a ferramenta de Python.
<hr>

### Exibindo a fonte de dados na saída do Python
> Abra a ferramenta Python e espere carregar o Jupyter Notebook, após isso atribua a sua fonte de dados a uma variável para ser exibida dentro da tela do Python.
`Exemplo: NomedaVariavel = Alteryx.read("#1")`
<hr>

### Exibindo os dados do Python no Output 
- Para exibir o Dataframe no Output do Alteryx, vamos codar o seguinte:
>`NomedeOutraVariavel = Alteryx.write(NomedaVariavel,1)`
<hr>

### Criando uma nova tabela 
- Para criar uma nova coluna na tabela use o seguinte comando:
>`NomedaVariavel ['Total Vendas'] = sum(NomedaVariavel['ColunaParaRelizarOperaçao'])`
<hr>


### Importando script já pronto no Alteryx

- É possível importar um script Python ou Jupyter Notebook existente utilizando a função de importação do Alteryx. Caso deseje gerenciar caminhos relativos, utilize o comando import na célula. Exemplos de importação incluem o uso do comando import para importar um diretório e o uso da função de importação do Alteryx para importar um único script.

> Clique no menu Alteryx e  selecione `Importar Script`.

> Clique em Escolher arquivo e navegue até um arquivo .py ou .ipynb. e clique em `Importar`.

## Implementando Power BI com Alteryx

- Entre no site <a href="https://help.alteryx.com/pt-br/20231/designer/microsoft-power-bi">Alteryx Power Bi</a> e instale a extensão para adicionar a ferramenta de saída para o Alteryx.
- Dentro do Alteryx vá até a Aba `Desenvolvedor` ou vá até a barra de pesquisa e coloque `Power Bi`.

>&copy; Sara Castro 2023 - Developer Full Stack
