
# Documento de Visão  
## Sistema de Agendamento para Clínica

---

## 1. Objetivo

O objetivo deste sistema é otimizar a gestão da agenda médica, horários e procedimentos clínicos, promovendo maior agilidade, organização e eficiência no funcionamento da clínica. A proposta é oferecer uma solução prática, intuitiva e eficaz, que reduza conflitos de agendamento e aumente a produtividade da equipe.

---

## 2. Escopo

### 2.1 Escopo IN (Funcionalidades Incluídas)

O sistema incluirá as seguintes funcionalidades:

- Controle e organização da agenda médica.
- Cadastro de usuários com perfis distintos (atendente, médico, gestor).
- Visualização e gerenciamento da disponibilidade dos médicos.
- Cadastro e gerenciamento de pacientes.
- Exibição de mensagens de erro claras e objetivas (ex: "horário ocupado", "fora do horário de atendimento").

### 2.2 Escopo OUT (Funcionalidades Excluídas)

As funcionalidades abaixo não serão contempladas nesta versão do sistema:

- Envio de mensagens automáticas (e-mail, SMS, WhatsApp).
- Agendamento remoto por parte dos pacientes (agendamento será realizado apenas internamente).
- Gerenciamento de prontuários eletrônicos.
- Sistema de sugestão automática para conflitos de horários.
- Personalização avançada de mensagens de erro.

---

## 3. Regras de Negócio

- **Conflito de horários não é permitido:** Não será possível agendar duas consultas no mesmo horário com o mesmo profissional.
- **Horário de atendimento personalizado:** Cada profissional poderá definir sua própria janela de atendimento.
- **Duração fixa de consulta:** Cada consulta terá duração padrão de 30 minutos.
- **Agendamento apenas dentro do horário de trabalho:** Consultas só poderão ser marcadas dentro do horário de atendimento definido pelo profissional.
- **Slots exclusivos:** Cada slot de tempo só poderá ser ocupado por uma única consulta.

---

## 4. Premissas

- O horário comercial padrão será das **08h às 18h**, com possibilidade de personalização por profissional.
- O sistema será utilizado exclusivamente pela equipe da clínica, em ambiente interno.
- Todos os dados dos usuários e pacientes serão armazenados de forma segura e acessível apenas aos perfis autorizados.

---

## 5. Stakeholders

| Stakeholder          | Papel no Sistema                                           |
|----------------------|-----------------------------------------------------------|
| **Atendentes**       | Realizam agendamentos, cadastros e controle da agenda.    |
| **Médicos**          | Definem horários disponíveis e realizam os atendimentos. |
| **Pacientes**        | Recebem os atendimentos e podem ser cadastrados no sistema.|
| **Gestor da Clínica**| Supervisiona o uso do sistema e configura parâmetros gerais.|

---

## 6. Considerações Finais

Este sistema visa proporcionar um ambiente organizado, funcional e eficiente, reduzindo erros humanos e otimizando o tempo de todos os envolvidos no processo de agendamento clínico. O foco é garantir uma experiência simples e objetiva para a equipe da clínica.
```

Se quiser, posso te ajudar a salvar isso em um arquivo `.md` também! Quer?
