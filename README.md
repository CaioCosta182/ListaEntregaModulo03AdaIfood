# Lista Modulo03 Ada-Ifood

<h1>Contador de Itens de Hortifrutis</h1></br>
A função contarItens realiza a contagem de itens pertencentes a diferentes categorias de hortifrutis, tais como frutas, legumes e verduras. Abaixo estão as principais características do código:</br>

<h2>Estrutura do Código:</h2></br>
Definição de Tipos: O código define um objeto chamado tipos, que mapeia categorias (frutas, legumes, verduras) para suas respectivas listas de itens.</br></br>

Contagem Inicial: Um objeto contagem é inicializado para armazenar a contagem de itens de cada categoria (inicialmente configurado com zero para todas as categorias).</br>

Iteração sobre Hortifrutis: O código utiliza um loop forEach para iterar sobre a lista de hortifrutis fornecida como parâmetro.</br>

Verificação de Categoria: Para cada item na lista, a função verifica a qual categoria ele pertence (fruta, legume ou verdura) usando a estrutura condicional if-else.</br>

Atualização da Contagem: Com base na categoria identificada, a contagem correspondente é incrementada.</br>

Retorno da Contagem: Ao final da execução, a função retorna o objeto de contagem com a quantidade de itens em cada categoria.</br>


<h1>Verificação de Salários dos Empregados</h1></br>
O código realiza a verificação de salários dentro de uma lista de empregados. Aqui estão os principais pontos do código:</br></br>

<h2>Estrutura do Código:</h2></br>
Lista de Empregados: O código define uma lista de empregados, cada um representado por um objeto com propriedades nome e salario.</br></br>

Verificação de Salário Maior ou Igual a R$ 1.500,00: Utiliza o método some para verificar se pelo menos um empregado tem um salário maior ou igual a R$ 1.500,00.</br>

Mensagem de Resultado: Se há empregados com salários maiores ou iguais a R$ 1.500,00, o código utiliza o método find para encontrar o primeiro empregado que atende a essa condição e imprime uma mensagem informando o nome do funcionário encontrado. Caso contrário, exibe uma mensagem indicando que nenhum empregado possui tal salário.</br>

Verificação de Salário Menor ou Igual a R$ 1.000,00: Similarmente, utiliza o método some para verificar se pelo menos um empregado tem um salário menor ou igual a R$ 1.000,00.</br>

Mensagem de Resultado para Salário Menor ou Igual a R$ 1.000,00: Se a verificação for positiva, encontra o primeiro empregado que atende a essa condição usando find e imprime uma mensagem informando o nome do funcionário encontrado. Caso contrário, exibe uma mensagem indicando que nenhum empregado possui tal salário.


<h1>Cálculo do Índice de Massa Corporal (IMC) para Pessoas</h1></br>
O código realiza o cálculo do Índice de Massa Corporal (IMC) para uma lista de pessoas, usando a fórmula padrão: IMC = peso / altura². Aqui estão os principais pontos do código:</br></br>

<h2>Estrutura do Código</h2></br>
Lista de Pessoas: O código define uma lista de pessoas, onde cada pessoa é representada por um objeto com as propriedades nome, altura e peso.</br></br>

Função para Calcular IMC: A função calcularIMC é declarada para calcular o IMC com base no nome, altura e peso fornecidos como argumentos. O resultado é formatado usando toFixed(2) para exibir apenas duas casas decimais.</br>

Iteração sobre Pessoas: Utiliza o método forEach para iterar sobre a lista de pessoas. Para cada pessoa, chama a função calcularIMC e imprime o resultado no console.</br>

<h1>Cálculo da Média das Notas dos Alunos</h1></br>
O código realiza o cálculo da média das notas para cada aluno em uma lista. Aqui estão os principais pontos do código:</br></br>

<h2>Estrutura do Código</h2></br>
Lista de Alunos: O código define uma lista de alunos, onde cada aluno é representado por um objeto com as propriedades nome e notas (uma lista de notas).</br></br>

Cálculo da Média: Utiliza o método map para criar um novo objeto para cada aluno, contendo o nome e a media. A média é calculada usando o método reduce para somar as notas e dividir pelo número de notas (3 neste caso).</br>

Formatação da Média: Utiliza toFixed(2) para formatar a média com duas casas decimais.</br>

Exibição do Resultado: Imprime no console o array alunosComMedia que contém objetos com os nomes e médias calculadas para cada aluno.</br>

