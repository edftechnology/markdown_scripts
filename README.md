<!-- LOGOTIPO DO PROJETO -->
<div style="display: flex; justify-content: center;">
   <a href="https://github.com/SEU-USUARIO/SEU-PROJETO">
     <img src="docs/figures/gold_edf_technology_logo_transparent_background_and_gold_name.png" alt="Logo" width="200" height="100">
   </a>
</div>

<h3 align="center">NomeDoProjeto</h3>

<div style="display: flex; justify-content: center;">
  <a href="https://doi.org/SEU-DOI">
    <img src="https://zenodo.org/badge/SEU_BADGE.svg" alt="DOI">
  </a>
</div>

<p align="center">
 Uma descrição curta e genérica do projeto. Substitua por um resumo real quando usar este template.
 <br />
 <a href="https://github.com/SEU-USUARIO/SEU-PROJETO"><strong>Explore os documentos »</strong></a>
 <br />
 <br />
 <a href="https://github.com/SEU-USUARIO/SEU-PROJETO">Ver demonstração</a>
 ·
 <a href="https://github.com/SEU-USUARIO/SEU-PROJETO">Relatar bug</a>
 ·
 <a href="https://github.com/SEU-USUARIO/SEU-PROJETO">Solicitar recurso</a>
</p>




## Resumo

Resumo genérico do projeto. Explique o problema, o objetivo e o valor da solução em 2-4 linhas.

## _Abstract_

_Generic abstract in English. Summarize the purpose, scope, and outputs in 2-4 lines._



## Descrição

`<nome_da_aplicacao>`

Colocar a descrição da aplicação/subaplicação aqui.

<!-- COMEÇANDO -->
### Começando

Este template mostra como documentar a configuração local do projeto. Substitua pelos passos reais.



### Pré-requisitos

Lista genérica de ferramentas necessárias. Ajuste versões e remova o que não se aplica.

* [![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)

* [![Anaconda](https://img.shields.io/badge/Anaconda-4.x-44A833?style=flat-square&logo=anaconda&logoColor=white)](https://www.anaconda.com/)

* [![Git](https://img.shields.io/badge/Git-2.x-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)

* [![VS Code](https://img.shields.io/badge/VS%20Code-1.x-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/) ou qualquer IDE compatível

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>




## 1. Configurar/Instalar/Usar o repo `markdown_scripts` no repositório do seu projeto

Para configurar/instalar/usar o `markdown_scripts`, siga os passos abaixo:

1. Abrir o `Terminal Emulator`. Você pode fazer isso pressionando:

    ```bash
    Ctrl + Alt + T
    ```



2. Acessar a pasta do seu projeto:

```bash
cd <caminho_ate_o_projeto>
```

3. Adicionar o `markdown_scripts` como submodule:

```bash
git submodule add \
    git@github.com:edftechnology/markdown_scripts.git \
    subs/submodules/markdown_scripts
```

4. Inicializar submodules existentes (se aplicável):

```bash
git submodule update --init --recursive
```


## 2. (Opcional) Atualizar o `markdown_scripts`

Os comandos interativos do ecossistema agora podem verificar se o submodule
`subs/submodules/markdown_scripts` est\u00e1 atr\u00e1s do `origin/<branch>` antes de executar a fun\u00e7\u00e3o principal.

Quando houver uma vers\u00e3o mais nova e a sess\u00e3o for interativa (`TTY`), o usu\u00e1rio ver\u00e1 um prompt neste formato:

```bash
[markdown_scripts] A newer version is available. Would you like to update now? [y/N]
```

Pol\u00edtica adotada:

- Perguntar apenas em comandos interativos
- N\u00e3o perguntar em `scripts`, `CI` ou qualquer execu\u00e7\u00e3o sem `TTY`
- Tratar `Enter` como `no`
- Continuar normalmente se o usu\u00e1rio responder `n` ou apenas `Enter`
- Executar atualiza\u00e7\u00e3o com `fast-forward only` se o usu\u00e1rio responder `y`
- Reiniciar o pr\u00f3prio comando ap\u00f3s a atualiza\u00e7\u00e3o para executar j\u00e1 com a vers\u00e3o nova

O fluxo de atualiza\u00e7\u00e3o executa:

```bash
git -C subs/submodules/markdown_scripts fetch origin
git -C subs/submodules/markdown_scripts pull --ff-only
```

Sem `TTY`, o comportamento fica s\u00f3 no aviso e a execu\u00e7\u00e3o segue sem atualizar.

## 3. Observação

Este bloco é um template. Ajuste URLs, paths e comandos conforme o padrão do seu projeto.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


### Exemplo rápido para adicionar o template em outro projeto

```bash
git submodule add \
    git@github.com:edftechnology/markdown_scripts.git \
    subs/submodules/markdown_scripts
```


## Como executar a aplicação

### Executar a partir do `Terminal Emulator`

1. Exemplo genérico de execução:

```bash
python3 main.py --input caminho/para/arquivo --output caminho/para/saida
```

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>




### Executar a partir da `Graphical User Interface (GUI)`

1. Exemplo genérico de execução:

```bash
python3 scripts/app_gui.py
```



## Mostrar ajuda

1. Exemplo genérico de ajuda:

```bash
python3 main.py --help
```



### Exemplo de Saída Esperada

Exemplo genérico (substitua pelo help real do projeto):

```bash
usage: main.py [-h] --input INPUT [--output OUTPUT]
```



## O que o aplicativo faz?

Describe in English, at a high level, what the application does and the main outputs.

- Example capability 1
- Example capability 2
- Example capability 3




## 1. Função da Aplicação

Descrição genérica da função principal do módulo.

### 1.1 Entrada(s)

1. Formatos de arquivo suportados (ex.: `.csv`, `.xlsx`).

### 1.2 Saída(s)

1. Descrição das saídas esperadas.



## 2. Observação(ões)

1. Observações gerais e boas práticas.
2. Restrições conhecidas.



# 3. Futura(s) Melhoria(s)

- Lista de melhorias planejadas.



<!-- LICENÇA -->
## Licença

Distribuído sob a licença `MIT`. Consulte `LICENSE.txt` para obter mais informações.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>



<!-- ROTEIRO -->
## Roteiro

- [ ] Adicionar registro de alterações
- [ ] Adicionar links de volta ao topo
- [ ] Adicionar modelos adicionais com exemplos
- [ ] Suporte multilíngue

Consulte os problemas abertos para obter uma lista completa dos recursos propostos.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>




<!-- CONTRIBUIÇÔES -->
## Contribuições

Explique como contribuir (fork, branch, PR, issues).

1. Bifurque o projeto
2. Crie sua ramificação (`git checkout -b feature/NovaFuncionalidade`)
3. Confirme suas alterações (`git commit -m 'Describe change'`)
4. Envie para a filial (`git push origin feature/NovaFuncionalidade`)
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

[1] Fonte ou documentação relevante.
[2] Artigo, tutorial ou manual adicional.
[3] Outro link útil.

