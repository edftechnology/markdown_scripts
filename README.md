# Como instalar/configurar/usar o `markdown scripts` no `Linux Ubuntu`

## Resumo

Guia direto para instalar o `markdown scripts` no seu projeto.

## _Abstract_

_A straightforward guide to installing `markdown scripts` in your project._


## Descrição

### `markdown scripts`

O `markdown scripts` é um repositório do `GitHub` para consolidar códigos genéricos em `markdown` para
serem utilizados em qualquer outro projeto. Ele também inclui um _script_ chamado `prepare_repo.sh`
que clona outros repos dentro do seu projeto com demais códigos genéricos em diversas linguagens e
arquivos que são convenientes existirem em projetos.


## Pré-requisitos

- `Git` instalado
- `SSH key` configurada no `GitHub`
- Acesso ao `GitHub` (repositório `edftechnology/markdown_scripts`)


## 1. Clonar o repo `markdown scripts` no repositório do seu projeto

Para clonar o `markdown scripts`, siga os passos abaixo:

1. Abrir o `Terminal Emulator`. Você pode fazer isso pressionando:

    ```bash
    Ctrl + Alt + T
    ```

2. Certifique-se de que seu sistema esteja limpo e atualizado.

    2.1 Limpar o `cache` do gerenciador de pacotes `apt`. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo `apt` e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando:
    ```bash
    sudo apt clean
    ```

    2.2 Remover pacotes `.deb` antigos ou duplicados do `cache` local. É útil para liberar espaço, pois remove apenas os pacotes que não podem mais ser baixados (ou seja, versões antigas de pacotes que foram atualizados). Digite o seguinte comando:
    ```bash
    sudo apt autoclean
    ```

    2.3 Remover pacotes que foram automaticamente instalados para satisfazer as dependências de outros pacotes e que não são mais necessários. Digite o seguinte comando:
    ```bash
    sudo apt autoremove -y
    ```

    2.4 Buscar as atualizações disponíveis para os pacotes que estão instalados em seu sistema. Digite o seguinte comando e pressione `Enter`:
    ```bash
    sudo apt update
    ```

    2.5 **Corrigir pacotes quebrados**: Isso atualizará a lista de pacotes disponíveis e tentará corrigir pacotes quebrados ou com dependências ausentes:
    ```bash
    sudo apt --fix-broken install
    ```

    2.6 Limpar o `cache` do gerenciador de pacotes `apt` novamente:
    ```bash
    sudo apt clean
    ```

    2.7 Para ver a lista de pacotes a serem atualizados, digite o seguinte comando e pressione `Enter`:
    ```bash
    sudo apt list --upgradable
    ```

    2.8 Realmente atualizar os pacotes instalados para as suas versões mais recentes, com base na última vez que você executou `sudo apt update`. Digite o seguinte comando e pressione `Enter`:
    ```bash
    sudo apt full-upgrade -y
    ```

3. Acessar a pasta do seu projeto:

    ```bash
    cd <caminho_ate_o_projeto>
    ```

4. Clonar o `markdown scripts`:

    ```bash
    git submodule add \
        git@github.com:edftechnology/markdown_scripts.git \
        subs/submodules/markdown_scripts
    ```


## 1.1 Código completo para configurar/instalar/usar

Para configurar/instalar/usar o `markdown scripts` no `Linux Ubuntu` sem precisar digitar linha por linha, você pode seguir estas etapas:

1. Abrir o `Terminal Emulator`. Você pode fazer isso pressionando:

    ```bash
    Ctrl + Alt + T
    ```

2. Digite o seguinte comando e pressione `Enter`:

    ```bash
    sudo apt clean
    sudo apt autoclean
    sudo apt autoremove -y
    sudo apt update
    sudo apt --fix-broken install
    sudo apt clean
    sudo apt list --upgradable
    sudo apt full-upgrade -y
    cd <caminho_ate_o_projeto>
    git submodule add git@github.com:edftechnology/markdown_scripts.git subs/submodules/markdown_scripts
    git submodule update --init --recursive
    bash subs/submodules/shell_scripts/scripts/prepare_repo.sh
    ```


## 2. Inicializar submodules existentes (se aplicável)

1. Se o seu repositório já tiver um `.gitmodules`, inicialize com:

    ```bash
    git submodule update --init --recursive
    ```


## 3. (Opcional) Executar o `prepare_repo.sh`

É conveniente executar o `scripts/prepare_repo.sh` depois de clonar o `markdown scripts`,
pois ele verifica se o seu repo está com todos os arquivos que é recomendado que um projeto
tenha, sem excluir ou sobrescrever os arquivos existentes. Para isso, na raiz do seu projeto,
execute o comando:

```bash
bash subs/submodules/shell_scripts/scripts/prepare_repo.sh
```

O script faz, de forma resumida:

- Garante/atualiza submodules essenciais
- Cria pastas padrão do projeto (docs, inputs, outputs, etc.)
- Cria `__init__.py` onde for apropriado


## Compatibilidade

- Testado em Linux Ubuntu (recomendado 20.04+).
- Deve funcionar em Debian e WSL, desde que o Git e o Bash estejam disponíveis.


## Licença

Este repositório inclui o arquivo `LICENSE.txt`.

## Contato e suporte

Para dúvidas ou problemas, abra uma issue no repositório do `GitHub`.


## Referências

[1] OPENAI. **Instalar o markdown scripts no linux ubuntu pelo terminal emulator**. Disponível em: <https://chatgpt.com/c/markdown-scripts>. ChatGPT. Acessado em: 02/04/2026.

