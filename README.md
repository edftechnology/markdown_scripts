<!-- LOGOTIPO DO PROJETO -->
<div style="display: flex; justify-content: center;">
   <a href="https://github.com/edendenis/audithas">
     <img src="docs/figures/ita_logo.png" alt="Logo" width="200" height="100">
   </a>
</div>

<h3 align="center">Audithas</h3>

<div style="display: flex; justify-content: center;">
  <a href="https://zenodo.org/doi/10.5281/zenodo.10668919">
    <img src="https://zenodo.org/badge/758237447.svg" alt="DOI">
  </a>
</div>

<p align="center">
 A aplicação Audithas gera o resumo estatístico das variáveis de um
 banco de dados, incluindo contagens, percentuais, medidas de tendência e dispersão, valores extremos e
 uso de memória.
 <br />
 <a href="https://github.com/edendenis/audithas"><strong>Explore os documentos »</strong></a>
 <br />
 <br />
 <a href="https://github.com/edendenis/audithas">Ver demonstração</a>
 ·
 <a href="https://github.com/edendenis/audithas">Relatar bug</a>
 ·
 <a href="https://github.com/edendenis/audithas">Solicitar recurso</a>
</p>


## Resumo

A aplicação Audithas gera o resumo estatístico das variáveis de um
banco de dados, apresentando contagens, percentuais, medidas descritivas, valores extremos e uso de
memória.

## _Abstract_

_The Audithas application generates the statistical summary of dataset variables,
providing counts, percentages, descriptive measures, extreme values, and memory usage._


<!-- COMEÇANDO -->
### Começando

Este é um exemplo de como você pode dar instruções sobre como configurar seu projeto localmente.
Para obter uma cópia local instalada e funcionando, siga estas etapas simples de exemplo.

### Pré-requisitos

Este é um exemplo de como listar os itens necessários para usar o software e como instalá-los.

