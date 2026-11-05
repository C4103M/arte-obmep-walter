# Modelo de Cartaz - OBMEP Mirim (EMEFEI Walter Friedrich)

Este projeto contém a recriação fiel em HTML5 e CSS3 do cartaz comemorativo da OBMEP Mirim para a escola **EMEFEI Walter Friedrich**.

## Como Usar

1. **Abrir o arquivo:**
   Dê um duplo clique no arquivo [`index.html`](file:///d:/Caio/Desktop/prototipo/index.html) para abri-lo em qualquer navegador moderno (Chrome, Edge, Firefox, etc.).

2. **Seletor de Nível (OBMEP Mirim 1 vs Mirim 2):**
   - Na barra superior, use o seletor `[ Mirim 1 (I) ] [ Mirim 2 (II) ]`.
   - Ao selecionar **Mirim 1**, o logo da OBMEP exibe o número romano **I** logo após o nome "mirim" e a faixa comemorativa exibe `OBMEP MIRIM I!`.
   - Ao selecionar **Mirim 2**, o logo da OBMEP exibe o número romano **II** logo após o nome "mirim" e a faixa exibe `OBMEP MIRIM II!`.
   - O seletor desaparece 100% na impressão.

3. **Como adicionar e remover cards (Alunos):**
   - **Padrão de 10 cards:** O cartaz vem configurado por padrão com 10 cards distribuídos perfeitamente (`2` no topo centralizados, `4` no meio e `4` na base).
   - **Cards de nome vazios:** Enquanto nenhuma foto ou nome for inserido, o espaço de nome permanece limpo e vazio.
   - **Botões `+` e `−` na barra superior e flutuantes:** Clique em `+` para adicionar novos alunos ou `−` para remover o último.
   - **Excluir card específico (✕):** Passe o mouse sobre qualquer card e clique no botão vermelho `✕` no canto superior esquerdo para remover aquele card individualmente.
   - **Ajuste automático de layout:** O cartaz reorganiza a distribuição de linhas e colunas dinamicamente para preservar o equilíbrio estético e o alinhamento.
   - **100% invisíveis na impressão:** Todos os botões de adicionar, subtrair e excluir desaparecem completamente ao imprimir.

4. **Como adicionar as fotos das pessoas:**
   - **Preenchimento Automático do Nome:** Ao selecionar uma imagem (ex: `LUCAS_SILVA.jpg`), o nome do arquivo é automaticamente formatado e preenche o espaço de nome do estudante (`LUCAS SILVA`).
   - O aviso `+ Foto` desaparece automaticamente assim que a foto é carregada e nunca aparece na impressão.
   - Ao passar o mouse sobre um card com foto, surge o botão sutil `Trocar Foto`.

5. **Como editar os nomes:**
   - **Botão Lapizinho (✏️):** Ao passar o mouse sobre qualquer card ou faixa de nome, aparece um botão com ícone de lápis. Clique nele (ou dê um duplo clique no nome) para editar diretamente.
   - Pressione `Enter` ou clique fora para salvar a alteração.
   - Este botão é 100% ocultado na impressão.

6. **Impressão Sem Margens e Sem Sobreposições:**
   - Clique no botão **"🖨️ Imprimir / Salvar PDF"** ou use o atalho `Ctrl + P`.
   - O espaçamento do cabeçalho foi calibrado para que a faixa *"PARA A 2ª FASE DA OBMEP MIRIM"* e a frase cursiva *"nosso orgulho é ver o talento de vocês!"* nunca se sobreponham.
   - O CSS já está configurado com `@page { size: A4 portrait; margin: 0; }` e `-webkit-print-color-adjust: exact;` para ocupar 100% da folha sem bordas brancas e com todas as cores fiéis.
   - Na janela de impressão do navegador, certifique-se de que a opção **"Gráficos de segundo plano" (Background graphics)** esteja marcada e **Margens** definida como **"Nenhuma"** (se solicitado).

