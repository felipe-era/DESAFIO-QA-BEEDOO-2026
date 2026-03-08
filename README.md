# DESAFIO-QA-BEEDOO-2026

## 📌 Objetivo da Aplicação

O objetivo da aplicação é permitir o gerenciamento de cursos por meio de um módulo simples de **cadastro e consulta**.  
O sistema possibilita registrar novos cursos e visualizar os cursos já cadastrados em uma listagem, centralizando essas informações em uma interface única.

Dessa forma, a aplicação funciona como uma **ferramenta básica de administração de cursos**, permitindo manter e consultar esses registros de forma organizada.

---

## 🔄 Principais Fluxos Disponíveis

Os principais fluxos disponíveis no sistema são:

### 📚 Cadastro de Cursos
No fluxo de cadastro, o usuário acessa a opção de criação de curso, preenche os campos solicitados e salva as informações para registrar um novo curso no sistema.

### 📋 Listagem de Cursos
No fluxo de listagem, o usuário consegue visualizar os cursos já cadastrados, normalmente apresentados em formato de **lista ou tabela**.

Esses dois fluxos representam as **funcionalidades centrais da aplicação** e concentram as principais interações do usuário com o sistema.

---

## ⚠️ Pontos Mais Críticos para Teste

Os pontos mais críticos para teste estão relacionados principalmente ao **processo de cadastro e à exibição das informações cadastradas**.

### 🧾 Cadastro de Cursos
No cadastro, é fundamental validar:

- Campos obrigatórios
- Formatos de dados aceitos
- Comportamento do sistema ao receber informações inválidas ou incompletas
- Persistência correta dos dados após o cadastro

### 📊 Listagem de Cursos
Na listagem, é importante verificar:

- Se os cursos cadastrados aparecem corretamente
- Se os dados exibidos estão consistentes com o cadastro
- Se a interface permanece estável com diferentes quantidades de registros

Também é necessário validar **comportamentos inesperados**, como:

- Falhas de carregamento de página
- Problemas de navegação entre telas
- Inconsistências entre cadastro e listagem

---

## 🧪 Cenários de Teste e Bugs Encontrados

Todos os **cenários de teste executados** e os **bugs identificados durante a execução** estão documentados na planilha abaixo.

📄 **Planilha de testes:**  
https://docs.google.com/spreadsheets/d/1rpMDeYKkDvcvaePQKoLlKR_PD7gQScRnIrMTqcT0J_A/edit?usp=sharing

⚠️ Observação:  
Os **cenários de teste e os bugs estão no mesmo arquivo**.  
Para visualizar cada um deles, basta **alterar a aba na parte inferior da planilha**.
