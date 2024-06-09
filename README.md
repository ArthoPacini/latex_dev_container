
# Container de Desenvolvimento LaTeX

<img height="250" src="https://raw.githubusercontent.com/qdm12/latexdevcontainer/master/title.svg?sanitize=true">

Este projeto simplifica o processo de desenvolvimento em LaTeX ao fornecer um container de desenvolvimento pronto para uso no Visual Studio Code. Ele permite que você escreva e compile documentos LaTeX sem a necessidade de instalar manualmente distribuições ou pacotes LaTeX em sua máquina. O container gera automaticamente um PDF cada vez que seu projeto é alterado.

### Pré-requisitos

Certifique-se de ter instalado:
- [Docker](https://www.docker.com/get-started) (Com o docker compose)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Extensão Remote - Containers para VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### Configuração

1. **Clonar o Repositório**
   ```bash
   git clone https://github.com/ArthoPacini/latex_dev_container.git
   cd latex_dev_container
   ```

2. **Abrir com o VSCode**
   - Abra o Visual Studio Code.
   - Espere alguns instantes, se o VSCode detectar o Dev Container, uma mensagem irá pedir para abrir no Container, caso isso não ocorrer siga o próximo passo.
   - Pressione `F1` e procure por "Remote-Containers: Open Folder in Container..." 
   - Selecione a pasta `latex_dev_container` que você clonou.

3. **Comece a Escrever**
   - Navegue até a pasta `/paper`.
   - Você encontrará um arquivo `hello_world.tex` e um `hello_world.bib` como exemplos.
   - Você pode deletar esses arquivos de exemplo e copiar seus próprios arquivos LaTeX aqui (do Overleaf por exemplo).

O container está configurado para compilar automaticamente os arquivos `.tex` para PDF cada vez que você salvar alterações. O PDF resultante será localizado no mesmo diretório `/paper`.

## Agradecimentos

Este projeto é um fork e extensão de [qdm12/latexdevcontainer](https://github.com/qdm12/latexdevcontainer). Esse projeto só adiciona uma camada de instalação de vários pacotes LaTeX com cache. Recomendo checar o repositório para mais informações.

## Licença

Este projeto é liberado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
