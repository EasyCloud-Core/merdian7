# 🚀 **Domingo_02_Programação Completa - Hackathon Marvel: Missão Invoice_MORRO_MAKERS_RUST**  
*(Dia Intenso de Rust, Faturas e Super-Heróis)*  

---

## 📅 **Cronograma Detalhado (9h às 18h)**  

### **🌅 MANHÃ: PREPARAÇÃO E PLANEJAMENTO**  
**9h00 - 9h30** 🎤 **Abertura Épica**  
- Boas-vindas da S.H.I.E.L.D. (Nick Fury virtual)  
- Explicação do desafio (baseado no PDF)  
- Apresentação dos Squads (2-5 pessoas)  

**9h30 - 10h30** 🔍 **Análise Técnica do Problema**  
- Leitura guiada do PDF + identificação de desafios  
- Divisão de módulos por squad:  
  - **Parsing de PDF**  
  - **Armazenamento**  
  - **Geração de CSV**  
  - **Interface (CLI/GUI)**  

**10h30 - 10h45** ☕ **Coffee Break (Estilo Stark Lounge)**  

**10h45 - 12h00** 🦀 **Treino Relâmpago de Rust**  
- Foco nas partes que **vão doer**:  
  - `Result` e `Error` handling  
  - `Structs` e `Enums` para modelagem de dados  
  - `Serde` para JSON/CSV  

---

### **🌇 TARDE: MÃO NA MASSA**  
**12h00 - 13h00** 🍔 **Almoço (Com Debate Nerd)**  
*Tema: "Como o Homem-Formiga debuga código multithread?"*  

**13h00 - 15h00** ⌨️ **Coding Sprint #1**  
- Squads trabalham em seus módulos  
- **Checkpoints a cada 45min** (standups estilo relatório da Maria Hill)  

**15h00 - 15h15** 🧃 **Pausa para Recarregar (Traga seu Vibranium)**  

**15h15 - 17h00** 🔗 **Coding Sprint #2 + Integração**  
- Squads começam a integrar os módulos  
- Testes do fluxo completo: **PDF → Dados → CSV**  

---

### **🌃 NOITE: DEMO + PITCH BATTLE**  
**17h00 - 17h45** 🎤 **Demo dos Squads**  
- Cada squad mostra:  
  - 1 coisa que funciona  
  - 1 erro épico  
  - 1 hack criativo  

**17h45 - 18h00** 🎤⚡ **Pitch Battle (Estilo Rap Battle)**  
- Cada squad tem **1 minuto** para soltar um punchline técnico rimado  
- **Temas obrigatórios:**  
  ```rust
  // Exemplo de punchline:
  "Meu parser é tão rápido que nem o Flash alcança,
  processo invoices em O(1) enquanto você usa O(n²) na raça!"
  ```  
- **Votação por aplausômetro**  

**18h00 - 18h15** 🏆 **Premiação**  
- Categorias:  
  - **"Melhor Uso de Pattern Matching"** (Prêmio Visão)  
  - **"Código Mais Performático"** (Prêmio Pantera Negra)  
  - **"Melhor Flow no Pitch Battle"** (Prêmio Homem de Ferro)  

---

## 📝 **Checklist de Preparação**  
- [ ] **Instalação do Rust**: `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`  
- [ ] **Crates Úteis**: `serde`, `thiserror`, `nom`, `sled`, `clap`  
- [ ] **Editor Configurado**: VS Code + Rust Analyzer ou JetBrains CLion  
- [ ] **Materiais Opcionais**:  
  - [Livro Oficial de Rust](https://doc.rust-lang.org/book/)  
  - [Rust by Example](https://doc.rust-lang.org/rust-by-example/)  

---

## 📂 **Estrutura do Projeto (Exemplo)**  
```bash
invoice_cruncher/  
├── Cargo.toml  
├── src/  
│   ├── main.rs          # Ponto de entrada  
│   ├── parser.rs        # Time Capitão América  
│   ├── database.rs      # Time Viúva Negra  
│   ├── csv_generator.rs # Time Homem de Ferro  
│   └── cli.rs           # Time Hulk  
└── assets/              # PDFs de teste  
```

---

