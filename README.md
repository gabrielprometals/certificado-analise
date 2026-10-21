# Certificados de Análise — Prometals

Sistema em um único arquivo (`index.html`) para buscar, editar e imprimir os **Certificados de Qualidade** que antes eram feitos na planilha *Certificados_da_analise.xlsx*.

Não precisa instalar nada: basta abrir o `index.html` no **Chrome** ou no **Edge**. Funciona sem internet.

## O que dá para fazer

| Tela | Para que serve |
|---|---|
| **Busca de OP** | Digite a OP e veja em qual corrida ela está (procura em OPs/Itens, OP da liga e Referência). Também busca por corrida, material, cliente, pedido ou nº do certificado. Com um só resultado, `Enter` já abre. |
| **Certificado** | Mesmo layout do Excel. Clique em qualquer campo e digite. Botões para **Duplicar**, **Excluir** e **Imprimir / PDF**. Opção de **incluir ou remover a análise química** e a assinatura. |
| **Nova corrida** | Cria um certificado novo, podendo copiar cliente, pedido e produtos de outro. |
| **Banco de dados** | Faixas mín./máx. de cada liga, usadas para conferir a análise química na tela (não sai na impressão). |

### Atalhos
- `/` — vai para a busca
- `Enter` — próximo campo · `Alt` + `Enter` — quebra de linha no campo
- Colar uma linha de valores do Excel/espectrômetro no campo **C** preenche a análise inteira
- `Ctrl` + `P` — imprimir / salvar PDF (A4, mesmo formato da planilha)
- `Esc` — volta para a busca

## Onde ficam os dados

As alterações são salvas **no navegador do computador** onde o arquivo foi aberto (não no arquivo e não no GitHub).

- Para levar para outro computador ou guardar uma cópia: **Backup → Exportar backup (.json)**.
- No outro computador: **Backup → Importar backup…** (escolha *Juntar* ou *Substituir*).
- **Backup → Restaurar dados originais da planilha** volta ao conteúdo importado do Excel.

> ⚠️ Os backups `.json` têm dados de clientes. O `.gitignore` deste repositório impede que sejam enviados ao GitHub por engano — guarde-os na rede interna.

## Privacidade

O `index.html` contém dados de clientes, a logo e a assinatura usadas nos certificados. **Mantenha este repositório privado.** Não ative o GitHub Pages em repositório público.

## Atualizar a versão

Substitua o `index.html` pela versão nova. Os dados já salvos no navegador continuam lá.