* [![Python 3.8](https://img.shields.io/badge/Python%203.8-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)

* [![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=flat-square&logo=anaconda&logoColor=white)](https://www.anaconda.com/)

* [![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)

* [![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/) ou qualquer IDE compatível (`PyCharm`, `Spyder`, `IDLE`, `Jupyter Notebook` etc.)

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


## Guia de instalação

### Instalar o Git

Verifique se você tem o Git instalado no seu computador. Se não tiver, você pode baixá-lo e instalá-lo a partir do site oficial do Git: https://git-scm.com/downloads

Abra o Git Bash. Você pode fazer isso clicando com o botão direito do mouse em qualquer diretório e selecionando a opção "Git Bash Here" no menu de contexto.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

## Guia de instalação

### Instalar o Git

Verifique se você tem o Git instalado no seu computador. Se não tiver, você pode baixá-lo e instalá-lo a partir do site oficial do Git: https://git-scm.com/downloads

Abra o Git Bash. Você pode fazer isso clicando com o botão direito do mouse em qualquer diretório e selecionando a opção "Git Bash Here" no menu de contexto.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

#### `Windows` [2]

Para gerar uma chave SSH no Windows para uso no GitLab, você pode seguir as etapas abaixo:

1. Verifique se você tem o Git instalado no seu computador. Se não tiver, você pode baixá-lo e instalá-lo a partir do site oficial do Git: https://git-scm.com/downloads

2. Abra o Git Bash. Você pode fazer isso clicando com o botão direito do mouse em qualquer diretório e selecionando a opção "Git Bash Here" no menu de contexto.

3. No Git Bash, digite o seguinte comando para gerar uma nova chave SSH `ssh-keygen -t rsa -C "seu_email@exemplo.com"` (`@gitlab.com`)

Certifique-se de substituir `seu_email@exemplo.com` pelo seu endereço de e-mail associado à sua conta do GitLab. Você pode deixar a senha em branco pressionando Enter duas vezes.

4. Será solicitado que você forneça um local para salvar a chave. Você pode simplesmente pressionar Enter para aceitar o local padrão (geralmente `C:\Usuários\SeuNome.ssh\id_rsa`).

5. O comando irá gerar a chave SSH pública e privada. Por padrão, a chave pública será salva como `id_rsa.pub`.

6. Agora, você precisa adicionar a chave SSH pública à sua conta do GitLab. Abra o GitLab no seu navegador e faça login na sua conta.

7. No canto superior direito da página, clique na sua foto de perfil e vá para `Settings` (Configurações) no menu suspenso.

8. No menu lateral esquerdo, clique em `SSH Keys` (Chaves SSH).

9. No campo 'Key', abra o arquivo `id_rsa.pub` (ou qualquer nome que você tenha dado à sua chave pública) que você gerou anteriormente. Copie todo o conteúdo do arquivo e cole no campo "Key" no GitLab.

10. Dê um nome para a chave, por exemplo, `Meu Computador` e clique em `Add Key` (Adicionar chave).

Agora você gerou e adicionou com sucesso uma chave SSH para uso no GitLab. Você poderá usar essa chave para autenticar suas operações do GitLab usando o Git no Windows.

Depois de copiar a chave pública, você poderá fazer login no servidor remoto sem precisar digitar a senha toda vez, desde que a chave privada esteja presente no sistema local e a frase secreta (se fornecida) esteja correta.

Lembre-se de proteger sua chave privada e evitar compartilhá-la com outras pessoas. É recomendável usar autenticação por chave SSH em vez de senhas, pois oferece uma camada adicional de segurança.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

### Atualizar pacotes `pip` e `setuptools` [3]

É recomendado que sejam atualizado os pacotes, como segue:

1. **Verificar a versão do `pip`:** Verifique se você está usando uma versão atualizada do `pip`. Execute o seguinte comando para atualizá-lo, caso necessário: `pip install --upgrade pip`

2. **Verificar a versão do `setuptools`:** Verifique se você possui a versão mais recente do pacote `setuptools` instalada. Execute o seguinte comando para atualizá-lo, se necessário:`pip install --upgrade setuptools`

3. **Verificar a versão do `wheel`:** O erro menciona que a opção `bdist_wheel` é inválida. Isso pode acontecer se o pacote `wheel` estiver desatualizado. Execute o seguinte comando para atualizar o pacote `wheel` com o comando: `pip install --upgrade wheel`

4. É recomendado reiniciar o Sistema Operacional (SO).

### Clonar o repositório do Git e instalar o pacote `proplib`

#### `Linux`

1. **Clone o repositório:**

  - **Pelo terminal:** `git clone git@github.com:edendenis/audithas.git`

  - **(Ou)** Fazer o _download_ do repositório `.zip` pela página web do GitHub, botão ao lado do botão azul `clone` à direita

  <p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

#### `Windows`

1. **Clone o repositório:**

  - **Pelo terminal:** `git clone git@github.com:edendenis/audithas.git`

  - (Ou) Fazer o _download_ do repositório `.zip` pela página web do GitHub, botão ao lado do botão azul `clone` à direita

  <p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

## Como executar a aplicação

### Executar a partir do `Terminal Emulator`

1. Abrir o `Terminal Emulator` e executar:

    -  Para o caso de planilhas `.xlsx`, por exemplo, para o arquivo `inputs/edb_emissions_databank_draft_v29B__web_.xlsx` execute:

        ```bash
        python3 main_audithas.py \
        --apply_predefined_conditions 0 \
        --uploaded_full_path inputs/edb_emissions_databank_draft_v29B__web_.xlsx \
        --output_format .xslx
        ```

    - Para o caso de texto separado por vĩrgula `.csv`, por exemplo, para o arquivo `inputs/edb_emissions_databank_draft_v29B__web_.xlsx` execute:

        ```bash
        python main_audithas.py \                                 
            --apply_predefined_conditions 0 \
            --uploaded_full_path inputs/edb_emissions_databank_draft_v29B__web_.xlsx \
            --output_format .xslx \
            --column_separator ";"
        ```

5. Os resultados, ou seja, dados de saída (_outputs_), serão salvos na subpasta `outputs/` que está dentro do projeto.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


### Executar a partir da `Guide User Interface (GUI)`

1. Abrir o `Terminal Emulator` e executar:

    ```bash
    python3 scripts/main_nicegui.py
    ```

## Mostrar ajuda

1. Você pode verificar os parâmetros aceitos pelo _script_ `main_audithas.py` executando o seguinte comando no `Terminal Emulator`:

    ```bash
    python3 main_audithas.py --help
    ```

    Ou, se o _script_ estiver em outro diretório, use o caminho absoluto:

    ```bash
    python3 /caminho/para/main_audithas.py --help
    ```

    Isso irá exibir a documentação dos argumentos disponíveis, incluindo seus tipos e descrições, caso tenham sido definidos com argparse.

### Exemplo de Saída Esperada

1. Se `main_audithas.py` usa `argparse`, a saída será algo como:

    ```bash
    usage: main_audithas.py [-h] [--apply_predefined_conditions APPLY_PREDEFINED_CONDITIONS]
                            --uploaded_full_path UPLOADED_FULL_PATH
                            [--output_format OUTPUT_FORMAT]
                            [--column_separator COLUMN_SEPARATOR]

    Run main_audithas analysis with user parameters.

    optional arguments:
      -h, --help            show this help message and exit
      --apply_predefined_conditions APPLY_PREDEFINED_CONDITIONS
                            Apply predefined conditions (1 = Yes, 0 = No)
      --uploaded_full_path UPLOADED_FULL_PATH
                            Path to the uploaded CSV file
      --output_format OUTPUT_FORMAT
                            Output format (.csv or .xlsx)
      --column_separator COLUMN_SEPARATOR
                            Column separator for CSV files
    ```

    Se o _script_ **NÃO** tiver `argparse` configurado, pode ser necessário abrir o código para inspecionar manualmente os argumentos aceitos.


## What the app does

This application creates an Excel workbook with the statistical summary of the variables in a database.

The statistical summary contains the following information:

- **Property number**: sequential property number contained in the database;

- **Property name**: name of the variable;

- **Variable data type**: data type of the variable recognized by Python;

- **Count**: count of existing values;

- **Count of values that start with a space**: count of values that start with an empty space;

- **Count of values that end with a space**: count of values that end with an empty space;

- **Number of unique values**: total number of unique values;

- **Percentage of unique values**: percentage of unique values;

- **Number of missing values**: total number of missing (empty) values;

- **Percentage of missing values**: percentage of missing (empty) values;

- **Count of infinite values**: total number of infinite values;

- **Percentage of infinite values**: percentage of infinite values;

- **Minimum**: minimum property value;

- **Average**: average property value;

- **Maximum**: maximum property value;

- **Range**: absolute difference between minimum and maximum;

- **Sample standard deviation**: standard deviation of the sample;

- **Population standard deviation**: standard deviation of the population;

- **Sample variance**: sample variance;

- **Population variance**: population variance;

- **Absolute frequency of mode**: absolute frequency of the mode;

- **Mode**: mode;

- **Kurtosis**: Fisher's kurtosis, normalized by N-1 (0 represents normal, <0 flat, >0 elongated);

- **Skewness**: skewness normalized by N-1;

- **Standard error**: standard error normalized by N-1;

- **Maximum percentile value P_25%**: 25th percentile (1st quartile);

- **Maximum percentile value P_50%**: 50th percentile (2nd quartile);

- **Maximum percentile value P_75%**: 75th percentile (3rd quartile);

- **Maximum percentile value P_1%**: 1st percentile;

- **Count of values lower than or equal to P_1%**: count of values lower than or equal to the 1st percentile;

- **Percentage of values lower than or equal to P_1%**: percentage of count P_1%;

- **Minimum percentile value P_99%**: 99th percentile;

- **Count of values greater than or equal to P_99%**: count of values greater than or equal to the 99th percentile;

- **Percentage of values greater than or equal to P_99%**: percentage of count P_99%;

- **Memory usage [KiB]**: memory usage per property in kibibytes.

    - **Note on memory usage**: Float64 and Int64 variables allocate the same space in memory: 64 bits (i.e., 8 bytes). 
      The range of allowed values is what changes. See: `Memory usage [KiB] * 1024 / 8 = number of rows`.
 -->


## What the app shows as output(s)

# Relatório de Análise de Dados

## 1. Introdução

- [x] Objetivo da análise de dados: disponibilizar, via NiceGUI, um fluxo rápido de exploração e validação do conjunto de dados (pré-visualização, estatísticas descritivas, tipos, qualidade, outliers e gráficos essenciais), subsidiando decisões e a geração de saídas automatizadas pelo Audithas.

- [x] Descrição do conjunto de dados analisado (origem, tamanho, formato).

- [x] Metodologia utilizada para a análise.

## 2. Estatísticas Gerais do Conjunto de Dados

- [x] Número total de variáveis (colunas).

- [x] Número total de registros (linhas).

- [x] Tipos de dados por variável (`int`, `float`, `object`, `category`).

- [x] Resumo da ocupação de memória.

## 3. Qualidade dos Dados

- [x] Valores faltantes (*missing values*): contagem e percentual por variável.

- [x] Valores únicos por variável (importante para identificar categóricas).

- [x] Distribuição de valores nulos ou infinitos.

- [x] Detecção de valores com espaços em branco no início e/ou no final.

## 4. Estatísticas Descritivas das Variáveis Numéricas

- [x] Contagem de valores válidos.

- [x] Média, mediana, moda.

- [x] Desvio padrão, variância (populacional e amostral).

- [x] Valor mínimo e máximo.

- [x] Amplitude (diferença entre mínimo e máximo).

- [x] Quartis (P25, P50, P75, P99).

- [x] Assimetria (*Skewness*) e Curtose.

## 5. Análise de Outliers

- [x] Definição de outliers (por exemplo, valores fora de 1.5x o IQR).

- [x] Identificação das variáveis com maior presença de outliers.

## 6. Correlações Entre Variáveis

- Matriz de correlação (*Pearson, Spearman* ou *Kendall*).

- Identificação de variáveis altamente correlacionadas (coeficiente acima de 0.7).

## 7. Estatísticas de Variáveis Categóricas

- Contagem de ocorrências de cada categoria.

- Percentual de distribuição de cada categoria.

## 8. Análise de Tendências Temporais (se aplicável)

- [x] Distribuição dos dados ao longo do tempo (se houver timestamps).

- [x] Identificação de padrões sazonais.

## 9. Conclusões e Próximos Passos

- Resumo dos principais insights obtidos.

- Possíveis transformações ou tratamentos sugeridos para melhorar a qualidade dos dados.

- Próximos passos para análises futuras.



## 📊 Gráficos Essenciais no Relatório

- [x] **Histogramas** - Distribuição de variáveis numéricas.

- [x] **Boxplots** - Identificação de outliers.

- **Heatmap de Correlação** - Análise de relações entre variáveis numéricas.

- [x] **Gráfico de Dispersão** - Relação entre duas variáveis.

- [x] **Gráficos de Barras** - Distribuição de variáveis categóricas.

- [x] **Linha do Tempo** - Se houver dados temporais.


# Correlsp


## 1. Função da Aplicação:

Esta aplicação retorna os valores das correlações de:
    
- Karl Pearson e seus respectivos p-values;

- Charles Spearman  (monotocidade) e seus respectivos p-values;

- Maurice Kendall Para Dados Ordinais e seus respectivos p-values;

- Maurice Kendall Para Dados Ponderados e seus respectivos p-values.

### 1.1 Entrada(s):

&emsp;&emsp;1. Arquivo `.csv`, `.dsv`, `.txt` ou planilha (`.xls`, `.xlsx` ou `.xlsm`;

### 1.2 Saída(s):
    
&emsp;&emsp;1. À definir.

## 2. Observação(ões)

1. Recomenda-se utilizar barra dupla no endereço do arquivo para evitar erro na leitura (ver referência [27]). Arquivos direto do fileshare, usar barra invertida;

2. Caminho do arquivo NÃO deve conter caracteres especiais.

# 3. Futura(s) Melhoria(s)

- Ainda **NÃO** há futura(s) melhoria(s).

## 5. Cálculo(s)

### 5.1 Coeficiente de Correlação de Karl Pearson

<div align="center">
  <img src="docs/figures/karl_pearson.png" alt="Karl Pearson" />
  <p><strong>Figura 1</strong> – Karl Pearson (1857–1936) [37].</p>
</div>



#### 5.1.1 Descrição`

&emsp;&emsp;O Coeficiente de Correlação de Karl Pearson (1857-1936), Coeficiente de Correlação Produto-Momento ou Densidade $ \rho $ (letra grega) de Pearson, obviamente retorna o grau de correlação entre dois conjuntos de dados ($X$, $Y$). Em outras palavras, o coeficiente retorna a direção da tendência (crescente ou decrescente) de um conjunto em relação ao outro e vice-versa.

&emsp;&emsp;Este coeficiente pode assumir valores entre $-1$ e $1$, inclusive algum dos extremos. [17]

### 5.1.2 Interpretação do Coeficiente da Correlação de Karl Pearson

<div align="center">

|VALOR DO COEFICIENTE (\begin{align}\rho\end{align}) DE (INCLUSIVE)|VALOR DO COEFICIENTE (\begin{align}\rho\end{align}) DE (EXCLUSIVE)|INTERPRETAÇÃO DO VALOR DO COEFICIENTE|
|:-:|:-:|:-|
|$-1$|$0$|Significa que o primeiro conjunto de dados co-varia inversamente proporcional com o segundo. Se o primeiro conjunto cresce o outro decresce; Se o primeiro conjunto decresce o outro cresce| 
|$0$|-|Significa que o primeiro conjunto de dados NÃO co-varia linearmente com o segundo. Portanto, pode existir covariância NÃO-linear|
|$1$|$0$|Significa que o primeiro conjunto de dados co-varia diretamente proporcional com o segundo. Se o primeiro conjunto cresce o outro também cresce; Se o primeiro conjunto decresce o outro também decresce|

</div>

### 5.1.3 Cálculo(s) do Coeficiente de Correlação de Karl Pearson

\begin{align}
    \rho & = \dfrac{cov(X, Y)}{\sqrt{var(X)var(Y)}}
\end{align}

Sendo:

\begin{cases}
    \rho & \text{: Coeficiente de Correlação de Karl Pearson} \\[0.3cm]
    cov(X, Y) & \text{: covariância entre os conjuntos $X$ e $Y$} \\[0.3cm]
    var(X) & \text{: variância do conjunto $X$} \\[0.3cm]
    var(Y) & \text{: variância do conjunto $Y$}
\end{cases}



#### 5.1.4 Gráfico(s) do Coeficiente Correlação de Karl Pearson

### 5.2 $p$-value Para Mensurar Validade de Coeficientes de Correlação

&emsp;&emsp;Perceber que, os conceitos sobre Hipótese Nula e Alternativa, bem como o a Descrição do $p$-value são aplicáveis e válidas para todas as correlações. Logo, estes, serão comentado uma única vez salvo especificidades.

#### 5.2.1 Hipótese Nula e Alternativa

&emsp;&emsp;Em testes de hipóteses, deve-se assumir o pressuposto de que dois conjuntos de dados NÃO tem correlação entre si. Se esta hipótese, de fato, NÃO fo satisfeita, então, a configuração é conhecida como Hipótese Nula ($H_{0}$); Senão, a Hipótese Nula é rejeitada e passa a ser chamada de Hipótese Alternativa ($H_{1}$). [19]

##### 5.2.2 Descrição do $p$-value

&emsp;&emsp;O $p$-value, nível descritivo ou probabilidade de significância, retorna a probabilidade de uma correlação seja devido ao acaso, portanto, aparente. Este coeficiente pode assumir valores entre $0$ e $1$, inclusive algum dos extremos. Um valor $p$-value igual ou próximo de $1$ (um) NÃO necessariamente indica que uma correlação foi obtida a partir do acaso e também NÃO pode ser afirmada que a Hipótese Nula foi aceita. Um valor $p$-value igual ou próximo de $0$ (zero) indica que é pouco provavél que uma correlação foi obtida a partir do acaso e também pode ser afirmar que a probabilidade da Hipótese Nula ser rejeitada é alta. Portanto, neste último caso, deve-se assumir que a Hipótese Alternativo ($H_{1}$) é válida, ou seja, que os conjuntos de dados possuem correlação. [19] 

#### 5.2.3 Interpretação do Valor de p-value [19]

<div align="center">

|VALOR DO COEFICIENTE (p-value) DE (INCLUSIVE)|VALOR DO COEFICIENTE (p-value) DE (EXCLUSIVE)|EVIDÊNCIAS PARA REJEITAR A HIPÓTESE NULA $ H_{0} $|PLANO DE AÇÃO|
|:-:|:-:|:-|:-|
|$0$|$0,01$|Muito forte|Rejeitar Hipótese Nula, assumir Hipótese Alternativa|
|$0,01$|$0,05$|Forte|Rejeitar Hipótese Nula, assumir Hipótese Alternativa|
|$0,05$|$0,10$|Fraca|NÃO rejeitar Hipótese Nula, assumir Hipótese Nula|
|$0,10$|$1,00$|Muito fraca|NÃO rejeitar Hipótese Nula, assumir Hipótese Nula|

</div>

#### 5.2.4 Equívocos Comuns Sobre o $p$-value [20]

1. O $p$-value **NÃO** é a probabilidade de a Hipótese Nula de uma análise ser verdadeira;

2. O $p$-value **NÃO** é a probabilidade de um resultado ter sido gerado a partir do acaso;

3. A intensidade do $p$-value **NÃO** indica o tamanho ou a importância de um fenômeno observado.

### 5.3 Coeficiente de Correlação de Charles Spearman (Monotocidade)

<p align="center">
  <img src="docs/figures/charles_spearman.png" width="300"/><br>
  <em>Charles Spearman [21]</em>
</p>


#### 5.3.1 Descrição do Coeficiente de Correlação de Charles Spearman

&emsp;&emsp;O Coeficiente de Correlação de Charles Spearman (1863-1945, psicólogo e estatístico) ou Densidade $ \rho $ (letra grega) de Spearman, retorna o grau de intensidade do poder preditivo de uma função monótona - que preserva ou inverte a relação de ordem. Se a função preserva a relação, é chamada de crescente, senão, decrescente - da correlação entre dois conjuntos de dados (x, y). Em outras palavras, o coeficiente retorna a direção da tendência (crescente ou decrescente) de um conjunto em relação ao outro e vice-versa.

&emsp;&emsp;O Coeficiente de Correlação de Spearman entre dois conjuntos de dados é igual ao de Karl Pearson. Entretanto, enquanto o Coeficiente de Pearson analisa correlações lineares, o de Spearman analisa relações monótonas descritas anteriormente, monotocidade, sejam estas lineares ou NÃO-lineares. 

&emsp;&emsp;Trata-se de um coeficiente adequado tanto para conjunto de dados contínuos ou discretos, isso inclui, dados ordinais. Este coeficiente, assim como o de Kendall podem ser considerados como casos especiais de coeficiente de correlação geral.

&emsp;&emsp;Este coeficiente pode assumir valores entre -1 e 1, inclusive algum dos extremos. [18]

### 5.3.2 Interpretação do Coeficiente da Correlação de Charles Spearman

|VALOR DO COEFICIENTE $ \begin{align}\rho = r_{s}\end{align} $|DESCRIÇÃO|TENDÊNCIA DA VARIÁVEL INDEPENDENTE $ \begin{align}X\end{align} $|TENDÊNCIA DA VARIÁVEL DEPENDENTE $ \begin{align}Y\end{align} $|
|:-:|:-:|:-:|:-|
|$ \begin{align}\rho = r_{s} > 0\end{align} $ (Positivo)|Crescente|Crescente|$ Y $ cresce a medida que $ X $ cresce|
|$ \begin{align}\rho = r_{s} = 0\end{align} $ (Nulo)|Crescente|-|NÃO há indicativo do comportamento de $ Y $ a medida que $ X $ cresce|
|$ \begin{align}\rho = r_{s} < 0\end{align} $ (Negativo)|Crescente|Decrescente|$ Y $ decresce a medida que $ X $ cresce|

### 5.2.3 Interpretação Adicional do Coeficiente da Correlação de Charles Spearman [11]

<div align="center">

|VALOR DO COEFICIENTE ($ \rho = r_{s} $) DE (INCLUSIVE)|VALOR DO COEFICIENTE ($ \rho = r_{s} $) DE (EXCLUSIVE)|INTERPRETAÇÃO DO VALOR DO COEFICIENTE ($ \rho = r_{s} $)|
|:-:|:-:|:-|
|-1,00|-0,90|Correlação muito forte|
|-0,90|-0,70|Correlação forte|
|-0,70|-0,40|Correlação moderada|
|-0,40|-0,20|Correlação fraca|
|-0,20|0,00|Correlação muito fraca|
|0,00|-|Não há correlação|
|0,20|0,00|Correlação muito fraca|
|0,40|0,20|Correlação fraca|
|0,70|0,40|Correlação moderada|
|0,90|0,70|Correlação forte|
|1,00|0,90|Correlação muito forte|

</div>

### 5.3.4 Cálculo(s) do Coeficiente de Correlação de Charles Spearman

\begin{align}
    \rho = r_{s} = \dfrac{cov(rg_{X}, rg_{Y})}{\sigma(rg_{X}) \, \sigma(rg_{Y})}
\end{align}

&emsp;&emsp;Sendo:

\begin{cases}
    \rho = r_{s} & \text{: Coeficiente de Correlação de Charles Spearman} \\[6pt]
    cov(rg_{X}, rg_{Y}) & \text{: covariância entre os postos (dados organizados) de $X$ e $Y$} \\[6pt]
    \sigma(rg_{X}) & \text{: desvio-padrão dos postos (dados organizados) de $X$} \\[6pt]
    \sigma(rg_{Y}) & \text{: desvio-padrão dos postos (dados organizados) de $Y$}
\end{cases}


### 5.4 Coeficiente de Correlação de Maurice Kendall Para Dados Ordinais

<div align="center">
  <img src="docs/figures/maurice_kendall.png" alt="Maurice Kendall" />
  <p><strong>Figura 3</strong> – Maurice Kendall (1907-1983) [16].</p>
</div>


#### 5.4.1 Descrição do Coeficiente de Correlação de Maurice Kendall Para Dados Ordinais

&emsp;&emsp;O Coeficiente de Correlação (Tau, devido à letra grega) de Maurice Kendall (1938) ou apenas Coeficiente de Kendall, assim como o Coeficiente de Correlação de Spearman, analisa a correlação de postos entre dois conjuntos de dados. Sendo assim, avalia a semelhança entre as ordens dos conjuntos de dados agrupados por cada uma das quantidades. 

&emsp;&emsp;Se a semelhança da classificação entre dois conjuntos de dados for alta, o Coeficiente de Correlação de Kendall entre é igual ou próximo de $1$ (um). Se a semelhança da classificação entre dois conjuntos de dados for baixa, o Coeficiente de Correlação de Kendall entre é igual ou próximo de $-1$ (menos um)  

&emsp;&emsp;Trata-se de um coeficiente adequado tanto para conjunto de dados contínuos ou discretos, isso inclui, dados ordinais. Este coeficiente, assim como o de Kendall podem ser considerados como casos especiais de coeficiente de correlação geral.

&emsp;&emsp;Este coeficiente pode assumir valores entre $-1$ e $1$, inclusive algum dos extremos. [9]

### 5.4.2 Interpretação do Coeficiente da Correlação de Maurice Kendall Para Dados Ordinais

<div align="center">

|VALOR DO COEFICIENTE ($\tau$) DE (INCLUSIVE)|VALOR DO COEFICIENTE ($\tau$) DE (EXCLUSIVE)|TIPO|INTERPRETAÇÃO DO VALOR DO COEFICIENTE|
|:-:|:-:|:-:|:-|
|$-1$|$0$|Discordante|Quanto mais próximo de -1 (menos um), mais discordantes serão os agrupamentos dos conjuntos de dados| 
|$0$|-|Independente|Um agrupamento é independente do outro|
|$1$|$0$|Concordante|Quanto mais próximo de 1 (um), mais concordantes serão os agrupamentos dos conjuntos de dados|

</div>

### 5.4.3 Cálculo(s) do Coeficiente de Maurice Kendall Para Dados Ordinais

\begin{align}
    \tau_{A} = \dfrac{n_{c} - n_{d}}{n_{0}}
\end{align}

&emsp;&emsp;Sendo:

\begin{cases}
    \tau_{A} & \text{: Coeficiente de Correlação de Maurice Kendall} \\
    n_{c} & \text{: número total de pares concordantes} \\
    n_{d} & \text{: número total de pares discordantes} \\
    n_{0} = \dfrac{n(n-1)}{2} & \text{: número total de pares possíveis}
\end{cases}


### 5.5 Coeficiente de Correlação de Maurice Kendall Para Dados Ponderados

#### 5.5.1 Descrição do Coeficiente de Correlação de Maurice Kendall Para Dados Ponderados

&emsp;&emsp;O Coeficiente de Correlação (Tau, devido à letra grega) de Maurice Kendall (1938) ou apenas Coeficiente de Kendall, assim como o Coeficiente de Correlação de Spearman, analisa a correlação de postos entre dois conjuntos de dados. Sendo assim, avalia a semelhança entre as ordens dos conjuntos de dados agrupados por cada uma das quantidades. 

&emsp;&emsp;Se a semelhança da classificação entre dois conjuntos de dados for alta, o Coeficiente de Correlação de Kendall entre é igual ou próximo de 1 (um). Se a semelhança da classificação entre dois conjuntos de dados for baixa, o Coeficiente de Correlação de Kendall entre é igual ou próximo de -1 (menos um)  

&emsp;&emsp;Trata-se de um coeficiente adequado tanto para conjunto de dados contínuos ou discretos, isso inclui, dados ordinais. Este coeficiente, assim como o de Kendall podem ser considerados como casos especiais de coeficiente de correlação geral.
        
&emsp;&emsp;Este coeficiente pode assumir valores entre -1 e 1, inclusive algum dos extremos. [9]

### 5.5.2 Interpretação do Coeficiente da Correlação de Maurice Kendall Para Dados Ponderados

<div align="center">

|VALOR DO COEFICIENTE ($\tau$) DE (INCLUSIVE)|VALOR DO COEFICIENTE ($\tau$) DE (EXCLUSIVE)|TIPO|INTERPRETAÇÃO DO VALOR DO COEFICIENTE|
|:-:|:-:|:-:|:-|
|$-1$|$0$|Discordante|Quanto mais próximo de -1 (menos um), mais discordantes serão os agrupamentos dos conjuntos de dados| 
|$0$|-|Independente|Um agrupamento é independente do outro|
|$1$|$0$|Concordante|Quanto mais próximo de 1 (um), mais concordantes serão os agrupamentos dos conjuntos de dados|

</div>


### 5.5.3 Cálculo(s) do Coeficiente de Maurice Kendall Para Dados Ponderados

\begin{align}
\tau_{B} = \dfrac{n_{c} - n_{d}}{\sqrt{(n_{0}-n_{1})(n_{0}-n_{2})}}
\end{align}

Sendo:


\begin{cases}
    \tau_{B} & : \text{Coeficiente de Correlação de Maurice Kendall} \\[6pt]
    n_{c} & : \text{número total de pares concordantes} \\[6pt]
    n_{d} & : \text{número total de pares discordantes} \\[6pt]
    n_{0} & = \dfrac{n(n-1)}{2} \; : \text{número total de pares possíveis} \\[6pt]
    n_{1} & = \sum_{i} \dfrac{t_{i}(t_{i}-1)}{2}, \quad t_{i}: \text{valores empatados no $i$-ésimo grupo do 1º conjunto} \\[6pt]
    n_{2} & = \sum_{j} \dfrac{u_{j}(u_{j}-1)}{2}, \quad u_{j}: \text{valores empatados no $j$-ésimo grupo do 2º conjunto}
\end{cases}



<!-- LICENÇA -->
## Licença

Distribuído sob a licença `MIT`. Consulte `LICENSE.txt` para obter mais informações.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- ROTEIRO -->
## Roteiro

- [x] Adicionar registro de alterações

- [x] Adicionar links de volta ao topo

- [x] Adicionar modelos adicionais com exemplos

- [x] Suporte multilíngue
     
     - [x] Espanhol
     
     - [x] Inglês
     
     - [x] Português
     
     - [x] Português brasileiro 

Consulte os [problemas abertos](https://github.com/edendenis/audithas/issues) para obter uma lista completa dos recursos propostos (e problemas conhecidos).

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


<!-- CONTRIBUIÇÔES -->
## Contribuições

As contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

Se você tiver uma sugestão que possa melhorar isso, bifurque o repositório e crie uma solicitação `pull`. Você também pode simplesmente abrir um problema com a tag “aprimoramento”.
Não se esqueça de dar uma estrela ao projeto! Obrigado novamente!

1. Bifurque o projeto

2. Crie sua ramificação de recursos (`git checkout -b feature/AmazingFeature`)

3. Confirme suas alterações (`git commit -m 'Add some AmazingFeature'`)

4. Envie para a filial (`git push origin feature/AmazingFeature`)

5. Abra uma solicitação `pull`

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Agradecimentos

* [Best README Template](https://github.com/othneildrew/Best-README-Template?tab=readme-ov-file)

* [Choose an Open Source License](https://choosealicense.com)

* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)

* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)

* [Malven's Grid Cheatsheet](https://grid.malven.co/)

* [Img Shields](https://shields.io)

* [GitHub Pages](https://pages.github.com)

* [Font Awesome](https://fontawesome.com)

* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


## Referências

[1] NUMPY. NumPy. Disponível em: <https://numpy.org/doc/>. Acesso em: 8 jun. 2024.

[2] PANDAS DEVELOPMENT TEAM. pandas documentation. Disponível em: <https://pandas.pydata.org/docs/>. Acesso em: 8 jun. 2024.

[3] SCIPY COMMUNITY. SciPy documentation. Disponível em: <https://docs.scipy.org/doc/scipy/reference/>. Acesso em: 8 jun. 2024.

[4] PYTHON SOFTWARE FOUNDATION. The Python Language Reference. Release 3.12. Disponível em: <https://docs.python.org/3/reference/>. Acesso em: 8 jun. 2024.

[5] MATPLOTLIB DEVELOPMENT TEAM. Matplotlib. Disponível em: <https://matplotlib.org/stable/>. Acesso em: 8 jun. 2024.

[6] WASKOM, Michael L. et al. Seaborn. Disponível em: <https://seaborn.pydata.org/>. Acesso em: 8 jun. 2024.

[7] WIKIPEDIA. Pearson correlation coefficient. Disponível em: <https://en.wikipedia.org/wiki/Pearson_correlation_coefficient>. Acesso em: 8 jun. 2024.

[8] WIKIPEDIA. Spearman's rank correlation coefficient. Disponível em: <https://en.wikipedia.org/wiki/Spearman%27s_rank_correlation_coefficient>. Acesso em: 8 jun. 2024.

[9] WIKIPEDIA. Kendall rank correlation coefficient. Disponível em: <https://en.wikipedia.org/wiki/Kendall_rank_correlation_coefficient>. Acesso em: 8 jun. 2024.

[10] DRISCOLL, Eric. openpyxl. Disponível em: <https://openpyxl.readthedocs.io/en/stable/>. Acesso em: 8 jun. 2024.

[11] WIKIPEDIA. P-value. Disponível em: <https://en.wikipedia.org/wiki/P-value>. Acesso em: 8 jun. 2024.

[12] PYTHON SOFTWARE FOUNDATION. winsound — Sound-playing interface for Windows. Disponível em: <https://docs.python.org/3/library/winsound.html>. Acesso em: 8 jun. 2024.

[13] GOODMAN, Steven N. A Dirty Dozen: Twelve P-Value Misconceptions. Seminars in Hematology, v. 45, n. 3, p. 135-140, 2008.

[14] WIKIPEDIA. Karl Pearson. Disponível em: <https://en.wikipedia.org/wiki/Karl_Pearson>. Acesso em: 8 jun. 2024.

[15] WIKIPEDIA. Charles Spearman. Disponível em: <https://en.wikipedia.org/wiki/Charles_Spearman>. Acesso em: 8 jun. 2024.

[16] WIKIPEDIA. Maurice Kendall. Disponível em: <https://en.wikipedia.org/wiki/Maurice_Kendall>. Acesso em: 8 jun. 2024.

[17] PEARSON, K.. Mathematical contributions to the theory of evolution.—III. Regression, heredity, and panmixia. Philosophical Transactions of the Royal Society of London. Series A, v. 187, p. 253--318, 1896.

[18] SPEARMAN, C.. The proof and measurement of association between two things. The American Journal of Psychology, v. 15, n. 1, p. 72--101, 1904.

[19] FISHER, R. A.. Statistical Methods for Research Workers. Edinburgh: Oliver & Boyd, 1925.

[20] WASSERSTEIN, R. L.; LAZAR, N. A.. The ASA statement on p-values: context, process, and purpose. The American Statistician, v. 70, n. 2, p. 129--133, 2016.

[21] WIKIPEDIA. Charles Spearman. Disponível em: <https://en.wikipedia.org/wiki/Charles_Spearman>. Acesso em: 8 jun. 2024.

