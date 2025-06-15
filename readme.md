# MagPagNET

Ferramenta GUI em Python para extrair automaticamente certos campos das provisões



O **MagPagNET** facilita o processo manual de copiar e colar informações de provisões para o sistema PagNET. Com apenas um **Ctrl+A → Ctrl+C** na página de provisões, o software:

1. Detecta os campos essenciais (empresa, filial, centro de custo, tipo de operação etc.)
2. Exibe cada valor em botões clicáveis (cópia automática ao clicar)
3. Mantém a janela sempre em destaque (topmost)
4. Feedback de campos faltantes em vermelho

## Recursos

- Extração inteligente de campos PagNET:
  - `Pagnet Empresa`, `Pagnet Filial`, `Centro de Custo Solicitante`
  - `Pagnet Tipo de Operação Pagto`, `Pagnet Forma Pagamento`
  - `Pagnet Evento para Pagamento`, `Contrato Sistema jurídico ID`
  - `Pagnet Descrição Pagamento`, `Centro de Custo Definição`, `Centro de Custo`
- Ícone customizado da MAG Seguros

## Uso

1. Abra a página de provisões no SharePoint.
2. Pressione **Ctrl+A** para selecionar tudo e **Ctrl+C** para copiar.
3. Execute:
   ```bash
   magpagnet
   ```
4. Clique nos botões correspondentes para copiar cada campo diretamente ao clipboard.
5. Ao finalizar, clique em **Fechar Janela** ou responda **Não** no prompt de novo.

## Licença

MIT © Bruno Antunes Fernandes

