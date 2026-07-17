# 🕐 Relógio Digital com Múltiplos Fusos Horários

Um relógio digital interativo e inteligente que exibe a hora em diferentes fusos horários ao redor do mundo, com análise IA integrada!

---

## ✨ Características

🕐 **Relógios Digitais em Tempo Real**
- Display em formato 24h
- Atualização a cada segundo
- Design moderno e responsivo

🌍 **Suporte a 20+ Fusos Horários**
- São Paulo 🇧🇷
- Nova York 🗽
- Londres 🇬🇧
- Paris 🇫🇷
- Tóquio 🇯🇵
- E muitos mais!

🤖 **Análise Inteligente com IA**
- Identifica período do dia (manhã, tarde, noite, madrugada)
- Sugestões personalizadas baseadas na hora
- Recomendações de atividades
- Análise em tempo real

📱 **Design Responsivo**
- Funciona em desktop, tablet e mobile
- Interface intuitiva
- Animações suaves

---

## 🚀 Como Usar

### 1. Abrir a Aplicação
Abra o arquivo `index.html` em um navegador web moderno.

### 2. Adicionar um Relógio
- Clique no botão **"+ Adicionar Relógio"**
- Selecione um fuso horário na lista
- Ou use a busca para filtrar

### 3. Visualizar Informações
Cada relógio mostra:
- ⏰ Hora digital (HH:MM:SS)
- 📅 Data completa
- 🗓️ Dia da semana
- 🌅 Período do dia (Manhã, Tarde, Noite, Madrugada)
- 🤖 Análise IA personalizada
- UTC Offset (diferença do horário UTC)

### 4. Gerenciar Relógios
- Clique no **✕** para remover um relógio
- Use **"↻ Resetar"** para limpar todos

---

## 🎨 Interface

```
┌─────────────────────────────────────────┐
│         🕐 Relógio Digital              │
│   Hora em Diferentes Fusos Horários     │
├─────────────────────────────────────────┤
│  [+ Adicionar Relógio]  [↻ Resetar]    │
├─────────────────────────────────────────┤
│
│  ┌─────────────────┐  ┌─────────────────┐
│  │ 🇧🇷 São Paulo   │  │ 🗽 Nova York    │
│  │ UTC -03:00      │  │ UTC -05:00      │
│  │   14:30:45      │  │   09:30:45      │
│  │                 │  │                 │
│  │ 📅 17 de julho  │  │ 📅 17 de julho  │
│  │ Quinta-feira    │  │ Quinta-feira    │
│  │ Período: Tarde  │  │ Período: Manhã  │
│  │                 │  │                 │
│  │ 🤖 Boa tarde!   │  │ 🤖 Bom dia! É  │
│  │ São 14h. Máx    │  │ 9h da manhã...  │
│  │ produtividade! 💪│  │                 │
│  │ [✕]            │  │ [✕]            │
│  └─────────────────┘  └─────────────────┘
│
└─────────────────────────────────────────┘
```

---

## 💻 Tecnologias Utilizadas

- **HTML5** - Estrutura
- **CSS3** - Estilos responsivos e animações
- **JavaScript Vanilla** - Lógica e IA
- **Intl API** - Formatação de datas e horários internacionais

---

## 🔧 Instalação

### Método 1: Arquivo Local
1. Baixe os arquivos (`index.html`, `styles.css`, `script.js`)
2. Coloque-os na mesma pasta
3. Abra `index.html` em um navegador

### Método 2: GitHub
```bash
git clone https://github.com/jjaquelinepereira1982-alt/hbc-studios-ia.git
cd hbc-studios-ia/digital-clock
# Abra index.html em um navegador
```

### Método 3: Servidor Local (Node.js)
```bash
# Instale http-server globalmente
npm install -g http-server

# Na pasta do projeto
http-server digital-clock

# Acesse http://localhost:8080
```

---

## 📊 Fusos Horários Suportados

