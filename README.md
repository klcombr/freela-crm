# Freela CRM

CRM simples e bonito para freelancers. Roda 100% no navegador — sem servidor, sem
cadastro, sem dependências.

![License](https://img.shields.io/badge/license-MIT-blue)
![HTML](https://img.shields.io/badge/HTML5-E34F26)
![CSS](https://img.shields.io/badge/CSS3-1572B6)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E)

## O que é

Um CRM leve feito pra quem trabalha sozinho. Gerencia leads, clientes e receita —
tudo direto no navegador com localStorage.

## Funcionalidades

- **Pipeline de Leads** — Kanban com drag & drop: Novo → Contato → Proposta → Fechado
- **Cadastro de Clientes** — Nome, empresa, email, telefone, notas
- **Tracker de Receita** — Registra pagamentos, calcula total do mês e ticket médio
- **Follow-ups** — Data de retorno por lead, destacada quando atrasada ou para hoje
- **Dashboard** — Leads abertos, ganhos, conversão, valor ganho e pipeline aberto
- **Promoção automática** — mover um lead para "Fechado" cria o cliente na hora
- **100% Local** — Dados ficam no navegador (localStorage)
- **Dark Theme** — Visual profissional, sem enrolação
- **Responsivo** — Funciona no celular e desktop

## Como usar

1. Abra `index.html` no navegador
2. Adicione um lead no Pipeline
3. Arraste entre as colunas conforme o negócio avança
4. Acompanhe receita e conversão no Painel

Sem instalação. Sem cadastro. Sem frescura.

## Backup

Os dados vivem só no seu navegador. No console (F12):

```js
crm.export()                          // baixa um JSON com tudo
crm.import(jsonString)                // restaura a partir do dump
```

## Stack

- HTML5
- CSS3 (variables, grid, flexbox)
- JavaScript vanilla
- localStorage

## Licença

MIT — use como quiser.

---

Feito por [KL Com](https://github.com/klcombr) — freelancer em Praia Grande, SP.
