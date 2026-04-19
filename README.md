# 🌌 Stellar Calculator (Vue 2 Portable)

Uma calculadora imersa em um cosmos orbital, desenvolvida com a estética Pensando no Dark mode.

## 🛠️ Decisão de Arquitetura (Vue 2 via CDN)

Diferente de aplicações SPA modernas que exigem um processo complexo de compilação (Node.js/Vite), este projeto foi estruturado utilizando **Vue 2 via CDN**.

**Por que esta escolha?**
1. **Zero Setup**: Não é necessário instalar dependências ou rodar comandos `npm`.
2. **Performance**: O navegador carrega o framework diretamente de servidores otimizados, resultando em um tempo de carregamento quase nulo.
3. **Portabilidade**: O projeto inteiro reside em um único arquivo, facilitando o deploy imediato no **GitHub Pages**.

## ✨ Funcionalidades

- **Cálculos em Tempo Real**: Reatividade instantânea com o sistema de `data` e `methods` do Vue.
- **Visual Orbital**: Fundo estelar infinito com 3 camadas de profundidade e rotação centrada.
- **CSS pensando em performance**: Uso de `transform: rotate` processado via hardware (GPU) para animações suaves a 60fps.

## 🚀 Como Executar

Por ser uma aplicação baseada em CDN, o uso é extremamente simples:

1. Baixe o arquivo `index.html`.
2. Abra-o em qualquer navegador moderno.
3. Pronto! O Vue será injetado automaticamente e a calculadora estará funcional.

## 🎨 Cores e Estética

A paleta de cores inspirada no **Visual Studio Code**:
- **Comentários**: `#6a9955`
- **Keywords**: `#569cd6`
- **Números**: `#b5cea8`
- **Background**: Deep Black com desvio para o azul escuro (`#0a0a15`).

## 📝 Licença

Este projeto é de código aberto e está sob a licença MIT.

---
