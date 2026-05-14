# 🚌 Bus Occurrence Generator

Sistema web desenvolvido para auxiliar operadores de transporte coletivo na geração rápida de ocorrências operacionais.

## 📌 Objetivo

O projeto foi criado para automatizar processos repetitivos no ambiente operacional, reduzindo o tempo de preenchimento manual de ocorrências e padronizando informações importantes.

---

## ⚙️ Funcionalidades

### ✅ Intervalo Prolongado
- Cálculo automático de intervalo
- Validação de limite operacional
- Geração automática do texto da ocorrência

### ✅ Coletivo Realocado
- Registro de realocação de veículos
- Informações operacionais completas

### ✅ Perda de Partida
- Registro rápido de partidas perdidas
- Geração automática de relatório

### ✅ Coletivo Avariado
- Cadastro de avarias
- Dados de motorista e cobrador

### ✅ S.O.S Operacional
- Controle de atendimento mecânico
- Registro de chegada e observações

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript Vanilla

---

## 💡 Diferenciais

- Interface moderna e responsiva
- Sistema leve e rápido
- Funciona diretamente no navegador
- Não necessita instalação
- Automatiza processos repetitivos operacionais

---

## 🚀 Como executar

1. Faça o download do projeto
2. Abra o arquivo `index.html`
3. Utilize diretamente no navegador

---

## 📷 Interface do Sistema

O sistema possui interface intuitiva com abas separadas para cada tipo de ocorrência operacional.

---

## 🎯 Aplicação prática

Este sistema foi desenvolvido com foco em operações de transporte coletivo urbano, auxiliando controladores operacionais, monitoramento e equipes de gestão.

---

## 👨‍💻 Autor

Francisco José

Estudante de Análise e Desenvolvimento de Sistemas  
Profissional com experiência em operações e monitoramento.

---

## 📄 Licença

Projeto para fins educacionais e de automação operacional.

Por motivo de Confidêncialidade, foi usado nomes fictícios para fins acadêmicos.
Para Alterar os nomes, é preciso editar o index.html no bloco de notas seção Arrys encarregados conforme o print abaixo.
<img width="1107" height="611" alt="image" src="https://github.com/user-attachments/assets/f6236835-2005-4c11-9c98-e283699317a7" />

O mesmo vale para as linhas para auto preenchimento
<img width="736" height="605" alt="image" src="https://github.com/user-attachments/assets/74285d77-6df3-46fc-b0ec-8925d1eed4c0" />

[16:49, 14/05/2026] Franco: Funcionalidades Principais nas atulizações

| Aba | Função |
|-----|--------|
| *⏱️ Intervalo* | Calcula se o intervalo entre partidas está dentro do limite permitido (frequência ×2 +1) e gera ocorrência se ultrapassado |
| *🔄 Realocado* | Registra quando um coletivo é realocado para outra linha |
| *❌ Perca Partida* | Documenta perda de horário de partida |
| *🔧 Avaria* | Registra veículos avariados e acionamento do S.O.S |

 Principais Campos
- Dados da linha (nome, prefixos, horários)
- Responsáveis (ET/OTU, COP, Operacional)
- Frequência da linha (10/15/20 min ou personalizada)
- Motivo da ocorrência
- Informações de S.O.S (mecânico, placa, etc.)

Diferenciais implementadas
- ✅ *Autocomplete* para linhas e prefixos
- ✅ *Validação* de campos obrigatórios
- ✅ *Cálculo automático* de intervalos e limites
- ✅ *Geração de texto* formatado da ocorrência
- ✅ *Cópia* (texto/HTML) para registro
- ✅ *Design responsivo* para mobile
- ✅ *Tabela de referência* com limites por frequência
 
Público-alvo
Gestores operacionais, fiscais de transporte, equipes de controle de frota e departamento de ocorrências.
[16:49, 14/05/2026] Franco: Auto Preenchimento de linhas apenas para o  Terminal Grajaú, updates futuros para outros terminais.
