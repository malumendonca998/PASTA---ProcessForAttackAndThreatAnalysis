# # 🛡️ Análise de Ameaças com PASTA - Aplicativo de Compra e Venda de Tênis

Este projeto apresenta uma modelagem de ameaças utilizando a metodologia **PASTA (Process for Attack Simulation and Threat Analysis)** aplicada a um cenário realista: o desenvolvimento de um aplicativo para entusiastas e colecionadores de tênis. O objetivo é identificar possíveis ameaças, vulnerabilidades e riscos à segurança da aplicação.

---

## 📌 Cenário

Você faz parte da equipe de segurança de uma empresa de calçados que está lançando um app para dispositivos móveis. Esse app permitirá que os clientes comprem e vendam tênis, além de criar perfis e realizar transações financeiras. Seu papel é realizar a análise de ameaças para garantir que o app seja seguro e esteja em conformidade com as normas.

---

## 🔒 Metodologia Utilizada: PASTA

A estrutura **PASTA** é composta por **7 etapas**, que ajudam a identificar e tratar possíveis ameaças de segurança:

1. **Definir objetivos de negócios e segurança**
2. **Definir o escopo técnico**
3. **Decompor a aplicação**
4. **Analisar ameaças**
5. **Analisar vulnerabilidades**
6. **Modelagem de ataque**
7. **Análise de risco e impacto**

---

## 📝 Etapas Aplicadas

### I. Objetivos de Negócio e Segurança
- Criação de perfis de usuário por login interno ou via redes sociais.
- Processamento de transações financeiras.
- Conformidade com PCI-DSS.

### II. Escopo Técnico
- Tecnologias envolvidas: APIs, PKI, SHA-256, SQL.
- Foco em APIs pela exposição de dados sensíveis e ampla superfície de ataque.

### III. Decomposição da Aplicação
- Diagrama de fluxo de dados (presente no PDF).

### IV. Análise de Ameaças
- Injeção de código (como SQL Injection).
- Sequestro de sessão (Session Hijacking).

### V. Análise de Vulnerabilidades
- Falta de prepared statements.
- Tokens de API comprometidos ou mal configurados.

### VI. Modelagem de Ataque
- Árvore de ameaças representando caminhos potenciais de exploração (presente no PDF).

### VII. Análise de Risco e Impacto
- Uso de boas práticas como hashing com SHA-256, política de senhas, princípio do menor privilégio e plano de resposta a incidentes.

---

## 📄 Documento Completo

Para ver todos os detalhes da análise, você pode acessar o documento completo em PDF:

📎 [PASTA - Process for Attack Simulation and Threat Analysis.pdf](https://github.com/malumendonca998/PASTA---ProcessForAttackAndThreatAnalysis/blob/c872bcfb141e9a1a4a4e95b8b0da05d782a93ae1/PASTA%20-%20Process%20for%20Attack%20Simulation%20and%20Threat%20Analysis.pdf.pdf)

---

## 💡 Conclusão

Este projeto demonstra como aplicar a metodologia PASTA na prática, fornecendo uma visão clara sobre os riscos e medidas de segurança para aplicações modernas. É uma excelente ferramenta para qualquer profissional ou estudante que deseja se aprofundar na área de segurança da informação.

---

## 📬 Contato

Caso queira trocar uma ideia sobre segurança, tecnologia ou colaborações:

**Maria Luiza**  
🔗https://www.linkedin.com/in/maria-luiza-mendon%C3%A7a-7839a71ba/  
📧 Luizqmorais94@gmail.com
