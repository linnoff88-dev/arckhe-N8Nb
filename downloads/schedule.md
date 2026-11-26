# ⏰ Schedule Trigger - N8N Fundamentos

## 📚 O que é?

O **Schedule Trigger** é o node que permite executar workflows automaticamente em horários pré-determinados ou em intervalos regulares. É como um despertador ou cronômetro para suas automações.

Ideal para tarefas repetitivas que precisam acontecer sem intervençêo manual: relatórios diários, backups noturnos, sincronizações de dados, entre outros.

---

## ⏱️ Intervalos e CRON

### O que é:
Execute workflows a cada X minutos, horas, dias ou use expressões CRON para agendamentos complexos.

### Intervalos Simples:
- ✓ A cada 5 minutos
- ✓ A cada 1 hora
- ✓ A cada 1 dia

### CRON Avançado:
- ✓ Segunda a sexta às 9h
- ✓ Todo dia 1 do mês às 00h
- ✓ Padrões personalizados

### Por que aprender:
Automatize tarefas repetitivas sem intervençêo manual (relatórios, backups, sincronizações).

---

## 🌍 Configuraçêo de Timezone

### O que é:
Definir o fuso horário correto para garantir execuções no horário local desejado.

### ⚠️ Atençêo:
Servidores geralmente rodam em UTC. Sempre configure o timezone correto para evitar execuções em horários errados!

### Conceitos chave:
UTC, GMT, timezone local, horário de verêo.

---

## 💡 Exemplos Práticos

### 1. Relatório Diário
Execute todo dia às 8h para enviar relatório de vendas do dia anterior.
```
CRON: 0 8 * * *
```

### 2. Backup Semanal
Execute todo domingo às 3h da manhê para fazer backup do banco de dados.
```
CRON: 0 3 * * 0
```

### 3. Sincronizaçêo Horária
Execute a cada hora para sincronizar dados entre sistemas.
```
Intervalo: 1 hora
```

---

## 📌 Principais Tópicos

### Intervalos e CRON
- **O que é:** Execute workflows a cada X minutos, horas, dias ou use CRON para agendamentos complexos
- **Por que aprender:** Automatize tarefas repetitivas sem intervençêo manual (relatórios, backups, sincronizações)
- **Conceitos chave:** Intervalos fixos, expressões CRON, timezone, polling schedule

### Configuraçêo de Timezone
- **O que é:** Definir o fuso horário correto para garantir execuções no horário local desejado
- **Por que aprender:** Evitar execuções em horários errados, especialmente em equipes globais ou servidores em outras regiões
- **Conceitos chave:** UTC, GMT, timezone local, horário de verêo

### Modos de Execuçêo
- **O que é:** Escolher entre intervalos fixos ou expressões CRON para maior flexibilidade
- **Por que aprender:** CRON permite padrões complexos (apenas dias úteis, horários específicos, etc.)
- **Conceitos chave:** Cron syntax, interval mode, schedule mode

---

## 🚀 Próximos Passos

1. Pratique criando agendamentos simples (a cada hora)
2. Aprenda sintaxe CRON básica
3. Configure timezone corretamente
4. Teste diferentes padrões de agendamento
5. Combine com outros nodes para automações completas

---

**Categoria:** Trigger
**Dificuldade:** Iniciante
**Curso:** N8N Fundamentos - 17 Nodes Essenciais

---

© 2025 N8N Academy - Fundamentos Completos
Baseado em "Master n8n with 17 Nodes" por Nate Herk
