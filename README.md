# 🚀 Desafio em 3 Fases
Este projeto foi desenvolvido para testar e aprimorar suas habilidades em **Front-end**, **Back-end** e **Banco de Dados**.  
Você irá passar por **3 fases** de desenvolvimento, cada uma com objetivos claros e entregáveis definidos.

---

## 📚 Estrutura do Desafio

### 🔹 Fase 1: Front-end (Clonando uma Interface)
**Objetivo:**  
Reproduzir fielmente uma das interfaces disponibilizadas no **Figma**.

**Tarefas do aluno:**  
1. Escolher **uma das 3 interfaces** fornecidas.  
2. Criar uma página responsiva utilizando HTML, CSS e JavaScript (ou framework de sua preferência).  
3. Garantir que o design esteja o mais fiel possível ao modelo.  
4. Entregar o código em uma pasta específica e opcionalmente hospedar a página.  

**Links dos Protótipos no Figma:**  
1. [Interface 1](https://www.figma.com/community/file/1256871498988476466)  
2. [Interface 2](https://www.figma.com/community/file/1095066785418230052)  
3. [Interface 3](https://www.figma.com/community/file/949649489048687729)  

⚠️ **Atenção:** Para acessar os arquivos, o aluno deverá se **cadastrar gratuitamente no Figma Community**.  

---

### 🔹 Fase 2: Back-end (Desafios no HackerRank)
**Objetivo:**  
Demonstrar sua capacidade de resolução de problemas e lógica de programação.  

**Tarefas do aluno:**  
Resolver **DOIS DESAFIOS** no HackerRank:  
1. [Python: Arithmetic Operators](https://www.hackerrank.com/challenges/python-arithmetic-operators/problem?isFullScreen=true)  
   - Descrição: Operações básicas (soma, subtração e multiplicação) com entrada de dados.  
   - Linguagem sugerida: **Python 3**  

2. [Java: Welcome to Java!](https://www.hackerrank.com/challenges/welcome-to-java/problem?isFullScreen=true)  
   - Descrição: Imprima uma mensagem simples de boas-vindas utilizando Java.  
   - Linguagem sugerida: **Java**  

**Entrega:**  
- Código-fonte de cada desafio em pastas separadas.  
- Link do perfil ou prints mostrando a submissão concluída no HackerRank.  

---

### 🔹 Fase 3: Banco de Dados (Modelagem Física)

**Objetivo:**  
Modelar e implementar o banco de dados da Clínica Veterinária **VetSys** a partir do minimundo abaixo.  

#### 📖 Minimundo

Uma clínica veterinária realiza atendimentos para diversos animais domésticos, como cães, gatos e aves.  
- Cada **animal** é cadastrado com: nome, espécie, raça, idade.  
- Cada animal está associado a um **dono**.  
- Os **donos** são identificados com: nome completo, CPF, endereço e telefone.  
- Um dono pode ter **mais de um animal** cadastrado na clínica.  
- As **consultas** são agendadas com: data, horário, o animal a ser atendido e o veterinário responsável.  
- Os **veterinários** são cadastrados com: nome, CRMV, especialização.  
- Após a revisão dos requisitos, foi identificado que:  
  - Um veterinário pode possuir **várias especializações** (ex.: cirurgia, dermatologia, ortopedia, clínica geral).  
  - Uma especialização pode ser atribuída a **vários veterinários**.  
  - Assim, a informação de especialização foi modelada como uma **nova entidade** chamada `especializacoes`, com atributos `id_especializacao` e `nome_especializacao`.

---

#### 🛠️ Tarefa do Aluno
1. Criar o **modelo físico** (código SQL) do banco de dados VetSys:  
   - Criar tabelas e seus atributos.  
   - Definir **chaves primárias e estrangeiras**.  
   - Definir relacionamentos:  
     - Dono ↔ Animal (1:N)  
     - Veterinário ↔ Consulta (1:N)  
     - Animal ↔ Consulta (1:N)  
     - Veterinário ↔ Especialização (N:N)  
   - Criar a tabela intermediária para o relacionamento N:N.  
2. Entregar um **script SQL** (`vetsys.sql`) que:  
   - Crie todas as tabelas com as constraints adequadas.  
   - Defina tipos de dados adequados para cada atributo.  
3. Adicionar um **README.md** na pasta `fase-3-banco-de-dados/` explicando suas escolhas de modelagem.



