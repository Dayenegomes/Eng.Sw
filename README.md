## Equipe 04

| Integrante | Mátricula |
|---|---|
| Danton | 202206840011 |
| Dayene | 202306640027 |
| Débora | 202206840031 |
| George | 201906840014 |
| Getúlio | 202106840045 |

## Sistema Gerenciador de Salas 

**Disciplina:** EC01025 — Engenharia de Software  
**Instituição:** Universidade Federal do Pará (UFPA)  
**Repositório:** [https://github.com/Dayenegomes/Eng.Sw](https://github.com/Dayenegomes/Eng.Sw)

## 1. Sobre o projeto

O Sistema Gerenciador de Salas tem como objetivo facilitar o gerenciamento da ocupação e da disponibilidade das salas dos cursos de graduação do ITEC, centralizando informações relacionadas a professores, monitores e coordenadores.

O sistema busca melhorar a organização das salas, facilitar a consulta de informações e auxiliar no acompanhamento de problemas técnicos, como defeitos no ar-condicionado, no datashow e outras ocorrências.

## 2. Problema que o sistema busca resolver

O gerenciamento das salas exige comunicação entre professores, monitores e coordenação. Sem um ambiente centralizado, pode haver dificuldade para acompanhar quais salas estão disponíveis, quais estão ocupadas, quais professores estão utilizando cada espaço e quais apresentam problemas.

O sistema pretende reunir essas informações em um único ambiente, facilitando o acompanhamento da situação das salas e a comunicação entre os envolvidos.

## 3. Objetivos e funcionalidades

O sistema deverá oferecer funcionalidades como:

- **Gerenciamento de salas e setores:** permitir que a coordenação cadastre e edite informações de salas e setores.
- **Alocação de disciplinas:** permitir que a coordenação registre a alocação de disciplinas nas salas conforme o cronograma semestral.
- **Consulta do cronograma:** permitir que professores consultem as salas e os horários das disciplinas.
- **Visualização do status das salas:** permitir que monitores acompanhem a situação das salas sob sua responsabilidade e os professores registrados em cada uma.
- **Registro de professores não alocados:** permitir que o monitor registre um professor em uma sala desocupada, informando o nome do professor, a sala e o horário de início.
- **Registro de problemas técnicos:** permitir que monitores comuniquem problemas encontrados nas salas à coordenação.
- **Acompanhamento de problemas:** permitir que a coordenação consulte os problemas registrados e seu histórico.
- **Gerenciamento de acessos:** disponibilizar acesso por credenciais conforme os papéis dos usuários.

O sistema também prevê funcionalidades relacionadas à rotina dos monitores, como registro de entrada e saída do turno, empréstimo e devolução de kits, fechamento de salas e achados e perdidos.

## 4. Usuários do sistema

| Usuário | Responsabilidade |
|---|---|
| **Coordenador** | Alocar disciplinas, gerenciar salas e setores e acompanhar as informações e os problemas registrados. |
| **Monitor** | Acompanhar as salas do seu setor, registrar ocupações de professores e comunicar problemas. |
| **Professor** | Consultar o cronograma de salas e solicitar uma sala ao monitor quando necessário. |
| **Mantenedor** | Gerenciar aspectos de acesso e configuração, como credenciais e quantidade de monitores. |

## 5. Fluxo único principal

O fluxo principal utilizado nesta versão do projeto é:

**Professor chega ao monitor pedindo uma sala → o monitor verifica no sistema uma sala disponível → cede a sala ao professor → atualiza o sistema.**

Nesse processo, o monitor consulta a disponibilidade da sala e registra a ocupação no sistema. O registro permite atualizar a situação da sala e disponibilizar essa informação aos usuários autorizados.

## 6. Benefícios esperados

- Facilitar a identificação de salas disponíveis e ocupadas.
- Melhorar a organização e o acompanhamento das salas por setor.
- Centralizar informações sobre a ocupação dos espaços.
- Facilitar a comunicação de problemas técnicos à coordenação.
- Reduzir conflitos relacionados à utilização das salas.
- Melhorar o acesso às informações do cronograma.

## 7. Escopo e limitações

O sistema é voltado ao gerenciamento das salas, suas alocações, seus status e registros relacionados à rotina dos monitores.

Não fazem parte do escopo definido para esta versão:

- **Acesso de alunos ao sistema:** os alunos não são usuários previstos para acessar diretamente a aplicação.
- **Identificação automática e em tempo real da presença de professores:** o sistema depende dos registros realizados pelos usuários, como o monitor ao atualizar a ocupação da sala.

## 8. Partes interessadas (stakeholders)

- **Monitores:** utilizam o sistema para acompanhar as salas do setor e registrar informações da rotina.
- **Coordenadores:** acompanham a situação das salas, realizam alocações e gerenciam informações.
- **Professores:** consultam o cronograma e utilizam as salas.
- **Mantenedor:** administra credenciais e configurações de acesso.
- **Alunos:** são afetados pela organização e disponibilidade das salas, mesmo sem utilizar diretamente o sistema.

