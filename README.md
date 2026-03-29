# 🐾 Petshop do Marquinhos - Projeto Fase 2

Bem-vindo ao repositório do **Petshop do Marquinhos**! Projeto desenvolvido por **Francisco Quaresma** para a disciplina de Fundamentos de Sistemas Web.

## 🎯 Objetivo da Fase 2
Nesta segunda etapa, o sistema web estático foi aprimorado para se tornar uma plataforma interativa, dinâmica e acessível, cumprindo rigorosamente os requisitos das Aulas 6 a 10 da disciplina.

## ⚙️ Ajustes e Novas Funcionalidades
Os seguintes ajustes foram realizados no código-fonte em relação à Fase 1:

1. **Uso de CSS e Bootstrap:** Integração do framework Bootstrap para garantir a responsividade do layout e a implementação de um **Carrossel de Imagens** dinâmico na página inicial. Personalização avançada da tipografia utilizando o Google Fonts (fonte *Oldenburg*).
2. **Formulários Avançados:** Criação de uma seção completa de "Cadastro e Agendamento". O formulário engloba a identificação do cliente, dados do pet e a escolha do serviço (com ou sem tele-busca). Foram utilizados múltiplos elementos HTML5, como `input` (text, tel, email, number), `radio`, `select`, `checkbox` e o calendário nativo `datetime-local`.
3. **Interatividade com JavaScript:**
   - **Funções Temporais:** Implementação de um relógio em tempo real no rodapé do site, atualizado via `setInterval`.
   - **Manipulação do DOM:** Captura de dados do formulário na submissão (`submit`), travando o recarregamento com `preventDefault()` e exibindo um alerta (pop-up) personalizado com o nome do pet e a data do agendamento.
4. **Acessibilidade Web:** Revisão estrutural para atender aos requisitos de acessibilidade para deficientes visuais, garantindo a audiodescrição detalhada através do atributo `alt` em 100% das imagens utilizadas no sistema.

## 🔗 Acesso ao Projeto
O projeto está hospedado no GitHub Pages e pode ser testado ao vivo no link abaixo:
👉 **https://fpquaresma.github.io/petshop-fase1/**
