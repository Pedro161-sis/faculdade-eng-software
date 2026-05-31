# Relatório de Otimização de Performance Web - Unidade 4, Aula 1

Este documento registra o aprendizado prático sobre diagnóstico de performance web utilizando a ferramenta **WebPageTest**, aplicando os conceitos de auditoria em projetos front-end.

## 🎯 Objetivo do Teste
Avaliar a velocidade de carregamento, identificar gargalos de renderização e propor melhorias técnicas com base nas métricas do Core Web Vitals.

## 📊 Métricas Analisadas
* **First Contentful Paint (FCP):** Tempo até o primeiro elemento visual aparecer.
* **Largest Contentful Paint (LCP):** Tempo de carregamento do maior bloco de conteúdo (geralmente a imagem principal).
* **Time to Interactive (TTI):** Tempo necessário para a página se tornar totalmente interativa para o usuário.

## 🛠️ Recomendações Técnicas para Otimização
1. **Mídias Eficientes:** Converter imagens antigas (PNG/JPEG) para formatos modernos como **WebP** ou **AVIF**.
2. **Eliminar Bloqueios:** Adicionar os atributos `defer` ou `async` em scripts JavaScript que bloqueiam a renderização do HTML.
3. **Minificação:** Reduzir o tamanho de arquivos CSS e JS removendo espaços e comentários em produção.
