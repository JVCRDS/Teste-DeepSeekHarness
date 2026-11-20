# Teste DeepSeek Harness

Repositório de estudo e validação de um projeto construído com o **DeepSeek Harness**.
Aqui ficam o código da aplicação, a documentação da API, um front-end simples para
testes e a estrutura de arquitetura e infraestrutura do harness.

---

## Sumário

- [Metas do projeto](#metas-do-projeto)
- [Detalhamento das metas](#detalhamento-das-metas)
- [Como rodar](#como-rodar)
- [Estrutura do repositório](#estrutura-do-repositório)

---

## Metas do projeto

| # | Meta | Status |
|---|------|--------|
| 1 | Documentar as rotas com Swagger | ⏳ A fazer |
| 2 | Criar um front-end simples em XHTML com PrimeFaces para testar as funções do app | ⏳ A fazer |
| 3 | Estruturar o harness (arquitetura + infra) | 🚧 Em andamento |
| 4 | _(a definir)_ | — |
| 5 | _(a definir)_ | — |

**Legenda:** ⏳ A fazer · 🚧 Em andamento · ✅ Concluída

---

## Detalhamento das metas

### 1. Documentar as rotas com Swagger

Expor a documentação de todas as rotas da API com Swagger/OpenAPI, para consultar e
testar os endpoints pelo navegador.

- [ ] Adicionar a dependência do Swagger/OpenAPI ao projeto
- [ ] Documentar cada rota: descrição, parâmetros, corpo da requisição e respostas
- [ ] Deixar a interface do Swagger UI acessível no ambiente local

### 2. Front-end de testes em XHTML com PrimeFaces

Criar uma interface simples, em páginas XHTML com componentes PrimeFaces, para
exercitar as funções do app sem depender de ferramentas externas.

- [ ] Configurar JSF + PrimeFaces no projeto
- [ ] Criar as telas para as principais funções do app
- [ ] Ligar as telas aos serviços/rotas existentes

### 3. Estruturação do harness (arquitetura + infra) — 🚧 em andamento

Definir a arquitetura do projeto e a infraestrutura de build e deploy.

- [x] Iniciar a estruturação do harness
- [x] README do projeto
- [ ] Gerar a imagem da aplicação com Docker Compose
- [ ] Publicar a imagem no GitHub Container Registry (GHCR)
- [ ] Subir a aplicação em uma instância EC2 na AWS

### 4. _(a definir)_

- [ ] ...

### 5. _(a definir)_

- [ ] ...

---

## Como rodar

```bash
git clone https://github.com/JVCRDS/Teste-DeepSeekHarness.git
cd Teste-DeepSeekHarness
```

> Instruções de build e execução (incluindo Docker Compose) serão adicionadas aqui
> quando a meta 3 for concluída.

---

## Estrutura do repositório

> Será preenchida conforme a arquitetura do harness for definida (meta 3).
