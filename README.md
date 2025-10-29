# Estrutura do Projeto

Este documento explica a estrutura de diretórios e arquivos do projeto, suas responsabilidades e a importância de cada um para o funcionamento do sistema.

## public/
Contém arquivos estáticos que são servidos diretamente pelo servidor, sem processamento. Exemplos incluem favicon, manifest, imagens, e arquivos estáticos que não precisam de manipulação.

## src/arc/
Código fonte principal da aplicação contendo a lógica central da aplicação.

## src/components/
Componentes reutilizáveis que representam unidades de UI independentes e reutilizáveis ao longo do projeto.

## src/features/
Módulos organizados por domínio ou feature, agrupando funcionalidades relacionadas para facilitar manutenção e escalabilidade.

## src/services/
Responsável pela integração com APIs externas, chamadas HTTP, manipulação dos dados recebidos e envio para a camada de apresentação.

## src/hooks/
Hooks personalizados criados para reutilização de lógica em componentes funcionais (React), ou composables em frameworks como Vue.

## src/styles/
Contém estilos globais, variáveis CSS, tokens de design e temas para a aplicação.

## src/main.tsx
Arquivo de entrada principal da aplicação, onde a configuração inicial e o bootstrap da aplicação são realizados.

## src/package.json
Arquivo de configuração de dependências do projeto, scripts de build, script start, e outras configurações relacionadas ao projeto.

## README.structure.md
Este documento que explica a estrutura do projeto para facilitar entendimento e onboarding de novos desenvolvedores.