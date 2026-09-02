# Fluxo — controle financeiro pessoal

![Capa do Fluxo](cover.png)

Um app simples de controle financeiro em HTML/JS puro, sem frameworks e sem back-end. Registra entradas e saídas, calcula o saldo automaticamente e mostra um resumo de gastos por categoria.

## Funcionalidades

- Saldo atual, total de entradas e total de saídas
- Cadastro de lançamentos com valor, data, descrição e categoria
- Aceita valor com vírgula ou ponto decimal (`150,50` ou `150.50`)
- Resumo de gastos agrupado por categoria
- Lista dos últimos lançamentos, com opção de excluir
- Os dados ficam salvos automaticamente (usando a API de armazenamento do ambiente onde o app está rodando)

## Como usar

Basta abrir o `index.html` em qualquer navegador. Se publicar com o **GitHub Pages**, o app fica disponível direto em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

### Publicar com GitHub Pages

1. Suba os arquivos deste repositório para o GitHub.
2. Vá em **Settings → Pages**.
3. Em **Source**, selecione a branch `main` e a pasta `/root`.
4. Salve — o link fica disponível em alguns minutos.

## Tecnologias

Apenas HTML, CSS e JavaScript puro (sem dependências, sem build).

## Observação sobre armazenamento

O app salva os lançamentos automaticamente no `localStorage` do navegador, então os dados continuam lá mesmo depois de fechar a aba. (Se estiver rodando dentro do ambiente do Claude, ele usa a API de armazenamento própria do Claude em vez disso.)

