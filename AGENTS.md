# Regras do Projeto

## Backup de Arquivos

Antes de realizar **qualquer alteração** em qualquer arquivo do projeto, deve-se:

1. Criar um backup do arquivo original antes de modificá-lo
2. Os backups devem ser salvos com o formato: `<nome_original>.bak.<data_hora>` (ex: `index.html.bak.20260330120000`)
3. Armazenar os backups na pasta `backup` na raiz do projeto

## Processo de Alteração

Sempre que o usuário solicitar uma alteração no projeto:

1. **Primeiro passo**: Ler o conteúdo deste arquivo AGENTS.md
2. Identificar todos os arquivos que serão alterados
3. Criar backup de cada arquivo conforme regras acima
4. Realizar as alterações solicitadas
5. Verificar se a alteração foi aplicada corretamente

## Observações

- Estas regras se aplicam a todos os arquivos do projeto (HTML, CSS, JS, imagens, etc.)
- A data/hora no backup deve seguir o formato: YYYYMMDDHHMMSS
- A pasta `backup` está configurada no `.gitignore` para não ser enviada ao repositório remoto
