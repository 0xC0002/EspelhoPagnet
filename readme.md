# MagPagNET

Ferramenta em Python para extrair automaticamente campos especificos das provisões



O **MagPagNET** facilita o processo manual de copiar e colar informações de provisões para o PagNET. Com apenas um **Ctrl+A → Ctrl+C** na página de provisões, o software:

1. Detecta os campos essenciais (empresa, filial, centro de custo, tipo de operação etc.)
2. Exibe cada valor em botões clicáveis (cópia automática ao clicar)
3. Mantém a janela sempre em destaque (atributo topmost)
4. Feedback de campos faltantes em vermelho (Sugestão do gestor)

## Recursos

- Extração de campos da provisão:
  - `Pagnet Empresa`, `Pagnet Filial`, `Centro de Custo Solicitante`
  - `Pagnet Tipo de Operação Pagto`, `Pagnet Forma Pagamento`
  - `Pagnet Evento para Pagamento`, `Contrato Sistema jurídico ID`
  - `Pagnet Descrição Pagamento`, `Centro de Custo Definição`, `Centro de Custo`
- Ícone customizado da MAG Seguros
- Uso simples e fácil de entender

## Uso

1. Abra a uma provisão a ser copiado os campos.
2. Pressione **Ctrl+A** para selecionar tudo e **Ctrl+C** para copiar.
3. Execute:
   ```bash
   magpagnet
   ```
4. Clique nos botões correspondentes para copiar cada campo diretamente ao clipboard.
5. Ao finalizar, clique em **Fechar Janela** e responda **Sim** para reiniciar o processo, ou **Não** para fechar o magPagnet.

## Licença

MIT © Bruno Antunes Fernandes

