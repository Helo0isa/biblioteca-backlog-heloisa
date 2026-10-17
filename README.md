# 📚 Backlog da Biblioteca Saber Livre

Atividade prática de **Gestão Ágil de Projetos de Software** (Fatec Araras), com o Prof. Me. Orlando Saraiva Júnior. Nela eu fiz o papel de Product Owner da **Biblioteca Comunitária Saber Livre** e montei o backlog inicial do sistema web que a biblioteca quer, usando o **GitHub Projects**.

## Onde ver o backlog

👉 **[Abrir o Project no GitHub](LINK_DO_PROJECT)**

No Project tem duas visualizações principais:
- **Sprint 1:** quadro (Board) só com as estórias da primeira sprint, separadas por status.
- **Backlog por épico:** tabela com todas as estórias agrupadas debaixo do épico de cada uma, com estimativa, prioridade e sprint.

A meta da sprint, a capacidade e a justificativa do MVP estão no README do Project.

## O problema

Hoje a biblioteca controla tudo em fichas de papel e numa planilha compartilhada. Isso gera problemas como:
- ninguém sabe quantos exemplares de cada livro estão disponíveis;
- os leitores esquecem as datas de devolução e os atrasos são comuns;
- livros muito procurados ficam "presos" com quem devolve tarde;
- a coordenação não sabe quais livros são mais lidos para planejar compras.

## Como o backlog está organizado

| Épico | O que cobre | Estórias |
|---|---|---|
| E1 — Acervo | Cadastro de títulos e exemplares, situação dos exemplares, consulta pública | 5 |
| E2 — Leitores | Cadastro, tipos de leitor, LGPD, área do leitor | 4 |
| E3 — Empréstimos e devoluções | Registro no balcão, limites, prazos e renovações | 5 |
| E4 — Reservas | Fila de reserva, prazo de retirada de 48 h, cancelamento | 4 |
| E5 — Multas e bloqueios | Cálculo de multa, pagamento, bloqueio e desbloqueio | 4 |
| E6 — Notificações | E-mails de vencimento, atraso e reserva disponível | 3 |
| E7 — Relatórios | Livros mais emprestados, atrasos e leitores ativos | 3 |

No total são **7 épicos e 28 estórias**. Cada estória tem:
- texto no formato **Como / Quero / Para**;
- critérios de aceite no formato **Dado / Quando / Então**, usando os números das regras de negócio (RN01 a RN14);
- estimativa (em pontos) e prioridade (Alta, Média ou Baixa);
- tarefas detalhadas em algumas delas (E1-01, E2-01, E3-01 e E3-02).

## Sprint 1

**Meta:** entregar o menor caminho que já resolve um problema real. Qualquer pessoa consulta se um livro está disponível, e o bibliotecário cadastra acervo e leitores e registra empréstimos e devoluções.

**Estórias:** E1-01, E1-03, E1-04, E2-01, E2-02, E3-01 e E3-02, num total de 29 pontos.

## Estória dividida

Um exemplo de divisão de estória está documentado em um comentário na issue do épico **E4 — Reservas**, explicando o padrão de divisão que usei.

## Modelo de issue

O repositório tem um modelo de estória em `.github/ISSUE_TEMPLATE/estoria.yml`, que monta o formulário Como / Quero / Para com regras de negócio, critérios de aceite e tarefas.

---

Feito por **Heloísa Avelino Mazon** para a disciplina de Gestão Ágil de Projetos de Software.
