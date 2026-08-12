# Diagnóstico Comercial — INETRIS

Sistema de diagnóstico empresarial interativo usado pelo setor comercial da INETRIS.

## Como funciona

1. **Diagnóstico**: o cliente responde 15 perguntas Sim/Não divididas em 3 áreas — Planejamento, Pessoas e Processos.
2. **Resultado**: é gerado um painel visual com a pontuação por área e um nível geral (Ruim, Regular, Bom, Ótimo).
3. **Soluções recomendadas**: com base nas áreas que não atingiram o nível "Ótimo", o sistema sugere automaticamente os serviços da INETRIS relacionados a cada área.
4. **Proposta comercial**: o vendedor seleciona os serviços que serão contratados, define valor, forma de pagamento (Pix, Espécie, Boleto ou Cartão), quantidade de prestações e desconto (aplicável apenas no pagamento à vista).
5. **PDF**: a proposta final pode ser baixada em PDF direto pelo navegador, com layout já formatado para impressão/envio ao cliente.

## Tecnologia

Arquivo único em HTML, CSS e JavaScript puro — sem dependências externas, sem necessidade de build ou servidor. Funciona 100% no navegador, incluindo geração do PDF.

## Publicação

Este repositório está publicado via GitHub Pages em:

https://rhalley21.github.io/Diagn-stico-Comercial/

## Atualizando os valores dos serviços

Os valores de referência de cada serviço estão no início do bloco `<script>` do `index.html`, na constante `DEFAULT_SERVICE_VALUE`. Edite os números ali para refletir a tabela de preços real da empresa.
