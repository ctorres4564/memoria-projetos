# FonoSuite

## Objetivo

Este repositório constitui a memória permanente do ecossistema **FonoSuite**.

Seu objetivo é preservar o contexto, a arquitetura, as decisões, o histórico de desenvolvimento e a documentação de todos os projetos da plataforma, permitindo que qualquer desenvolvedor ou agente de IA continue o trabalho exatamente do ponto em que foi interrompido.

Este repositório não contém o código-fonte dos sistemas. Ele concentra a documentação viva que orienta o desenvolvimento de cada projeto.

---

# Estrutura

```
Projetos/
    FonoSuite Space/
    FonoSuite Anamnese/
    TeaFono/
    PueriCare/
    FonoLab/
    Hermes/
    ...

Templates/

Inbox.md

AGENTS.md

README.md
```

---

# Organização dos projetos

Cada projeto possui sua própria pasta contendo, no mínimo, os seguintes documentos:

```
Projeto/

    Contexto.md

    Estado Atual.md

    Diário do Projeto.md

    Decisões.md
```

## Contexto

Documento permanente.

Contém:

- objetivo do projeto;
- arquitetura;
- tecnologias utilizadas;
- regras importantes;
- visão geral;
- informações estáveis.

---

## Estado Atual

Representa a situação do projeto neste momento.

Deve responder rapidamente:

- em que estágio o projeto está;
- o que já foi concluído;
- o que está sendo desenvolvido;
- qual é a próxima tarefa;
- quais problemas permanecem em aberto.

---

## Diário do Projeto

Registro cronológico das atividades.

Cada atualização deve informar:

- data;
- alterações realizadas;
- arquivos modificados;
- decisões tomadas;
- problemas encontrados;
- próximos passos.

---

## Decisões

Registro permanente das decisões técnicas, arquiteturais e funcionais.

Nenhuma decisão importante deve ser perdida.

Sempre registrar:

- o que foi decidido;
- motivo;
- impacto;
- alternativas descartadas.

---

# Fluxo de trabalho

Antes de iniciar qualquer atividade:

1. Ler `AGENTS.md`.
2. Identificar o projeto correspondente.
3. Ler `Contexto.md`.
4. Ler `Estado Atual.md`.
5. Consultar `Decisões.md`, quando necessário.
6. Executar a tarefa.

Ao finalizar:

1. Atualizar `Estado Atual.md`.
2. Registrar a atividade em `Diário do Projeto.md`.
3. Atualizar `Decisões.md`, quando houver mudança relevante.
4. Sincronizar as alterações com o GitHub.

---

# Inbox

A nota **Inbox** funciona como caixa de entrada.

Ela deve receber:

- ideias;
- lembretes;
- observações rápidas;
- decisões ainda não organizadas;
- informações capturadas durante reuniões ou conversas.

Posteriormente essas informações devem ser distribuídas para os documentos corretos.

---

# Templates

A pasta **Templates** contém os modelos oficiais utilizados para criação de novos projetos e novos documentos.

Todos os projetos devem seguir a mesma estrutura documental.

---

# Integração com IA

Este repositório foi estruturado para servir como memória permanente para agentes de IA.

Os agentes devem utilizar:

- README.md como ponto de entrada;
- AGENTS.md como regras de funcionamento;
- documentação do projeto como contexto operacional.

O objetivo é permitir que diferentes agentes trabalhem de forma contínua, compartilhando o mesmo contexto sem perda de informações.

---

# Princípios

- A documentação é parte do projeto.
- O histórico nunca deve ser apagado.
- Decisões devem ser registradas.
- O contexto deve permanecer atualizado.
- A memória do projeto deve permitir que qualquer agente ou desenvolvedor continue o trabalho sem necessidade de reconstruir o contexto.