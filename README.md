# VideoLab

Editor de vídeos curtos que funciona no navegador, em celular e computador.

## Funcionalidades
- Upload de MP4, MOV e WebM de até 10 segundos (desde que o navegador consiga ler a duração)
- Pré-visualização
- Ajustes de brilho, contraste, saturação e nitidez
- Presets de cor
- Exportação MP4 com FFmpeg.wasm, sem upload para servidor

## Como publicar
1. Abra Settings > Pages no GitHub.
2. Em Build and deployment, escolha Deploy from a branch.
3. Selecione `main` e `/ (root)` e salve.
4. Aguarde a URL aparecer no painel Pages.

## Notas
- O motor FFmpeg.wasm é baixado de CDN na primeira execução. Precisa de internet para isso.
- A exportação pode exigir bastante memória em celulares. Alguns arquivos MOV podem não ser compatíveis.
- O site não remove nem falsifica informações de procedência de IA e não promete alterar rótulos aplicados por plataformas.
- A exportação precisa ser validada no navegador de destino antes de uso em produção.
