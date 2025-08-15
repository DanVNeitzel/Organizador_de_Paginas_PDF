**[Preview](https://danvneitzel.github.io/Organizador_de_Paginas_PDF/)**

# Organizador de Páginas PDF (HTML, CSS, JS + Bootstrap)

Este projeto é uma aplicação web que permite carregar um arquivo PDF, visualizar suas páginas, reorganizá-las, adicionar novas páginas em branco e exportar um novo PDF com as alterações feitas.  
Tudo é feito diretamente no navegador utilizando HTML, CSS, JavaScript e Bootstrap — sem necessidade de backend.

## ✨ Funcionalidades
- **Upload de PDF**: Carregue um arquivo PDF e visualize cada página como miniatura.
- **Reorganizar páginas**: Arraste e solte para mudar a ordem das páginas.
- **Adicionar novas páginas**: Insira páginas em branco ou importe páginas de outro PDF.
- **Remover páginas**: Selecione páginas para excluir antes de exportar.
- **Exportar novo PDF**: Gere um novo arquivo PDF com todas as modificações.
- **Interface responsiva**: Layout agradável com Bootstrap.

## 🛠 Tecnologias Utilizadas
- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **Bootstrap 5**
- **[PDF.js](https://mozilla.github.io/pdf.js/)** para leitura e renderização do PDF
- **[pdf-lib](https://pdf-lib.js.org/)** para manipulação e exportação do PDF

## 📂 Estrutura de Arquivos
```
/
├── index.html          # Página principal
├── style.css           # Estilos customizados
├── script.js           # Lógica principal
├── README.md           # Documentação do projeto
└── libs/               # Bibliotecas externas (pdf.js e pdf-lib)
```

## 🚀 Como Usar
1. **Baixe ou clone este repositório**:
   ```bash
   git clone https://github.com/seu-usuario/organizador-pdf.git
   ```
2. **Abra o arquivo `index.html` no navegador**.
3. **Carregue um PDF** usando o botão de upload.
4. **Reorganize, adicione ou remova páginas** conforme desejar.
5. **Clique em "Exportar PDF"** para baixar o arquivo modificado.

## 📦 Bibliotecas
Certifique-se de incluir no `index.html`:
```html
<script src="libs/pdf.min.js"></script>
<script src="libs/pdf.worker.min.js"></script>
<script src="libs/pdf-lib.min.js"></script>
```

## ⚠️ Observações
- Todo o processamento é feito **no lado do cliente** (client-side).
- O desempenho pode variar para PDFs muito grandes.
- Navegadores diferentes podem ter tempos de carregamento distintos.

## 📜 Licença
Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.
