<div align="center">

# 📡 Radar Sensorial

**Monitoramento de estímulos sensoriais em locais públicos**

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=flat-square)](https://github.com/brutsabreu/Radar-Sensorial)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)](https://figma.com)
[![License: MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-blue?style=flat-square)](LICENSE)

<br/>

> Ferramenta para consultar e registrar níveis de ruído e movimento em locais públicos,  
> ajudando pessoas neurodivergentes a se preparar antes de sair de casa.

</div>

---

## 🧠 O problema

Muitas pessoas neurodivergentes enfrentam **crises sensoriais** causadas por barulho excessivo, multidões ou estímulos intensos em locais públicos — shoppings, transporte, eventos, restaurantes.

O problema: não existe uma forma simples de saber **como está o ambiente** antes de chegar até ele.

---

## 💡 A solução

O **Radar Sensorial** permite que usuários:

- 🔍 **Consultem** o nível sensorial de um local antes de ir
- 📢 **Registrem alertas** quando um ambiente estiver intenso
- 📊 **Visualizem** indicadores de ruído e movimento em tempo real
- 🗺️ **Tomem decisões** com mais previsibilidade e segurança

**Exemplo de uso:**

→ "O Shopping está barulhento hoje?"  
→ Radar Sensorial: Ruído Alto · Movimento Médio · Atualizado há 5 min

---

## 🖥️ Demonstração

> *Interface em desenvolvimento — prints do Figma disponíveis em breve.*

---

## 🗂️ Estrutura do projeto

radar-sensorial/
├── index.html ← Página principal (Home)
├── style.css ← Estilos globais (cores, cards, badges)
├── script.js ← Lógica da interface (em desenvolvimento)
└── README.md


> A estrutura de pastas será reorganizada na Fase 4 (backend).

---

## 🚀 Roadmap de desenvolvimento

| Fase | Descrição | Status |
|------|-----------|--------|
| 1 — Design | Protótipo no Figma (UI/UX) | ✅ Concluído |
| 2 — Frontend | HTML + CSS estruturado | ✅ Concluído |
| 3 — JavaScript | Interatividade e filtros | ⏳ Em andamento |
| 4 — Backend | API + banco de dados (Supabase) | ⬜ Não iniciado |
| 5 — Deploy | Publicação no Vercel | ⬜ Não iniciado |

---

## 🛠️ Tecnologias

**Fase atual:**

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura semântica |
| CSS3 | Layout e estilos responsivos |
| JavaScript ES6+ | Interatividade e lógica (em breve) |
| Bootstrap 5 | Componentes e grid responsivo |
| Figma | Prototipação de interface |

**Planejado:**

| Tecnologia | Uso |
|------------|-----|
| Supabase | Banco de dados e autenticação |
| PostgreSQL | Banco de dados relacional |
| Vercel | Hospedagem e deploy contínuo |

---

## 🎨 Paleta de cores

| Cor | Uso | Hex |
|-----|-----|-----|
| Roxo escuro | Fundo da página | `#1A1025` |
| Roxo médio | Cards e inputs | `#241535` |
| Roxo borda | Bordas dos elementos | `#3B2550` |
| Branco | Texto principal | `#F1F5F9` |
| Lilás | Texto secundário | `#C4B5D4` |
| Cinza | Texto terciário | `#8B7A9E` |
| Roxo | Acento | `#A78BFA` |
| Verde | Nível baixo | `#22C55E` |
| Amarelo | Nível médio | `#F59E0B` |
| Vermelho | Nível alto | `#EF4444` |

---

## ♿ Acessibilidade

O projeto foi desenvolvido com acessibilidade como prioridade:

- Contraste de cores seguindo o padrão **WCAG AA (4.5:1)**
- Interface otimizada para **mobile-first**
- Linguagem clara e objetiva para diferentes perfis cognitivos
- Indicadores visuais de nível (não dependem apenas de cor)

---

## 🧩 Funcionalidades planejadas

### Fase 1 - Design (✅ Concluído)
- [x] Tela Home no Figma
- [x] Paleta de cores definida
- [x] Tipografia (Inter)
- [x] Componentes (cards, badges, busca)

### Fase 2 - Frontend (✅ Concluído)
- [x] Estrutura HTML da tela Home
- [x] Estilização CSS com variáveis
- [x] Cards com badges de nível
- [x] Campo de busca estilizado
- [x] Responsividade (mobile-first)

### Fase 3 - JavaScript (⏳ Em andamento)
- [ ] Filtrar locais pela busca
- [ ] Clicar nos cards para ver detalhes
- [ ] Atualizar dados em tempo real

### Fase 4 - Backend (⬜ Não iniciado)
- [ ] Banco de dados no Supabase
- [ ] Tabelas: locais, registros, usuários
- [ ] API para consulta e registro

### Fase 5 - Deploy (⬜ Não iniciado)
- [ ] Publicação no Vercel
- [ ] Configuração de domínio

---

## 💻 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/brutsabreu/Radar-Sensorial.git

# Entre na pasta
cd Radar-Sensorial

# Abra com Live Server (VS Code)
# Clique com o botão direito no index.html → Open with Live Server

# Ou abra diretamente no navegador
# Basta dar duplo clique no index.html

🤝 Contribuindo
Contribuições são bem-vindas! Se você tem sugestões, abre uma issue ou um pull request.

📄 Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.

👤 Autora
Feito por Bruna Abreu
https://img.shields.io/badge/GitHub-brutsabreu-181717?style=flat-square&logo=github

<div align="center"> <sub>Construído com propósito. Para quem precisa de mais previsibilidade no mundo.</sub> </div>

