# Landing Page — Fernando Sato (`FS.HUB`)

Landing page responsiva em página única (*Single Page Application* estática), desenvolvida com HTML5, CSS3 e JavaScript puro, pronta para hospedagem gratuita via **GitHub Pages**.

## Seções Incluídas

- **Carrossel Hero Interativo:** 7 slides dedicados com navegação por setas, indicadores, autoplay e suporte a gestos (*swipe*), direcionando diretamente para cada seção.
- **Games:** Destaques sobre mídia física, latência de rede e biblioteca favorita.
- **Galeria:** Grade de imagens com filtro por categoria (`Telecom & Campo`, `Dev & Apps`, `Setup & Hardware`) e visualização ampliada (*lightbox*).
- **Timão:** Espaço dedicado ao Sport Club Corinthians Paulista com escudo estilizado em SVG, conquistas e mural interativo.
- **Trabalho:** Apresentação da atuação em engenharia de campo telecom (HFC/DOCSIS/Wi-Fi) e utilitários web mobile.
- **Download:** Geração e download instantâneo de arquivos técnicos (`niveis-rf-docsis.txt` e `checklist-campo.json`).
- **Links:** Central de atalhos rápidos e repositórios.
- **Contato:** Formulário interativo e cópia rápida de identificação.

## Estrutura do Repositório

```text
├── index.html                    # Código completo da Landing Page (HTML + CSS + JS)
├── README.md                     # Documentação do projeto
└── scripts/
    └── atualizar-revisao.py      # Script para atualizar versão, data e hora no rodapé ao editar o código
```

## Controle de Versão no Rodapé

O rodapé exibe o texto fixo da última revisão gravada no código-fonte:

```text
Criado por: Fernando Sato - Versão 1.1 - 24/11/2026 20:37
```

Para evitar alterações falsas a cada visualização no navegador, **a versão, data e hora não utilizam `new Date()` em tempo real**. Elas permanecem estáticas no HTML e são atualizadas apenas quando você edita uma nova revisão.

### Como atualizar a versão ao editar o projeto

1. **Via script Python (recomendado):**
   Execute o script incluído na pasta `scripts/` antes de fazer o *commit*:
   ```bash
   python scripts/atualizar-revisao.py 1.2
   ```
   O script incrementa/define a versão informada, captura a data e hora exatas da edição e atualiza tanto o texto do rodapé no `index.html` quanto este `README.md`.

2. **Manualmente:**
   Edite a tag `<footer>` no arquivo `index.html`:
   ```html
   <p class="footer-version" id="footerRevision" data-version="1.2" data-updated="DD/MM/AAAA HH:MM">
     Criado por: Fernando Sato - Versão 1.2 - DD/MM/AAAA HH:MM
   </p>
   ```

## Publicação no GitHub Pages

1. Crie um repositório no GitHub e envie os arquivos `index.html` e `README.md`.
2. Acesse **Settings > Pages** no repositório.
3. Em **Build and deployment > Branch**, selecione `main` e a pasta `/ (root)` e clique em **Save**.
4. O site ficará acessível em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.
