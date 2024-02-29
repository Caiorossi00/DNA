<h1>DNA</h1>

O script dna.py é uma projeto em Python que realiza a análise de sequências de DNA, comparando-as com perfis de referência armazenados em um arquivo CSV. Através da identificação de padrões conhecidos como Short Tandem Repeats (STRs), o programa determina a correspondência entre a sequência fornecida e os perfis da base de dados. Ao identificar uma correspondência exata, exibe o nome associado ao perfil correspondente. Caso contrário, informa "No match". Essa aplicação é útil em aplicações forenses e de identificação genética, onde a análise precisa de STRs é crucial para a identificação de indivíduos.
<br>
Principais componentes do script:
<ul>
  <li><strong>Função `longest_match`</strong>: Determina o comprimento da sequência mais longa consecutiva de um subconjunto (STR) em uma sequência de DNA.</li>
  <li><strong>Função `main`</strong>: Lida com a leitura da base de dados e da sequência de DNA a partir de arquivos fornecidos como argumentos de linha de comando (sys.argv). Calcula as contagens de cada STR na sequência de DNA e compara com as contagens na base de dados.</li>
  <li><strong>Verificação de Command-Line</strong>: Garante o uso correto do script, fornecendo uma mensagem de uso caso contrário.</li>
  <li><strong>Impressão de Resultados</strong>: Imprime o nome da pessoa associada ao perfil se houver correspondência, ou "No match" se não houver correspondência.</li>
</ul>

Destaques e Aprendizados: <br>
<ol>
  <li>Utilização de estruturas de dados como dicionários e listas para manipulação de informações</li>
  <li>Trabalho com entrada e saída de dados, leitura de arquivos CSV e de texto</li>
  <li>Implementação de algoritmo para encontrar a correspondência mais longa de sequências (STRs) em uma cadeia de DNA</li>
  <li>Uso de lógica de programação para comparação de perfis de DNA e identificação de correspondências</li>
  <li>Manuseio de argumentos de linha de comando para tornar o script interativo</li>
</ol>


Datas Importantes: 
<ul>
  <li>Início: 21/02/2024</li>
  <li>Fim: 29/02/2024</li>
</ul>
