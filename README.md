# Sorteador de Equipes

Um aplicativo web moderno para criar, sortear e organizar equipes de forma dinâmica, visual e intuitiva. Ideal para projetos, hackathons, trabalhos em grupo, eventos e qualquer situação em que seja necessário dividir pessoas em equipes equilibradas.

## 🚀 Funcionalidades Principais

- **Criação dinâmica de categorias (funções):**
  - Adicione quantas funções/categorias quiser (ex: Programador, Artista, Sonoplasta, etc).
  - Cada categoria pode ter uma cor personalizada escolhida pelo usuário.
  - Remova categorias facilmente (sempre mantendo pelo menos uma).

- **Adição e remoção de membros:**
  - Adicione nomes de participantes em cada categoria.
  - Remova nomes individualmente.
  - Usabilidade aprimorada: adicione nomes pressionando ENTER e o foco permanece no campo.

- **Layout moderno e responsivo:**
  - Categorias exibidas em grade de 3 colunas, centralizadas, com espaçamento agradável.
  - Cores e indicadores visuais para cada categoria.

- **Sorteio inteligente de equipes:**
  - Defina o número mínimo de membros por equipe.
  - O sorteio garante equilíbrio entre as funções nas equipes.
  - Cada equipe recebe pelo menos um membro da função mais numerosa.
  - Evita repetição da função menos numerosa na mesma equipe.
  - Distribuição aleatória e justa dos participantes.

- **Drag & Drop (Arrastar e Soltar):**
  - Após o sorteio, arraste e solte membros entre equipes para ajustes manuais.
  - O estado das equipes é atualizado automaticamente.

- **Exportação para Excel:**
  - Exporte as equipes sorteadas para um arquivo Excel (.xlsx) com apenas um clique.
  - Cada equipe é exportada em uma coluna, com uma coluna vazia como espaçador entre elas.
  - O formato facilita a visualização e impressão.

- **Interface amigável:**
  - Design escuro, moderno e agradável.
  - Botões grandes e intuitivos.
  - Mensagens de alerta para evitar erros comuns.
  - Totalmente em português.

## 📝 Passo a Passo de Uso

1. **Abra o arquivo `index.html` em seu navegador.**
2. **Adicione as funções/categorias desejadas:**
   - Digite o nome da função (ex: Programador) e escolha uma cor.
   - Clique em "Adicionar Categoria" ou pressione ENTER.
3. **Adicione os nomes dos participantes em cada categoria:**
   - Digite o nome e clique em "Adicionar" ou pressione ENTER.
   - Repita para todos os participantes.
4. **Defina o mínimo de membros por equipe** no topo da página.
5. **Clique em "Sortear Equipes"** para gerar as equipes equilibradas.
6. **Ajuste manualmente (opcional):**
   - Arraste e solte membros entre equipes conforme necessário.
7. **Exporte para Excel:**
   - Clique em "Exportar para Excel" para baixar o arquivo com as equipes.

## 💡 Dicas e Observações

- O sorteio sempre tenta equilibrar as funções entre as equipes.
- Você pode criar quantas categorias quiser, com qualquer nome e cor.
- O sistema impede que haja menos de uma categoria.
- O layout se adapta a diferentes tamanhos de tela.
- O arquivo Excel gerado é compatível com Microsoft Excel, Google Sheets e LibreOffice.
- O aplicativo funciona 100% local, sem necessidade de internet após baixar o arquivo.

## 📦 Como usar offline

1. Baixe o repositório ou apenas o arquivo `index.html`.
2. Dê um duplo clique no arquivo para abrir no navegador.
3. Pronto! Não é necessário instalar nada.

## 🛠️ Tecnologias Utilizadas

- HTML5, CSS3 e JavaScript puro (sem frameworks)
- [xlsx.js](https://github.com/SheetJS/sheetjs) para exportação Excel (via CDN)

## 👨‍💻 Autor

Feito com carinho por Prof Bruno Martins.

---

Sinta-se à vontade para sugerir melhorias ou relatar problemas!

