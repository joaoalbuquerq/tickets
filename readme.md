# Tickets 🎟️

### Sistema para Gerenciamento de Senhas 🏥

O **Tickets** é uma aplicação criada para gerenciar a emissão, controle de chamadas e relatórios de senhas em ambientes de atendimento como clínicas, laboratórios e repartições! 💰

---

## Requisitos para Funcionamento 🛠️

Antes de rodar o projeto, você precisa ter instalado:

- **Git** 💾 (para clonar o repositório)
- **NodeJS** 🧵 (para gerenciar dependências)
- **Ionic CLI** 🕹️ (para executar o projeto)

---

## Como Executar o Projeto 🌍🔄

Siga os passos abaixo para colocar o projeto no ar:

1. **Clone o repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

2. **Entre na pasta do projeto**:
   ```bash
   cd nome-da-pasta-clonada
   ```

3. **Instale as dependências**:
   ```bash
   npm install
   ```

4. **Rode o servidor de desenvolvimento**:
   ```bash
   ionic serve
   ```

5. **Acesse o sistema no navegador**:
   
   🔗 [http://localhost:8100](http://localhost:8100)

---

## Funcionalidades Principais 📈

### 📅 Emissão de Senhas

- Gere diferentes tipos de senhas conforme a necessidade do atendimento:
  - **SP** - Senha Prioritária 🔍
  - **SG** - Senha Geral 🌐
  - **SE** - Senha para Retirada de Exames 📉

### 🔁 Chamada de Senhas

- O sistema segue uma ordem inteligente para chamada de senhas:

```
[SP] -> [SE|SG] -> [SP] -> [SE|SG]
```

- Alterna de forma a priorizar senhas especiais sem esquecer as gerais e exames! 👌

### ⏳ Priorizacão de Atendimento

- Garantimos que quem precisa de atendimento prioritário não fique esperando desnecessariamente! ❤️

### 📊 Relatórios Detalhados

- Gere relatórios completos para análise e auditoria! 📄

O relatório contém:

- ✅ Quantitativo geral de senhas emitidas
- ✅ Quantitativo geral de senhas atendidas
- ✅ Quantitativo por tipo de senha (SP, SG, SE)
- ✅ Listagem detalhada:
  - Numeração da senha
  - Tipo de senha
  - Data e hora da emissão
  - Data e hora do atendimento
  - Guichê que realizou o atendimento (se aplicável)
- ✅ Tempo Médio (TM) de atendimento, considerando variações!

---

## Observações Importantes ℹ️

- Caso não tenha o **Ionic CLI** instalado, instale com:

  ```bash
  npm install -g @ionic/cli
  ```

- Este projeto é focado para fins educativos, melhorias em atendimento e organização de fluxo! 🌟

---

## Licença 📜

Este projeto está licenciado sob a **Creative Commons License**. Para mais detalhes, consulte o arquivo [LICENSE](./LICENSE). 📚

Projeto livre para estudos, melhorias e adaptações! 🚀

