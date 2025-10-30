# 🧭 Agenda de Laboratórios

Sistema simples para gerenciar o uso e a organização dos laboratórios.  
Permite registrar turmas, professores, salas e o status de limpeza (5S) de cada dia.  
O objetivo é facilitar o controle semanal de quem utilizou cada laboratório e se o ambiente foi deixado em boas condições.

---

## ⚙️ Como funciona

- O sistema é totalmente online e funciona direto no navegador.  
- Os dados são salvos automaticamente no **Firebase**, sem necessidade de servidor local.  
- A tela principal mostra:
  - Um **calendário** com os dias do mês.  
  - As semanas aparecem coloridas de acordo com o status:
    - 🟥 Vermelho → dia pendente  
    - 🟨 Amarelo → semana pendente  
    - 🟩 Verde → semana com tudo OK  
    - 🔵 Azul → semana selecionada  
  - Um **formulário** para adicionar agendamentos com data, sala, turma, professor e status.  
  - Uma **tabela** com todos os agendamentos do mês.  
  - Um **resumo** com estatísticas de 5S por turma e professor.

---

## 🧑‍💻 Como usar

1. **Acesse o site** (ou abra o arquivo `index.html` no seu navegador).  
2. Na tela inicial, escolha a **sala** que deseja visualizar.  
3. Clique em **Selecionar**.  
4. Use o formulário à esquerda para **adicionar um agendamento**:
   - Escolha o **dia**, a **sala**, a **turma**, o **professor** e o **status (5S)**.  
   - Clique em **Salvar Agendamento**.  
5. O calendário e as tabelas serão atualizados automaticamente.  
6. É possível editar, excluir ou mudar o status direto na tabela.  
7. Use o botão **“Trocar Filtro”** no topo para voltar à seleção de salas.  
8. Na tela de **Gerenciamento**, você pode cadastrar novas salas, turmas e professores.

---

## ☁️ Hospedagem

O sistema pode ser hospedado facilmente no **GitHub Pages**:
1. Envie o projeto para o seu repositório.  
2. Vá em **Settings → Pages**.  
3. Escolha o branch `main` e o diretório `/ (root)`.  
4. Salve — o link será algo como:  
