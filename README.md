# Global Solution - Soluções em Energias Renováveis e Sustentáveis (2025)

**Projeto:** Sistema de Iluminação Inteligente com ESP32 e Sensor PIR
**Curso:** Ciências da Computação - FIAP

## 👨‍💻 Integrantes do Grupo
* **Guilherme Willians de Souza Inácio** - RM565319
* **Kaua da Silva Lazarim** - RM564625
* **Nelson Troccoli Santos Neto** - RM562815

---

## 📝 Descrição do Projeto
Este projeto propõe uma solução IoT simples e eficaz para combater o desperdício de energia em ambientes corporativos. Utilizando um microcontrolador ESP32 e um sensor de presença PIR, simulamos um sistema de automação que aciona a iluminação apenas quando há ocupação no ambiente.

### 🎯 Objetivo
* Detectar presença através de sensor PIR.
* Automatizar o acionamento de luzes (LED) para evitar que permaneçam acesas sem necessidade.
* Promover eficiência energética e sustentabilidade em Smart Offices e edifícios inteligentes.

### 🛠️ Componentes Utilizados (Simulação)
* **ESP32** (Microcontrolador)
* **Sensor PIR** (Detector de movimento)
* **LED + Resistor** (Simulação da lâmpada)

---

## 📊 Dados e Resultados
O sistema foi testado com dados simulados para comprovar a economia de energia. A automação demonstrou uma redução significativa no consumo comparado a um sistema convencional (luz sempre ligada).

### Tabela de Operação Simulada

| Horário | Estado do Sensor (PIR) | Estado da Luz (LED) | Consumo (W) |
| :--- | :--- | :--- | :--- |
| 08:00 | Sem Movimento | OFF | 0 |
| 08:01 | Com Movimento | ON | 8 |
| 08:02 | Com Movimento | ON | 8 |
| 08:03 | Sem Movimento | OFF | 0 |
| ... | ... | ... | ... |
| **08:10** | Com Movimento | ON | 8 |
| **08:11** | Com Movimento | ON | 8 |
| **08:12** | Sem Movimento | OFF | 0 |

### 📈 Estatísticas de Economia
Com base na simulação realizada:
* **Consumo total com automação:** 32 Wh
* **Consumo estimado sem automação:** 96 Wh
* **Economia gerada:** 64 Wh
* **Economia Percentual:** ~66%

---

## 🚀 Como Executar o Projeto
Este projeto foi desenvolvido e simulado na plataforma **Wokwi**.

1.  Acesse o link da simulação: [Link para o Projeto no Wokwi](https://wokwi.com/projects/448015641207195649)
2.  Clique no botão **"Play"** (ícone verde) no centro da tela para iniciar.
3.  **Interaja com o Sensor:** Clique sobre o Sensor PIR e selecione "Simulate Motion" (ou mova o cursor sobre ele, dependendo da configuração) para simular a presença de uma pessoa.
4.  Observe o LED acender ao detectar movimento e apagar após o tempo programado sem presença.

---

## 📂 Estrutura do Repositório
* `README.md`: Documentação do projeto.
* `codigo_fonte/`: Contém o código (C++/Arduino) utilizado no ESP32.
