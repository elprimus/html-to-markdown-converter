# htmlToMd

# HTML to Markdown Converter

Este é um simples programa em Python para converter arquivos HTML em arquivos Markdown.

## Funcionalidades

- Converte arquivos HTML em Markdown.
- Aceita caminhos de arquivos HTML como entrada.
- Permite especificar o caminho onde o arquivo Markdown resultante será salvo.
- Fornece uma mensagem de ajuda explicando como utilizar o programa.

## Como usar

Para usar este programa, siga as instruções abaixo:

1. Clone este repositório:

    ```bash
    git clone https://github.com/seu-usuario/html-to-markdown-converter.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd html-to-markdown-converter
    ```

3. Execute o programa Python fornecendo o caminho para o arquivo HTML e o caminho para o arquivo Markdown:

    ```bash
    python converter.py <path_do_arquivo_html> <path_para_escrever_o_arquivo_md>
    ```

    Por exemplo:

    ```bash
    python converter.py input.html output.md
    ```

    Isso converterá o arquivo HTML `input.html` em Markdown e o salvará como `output.md`.

## Requisitos

- Python 3.x
- Biblioteca html2text (instalável via pip)

    ```bash
    pip install html2text
    ```

## Contribuindo

Se você encontrar problemas ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue ou enviar uma pull request neste repositório.

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

