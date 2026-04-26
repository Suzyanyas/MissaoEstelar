# 🚀 MissãoEstelar


<img width="400" height="400" alt="Design sem noeeme" src="https://github.com/user-attachments/assets/fc12e242-7c17-404f-9cf7-bb1e3ed6c94e" />


> App de gestão de tarefas gamificado para crianças, com tema espacial.

MissãoEstelar transforma as tarefas diárias das crianças numa aventura intergaláctica. Cada tarefa concluída vale pontos estelares, desbloqueia recompensas e faz a criança subir no ranking da semana. Pensado especialmente para crianças com TDAH que precisam de motivação visual, feedback imediato e estrutura diária.

---

## ✨ Funcionalidades

### Para as crianças
- **Tarefas diárias** com ícones, pontos, timer e lembrete de horário
- **Pontos estelares** ganhos a cada tarefa concluída
- **Caixa Estelar** — prémio surpresa ao completar todas as tarefas do dia
- **Ranking semanal** entre os irmãos
- **Diário espacial** com seletor de humor (7 emoções)
- **Recompensas** — trocar pontos por prémios definidos pelos pais
- **CÓSMICO** — mascote com IA (Groq/LLaMA) que motiva e celebra conquistas
- **Histórico de 7 dias** — visualização do progresso recente
- **Streak** — contador de dias consecutivos com todas as tarefas feitas

### Para os pais (painel admin)
- Gestão de perfis (foto, emoji, cor, PIN)
- Criação e edição de tarefas (diárias/semanais, horários, pontos)
- Catálogo de recompensas e aprovação de resgates
- Sistema de mesada mensal calculado com base na taxa de conclusão
- Registo de penalizações (dedução de pontos/dinheiro)
- Envio de mensagens às crianças
- Visualização do diário de cada filho
- Histórico de tarefas e estatísticas

### Tecnologia
- Login por PIN ou **reconhecimento facial** (face-api.js)
- **PWA** instalável no telemóvel (ícone, offline, fullscreen)
- Som procedural gerado via **Web Audio API** (sem ficheiros de áudio)
- Voz sintetizada em português via **Web Speech API**

---

## 🛠️ Stack Tecnológica

| Camada | Tecnologia |
|--------|-----------|
| Frontend | HTML + CSS + JavaScript vanilla |
| Base de dados | [Supabase](https://supabase.com) (PostgreSQL) |
| Armazenamento de fotos | Supabase Storage |
| IA do mascote | [Groq API](https://groq.com) (LLaMA 3 70B) |
| Reconhecimento facial | [face-api.js](https://github.com/justadudewhohacks/face-api.js) |
| Deploy | [Netlify](https://netlify.com) (static + serverless functions) |
| Áudio | Web Audio API (procedural) |
| Voz | Web Speech API |

---

## 📁 Estrutura do Projeto

