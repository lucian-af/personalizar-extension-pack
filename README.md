# Personalizar Extension Pack

Conjunto de plugins para o VS Code que eu utilizo.

## Gostaria de instalar somente algumas extensões?

Para instalar somente algumas das extensões, basta editar o arquivo [package.json](package.json) removendo as extensões não desejadas do `extensionPack` e depois siga os procedimentos abaixo para instalar localmente.

## Como desenvolver e instalar localmente

- Clone o repositório

```bash
$ git clone https://github.com/lucian-af/personalizar-extension-pack
```

- Instale o vsce

```bash
$ npm install -g vsce
```

- Crie o pacote da extensão

```bash
$ vsce package
```

- Instale a extensão através do arquivo `.vsix`

1. Abra o VS Code
2. Selecione **Extensions** do menu
3. Clique em **More** > **Install from VSIX...**
4. Selecione o arquivo `reactavancado-extension-pack-x.x.x.vsix`
5. Clique em **Reload Now** para recarregar o VS Code