| Cidade | Fuso Horário | UTC | Emoji |
|--------|-------------|-----|-------|
| São Paulo | America/Sao_Paulo | -03:00 | 🇧🇷 |
| Nova York | America/New_York | -05:00 | 🗽 |
| Chicago | America/Chicago | -06:00 | 🌆 |
| Los Angeles | America/Los_Angeles | -08:00 | 🌴 |
| Londres | Europe/London | +00:00 | 🇬🇧 |
| Paris | Europe/Paris | +01:00 | 🇫🇷 |
| Berlim | Europe/Berlin | +01:00 | 🇩🇪 |
| Amsterdã | Europe/Amsterdam | +01:00 | 🇳🇱 |
| Istambul | Europe/Istanbul | +03:00 | 🇹🇷 |
| Moscou | Europe/Moscow | +03:00 | 🇷🇺 |
| Dubai | Asia/Dubai | +04:00 | 🇦🇪 |
| Índia | Asia/Kolkata | +05:30 | 🇮🇳 |
| Bangkok | Asia/Bangkok | +07:00 | 🇹🇭 |
| Singapura | Asia/Singapore | +08:00 | 🇸🇬 |
| Hong Kong | Asia/Hong_Kong | +08:00 | 🇭🇰 |
| Tóquio | Asia/Tokyo | +09:00 | 🇯🇵 |
| Sydney | Australia/Sydney | +10:00 | 🇦🇺 |
| Cidade do Cabo | Africa/Johannesburg | +02:00 | 🇿🇦 |

---

## 🤖 Análise IA

A IA analisa a hora e oferece recomendações contextuais:

### 🌅 Manhã (5h - 12h)
> "🌅 Bom dia! É Xh da manhã. Ótimo momento para reuniões ou trabalho criativo."

### 🍽️ Almoço (12h - 14h)
> "🍽️ Hora do almoço! São Xh. Que tal fazer uma pausa para comer?"

### ☀️ Tarde (14h - 18h)
> "☀️ Boa tarde! São Xh. Produtividade no pico! 💪"

### 🌅 Noite (18h - 22h)
> "🌅 Boa noite! São Xh. Tempo de relaxar e descansar."

### 🌙 Madrugada (22h - 5h)
> "🌙 Madrugada! São Xh. Repouso é importante! 😴"

---

## 🎯 Casos de Uso

✅ **Coordenação Internacional**
- Agendar reuniões com equipes em diferentes fusos
- Entender melhor compatibilidade de horários

✅ **Planejamento de Viagens**
- Saber a hora em diferentes destinos
- Planejar chegadas e saídas

✅ **Trabalho Remoto**
- Coordenar com colegas globais
- Respeitar horários de descanso

✅ **Educação**
- Aprender sobre fusos horários
- Entender distribuição geográfica

---

## 🐛 Troubleshooting

### O relógio não atualiza?
- Certifique-se de que JavaScript está ativado
- Recarregue a página (F5)
- Tente em outro navegador

### Fuso horário errado?
- Verifique a configuração de data/hora do seu sistema
- O navegador usa a hora do sistema operacional

### Modal não fecha?
- Clique no X ou fora da modal
- Verifique console (F12) para erros

---

## 🚀 Desenvolvimento Futuro

- [ ] Integração com API de IA (GPT-4, Claude)
- [ ] Modo escuro/claro
- [ ] Salvar preferências em localStorage
- [ ] Alarmes e notificações
- [ ] Sincronização com Google Calendar
- [ ] Aplicativo mobile (React Native)
- [ ] Integração com Slack/Teams

---

## 📝 Estrutura dos Arquivos

```
digital-clock/
├── index.html      # Estrutura HTML
├── styles.css      # Estilos e animações
├── script.js       # Lógica JavaScript e IA
└── README.md       # Este arquivo
```

---

## 💡 Dicas

1. **Adicione seus fusos horários preferidos** para monitoramento rápido
2. **Use a busca** para encontrar fusos específicos rapidamente
3. **Observe o período do dia** para comunicação mais eficiente
4. **Sincronize reuniões** consultando múltiplos relógios

---

## 🤝 Contribuindo

Quer melhorar este projeto? Abra uma issue ou pull request no [repositório principal](https://github.com/jjaquelinepereira1982-alt/hbc-studios-ia)!

---

## 📄 Licença

MIT License - Veja [LICENSE](../LICENSE)

---

## 📞 Suporte

- GitHub Issues: [Abrir Issue](https://github.com/jjaquelinepereira1982-alt/hbc-studios-ia/issues)
- Email: support@hbcstudios.com
- Discord: [HBC Studios Community](https://discord.gg/hbcstudios)

---

<div align="center">

**Feito com ❤️ por HBC STUDIOS IA**

⭐ Se achou útil, deixe uma estrela no GitHub! ⭐

</div>