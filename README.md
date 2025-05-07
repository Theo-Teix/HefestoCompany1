# Landing Page Hefesto - Sistema de Acompanhamento de Obras 3D

Este projeto contém o código-fonte de uma landing page desenvolvida para a Hefesto, com foco em apresentar seu sistema de acompanhamento de obras de prédios com visualização 3D.

## Estrutura de Arquivos

```
/
├── index.html             # Arquivo principal da landing page
├── css/
│   └── style.css          # Folha de estilos da página
├── images/                # Pasta para imagens (atualmente com placeholders no código)
├── landing_page_structure.md # Documento com a estrutura e conteúdo definidos
└── README.md              # Este arquivo
```

## Como Visualizar e Editar (VSCode)

1.  **Baixe e Descompacte o Arquivo .zip:**
    *   Faça o download do arquivo `hefesto_landing_page.zip` fornecido.
    *   Descompacte o conteúdo em uma pasta de sua preferência no seu computador.

2.  **Abra no VSCode:**
    *   Abra o Visual Studio Code.
    *   Vá em `File > Open Folder...` (Arquivo > Abrir Pasta...).
    *   Navegue até a pasta onde você descompactou os arquivos e selecione-a.

3.  **Visualize a Landing Page:**
    *   No painel explorador de arquivos do VSCode (geralmente à esquerda), clique com o botão direito no arquivo `index.html`.
    *   Se você tiver a extensão "Live Server" instalada (recomendado):
        *   Clique em "Open with Live Server". Isso abrirá a página no seu navegador padrão e atualizará automaticamente quando você fizer alterações no código.
    *   Caso não tenha o Live Server:
        *   Você pode simplesmente abrir o arquivo `index.html` diretamente no seu navegador (arraste o arquivo para uma janela do navegador ou use "Abrir arquivo" no menu do navegador).

4.  **Editando o Conteúdo:**
    *   **HTML (`index.html`):** Contém toda a estrutura e o texto da página. Você pode editar os textos, adicionar ou remover seções diretamente neste arquivo.
    *   **CSS (`css/style.css`):** Contém todos os estilos visuais (cores, fontes, layout). As classes e IDs utilizados no HTML são estilizados aqui. O arquivo CSS está comentado para facilitar a identificação das seções.
    *   **Imagens (`images/`):** Atualmente, a página usa placeholders para as imagens da visualização 3D. Para adicionar suas próprias imagens:
        *   Coloque os arquivos de imagem (ex: `.jpg`, `.png`, `.svg`) dentro da pasta `images/`.
        *   No arquivo `index.html`, localize os comentários como `<!-- Placeholder para imagem/visualização 3D -->` ou as divs com classes como `hero-3d-placeholder`.
        *   Substitua o texto do placeholder ou adicione uma tag `<img>`, por exemplo: `<img src="images/sua-imagem.jpg" alt="Descrição da Imagem">`.

## Identidade Visual

*   **Cores Principais:**
    *   Azul Escuro (Títulos, Elementos de Destaque): `#2C3E50`
    *   Cinza Claro (Fundos de Seção): `#ECF0F1`
    *   Laranja (Botões CTA, Links): `#FF9800`
    *   Cinza Escuro (Texto Principal): `#333333`
*   **Fontes:**
    *   Títulos: Montserrat
    *   Corpo do Texto: Open Sans

## Próximos Passos Sugeridos

*   Substituir os placeholders de imagem/visualização 3D por imagens ou elementos visuais reais do sistema Hefesto.
*   Atualizar as informações de contato (email, telefone) e links de redes sociais no rodapé.
*   Integrar com um backend ou formulário de contato, se necessário para o botão "Solicite uma Demonstração".

--- 

Desenvolvido por Manus.
