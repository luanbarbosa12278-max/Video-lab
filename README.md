# VideoLab v2

Site de diagnóstico e exportação de vídeos curtos para navegador.

## Recursos
- Upload e prévia de MP4, MOV e WebM (até aproximadamente 10 segundos, com tolerância técnica)
- Informações de duração, dimensões, tamanho e tipo de arquivo
- Inspeção limitada de termos textuais associados a procedência; não valida C2PA nem detecta SynthID
- Ajustes de brilho, contraste e saturação
- Exportação por MediaRecorder + Canvas: resolução original ou redimensionamento para altura 1920/1280 mantendo proporção
- Áudio incluído quando suportado pelo navegador
- Download MP4 quando MediaRecorder oferece MP4; caso contrário WebM

## Publicação
Em Settings > Pages, escolha Deploy from a branch, main, /(root).

## Limitações
- A conversão de 720p para 1080p não restaura detalhes inexistentes.
- A inspeção textual não é uma análise completa de metadados nem prova ausência de marcas invisíveis.
- A exportação em tempo real pode ter dificuldades em dispositivos lentos, ao mudar de aba ou em navegadores sem suporte ao MediaRecorder.
- O site não remove marcas de procedência nem garante mudanças em etiquetas aplicadas por plataformas.
- Testar no navegador alvo antes de uso em produção.
