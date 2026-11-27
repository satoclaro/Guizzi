# Landing Page — Fernando Sato (`FS.HUB`)

Landing page responsiva em página única (*Single Page Application* estática), desenvolvida com HTML5, CSS3 e JavaScript puro, pronta para hospedagem gratuita via **GitHub Pages**.

## Seções e Subseções Incluídas

- **Carrossel Hero Interativo:** 7 slides dedicados com navegação por setas, indicadores, autoplay e suporte a gestos (*swipe*), direcionando diretamente para cada seção.
- **Games:** Destaques sobre mídia física, latência de rede e biblioteca favorita, com as subseções **Arcade**, **Nintendo**, **Super Nes**, **Mega Drive**, **Emuladores** e **Roms**.
- **Galeria:** Grade de imagens com filtro por categoria (`Telecom & Campo`, `Dev & Apps`, `Setup & Hardware`) e visualização ampliada (*lightbox*).
- **Timão:** Espaço dedicado ao Sport Club Corinthians Paulista com escudo estilizado em SVG, mural interativo e as subseções **História**, **Títulos**, **Fotos** e **Wallpaper**.
- **Trabalho:** Apresentação da atuação em engenharia de campo telecom (HFC/DOCSIS/Wi-Fi) e utilitários web mobile, incluindo atalhos para `Claro-Estoque`, `Equipamentos-` e `Tivit`.
- **Download:** Geração e download instantâneo de arquivos técnicos e subseções dedicadas (**Games**, **Trabalho**, **Fotos** e **Wallpaper**).
- **Links:** Central de atalhos rápidos para `Claro-Estoque`, `Equipamentos-`, `Tivit`, `Guizzi` e `github.com/satoclaro/Teste`.
- **Contato:** Formulário interativo e cópia rápida de identificação.
- **Seção e Página Secreta:** O link `Secreto` permanece camuflado na cor do fundo até ser selecionado (`::selection` / selecionar tudo), e a página secreta funciona **somente com o código `2103`**.

## Estrutura do Repositório

```text
├── index.html                    # Código completo da Landing Page (HTML + CSS + JS)
└── README.md                     # Documentação do projeto
```

## Controle de Versão no Rodapé

O rodapé exibe o texto estático da última revisão gravada diretamente no `index.html`:

```text
Criado por: Fernando Sato - Versão 1.5 - 26/11/2026 21:41
```

Para evitar alterações a cada visualização no navegador, **a versão, data e hora não utilizam `new Date()` em tempo real**. Elas permanecem fixas no HTML e são atualizadas diretamente aqui a cada nova revisão solicitada.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub e envie os arquivos `index.html` e `README.md`.
2. Acesse **Settings > Pages** no repositório.
3. Em **Build and deployment > Branch**, selecione `main` e a pasta `/ (root)` e clique em **Save**.
4. O site ficará acessível em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.
