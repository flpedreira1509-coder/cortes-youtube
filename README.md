# Cortes YouTube

**Agent Skill gratuita para Claude:** ajuda a transformar vídeos longos em propostas de cortes verticais de até 30 segundos para Reels, TikTok e YouTube Shorts.

> **Importante:** esta é uma skill de instruções, não um downloader ou editor de vídeo independente. Um link do YouTube, sozinho, não garante que Claude consiga assistir, baixar ou processar o vídeo. A execução depende dos recursos disponíveis no ambiente e do acesso legítimo ao conteúdo.

## Recursos
- Analisa transcrições, legendas, arquivos de vídeo ou conteúdo acessível por ferramentas disponíveis.
- Seleciona momentos com começo, desenvolvimento e conclusão.
- Recomenda cortes de até 30 segundos e timestamps quando confirmados.
- Cria ganchos, títulos, descrições e chamadas para ação.
- Prepara legendas em texto e, quando possível, em SRT.
- Recomenda enquadramento vertical 9:16.
- Informa quando precisa de transcrição, arquivo ou ferramenta adicional.

## Instalação no Claude
1. Baixe `cortes-youtube-skill.zip` neste repositório.
2. Extraia o arquivo. A pasta `cortes-youtube/` contém `SKILL.md` e os materiais de apoio.
3. Se necessário, compacte a pasta `cortes-youtube` novamente, mantendo `SKILL.md` na raiz dela.
4. No Claude, abra as configurações e procure a área de Skills.
5. Ative a execução de código, se a interface/plano exigir, e escolha a opção de adicionar/enviar uma skill.
6. Envie o ZIP da pasta `cortes-youtube` e ative a skill.

A disponibilidade e os nomes dos menus podem variar conforme produto, plano e versão. Consulte a documentação oficial: https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview

## Exemplos de uso
- `Analise este vídeo e encontre os melhores cortes de até 30 segundos: [link]`
- `Encontre 5 momentos fortes nesta transcrição e sugira timestamps.`
- `Crie legendas SRT para esta transcrição temporizada.`
- `Prepare instruções de edição vertical 9:16 para estes cortes.`

## Estrutura
```text
cortes-youtube/
├── SKILL.md
└── references/
    └── guia-de-saida.md
```

## Limitações e transparência
- Claude pode não conseguir acessar o conteúdo apenas pelo link.
- Sem acesso ao vídeo, peça transcrição, arquivo de legenda (VTT/SRT) ou arquivo de mídia compatível.
- Não invente timestamps, falas, cenas ou resultados.
- A exportação de MP4 depende de ferramentas de edição/processamento disponíveis.
- Respeite direitos autorais, termos da plataforma, privacidade e permissões de uso.

## Licença
Este repositório não inclui uma licença ampla por padrão. Se desejar permitir que terceiros modifiquem e redistribuam a skill, adicione uma licença explícita após decidir os termos.
