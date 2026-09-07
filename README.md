⚡ Calculadora de Consumo Elétrico






📌 Sobre o projeto

A Calculadora de Consumo Elétrico é um programa desenvolvido em Python que permite estimar o consumo mensal de energia elétrica de um aparelho.

O usuário informa o nome do aparelho, sua potência em watts e a quantidade média de horas de uso por dia. O programa calcula o consumo estimado em kWh por mês e também apresenta uma estimativa do custo mensal.

🎯 Objetivo

O objetivo do projeto é ajudar o usuário a compreender melhor o consumo de energia elétrica dos aparelhos e ter uma estimativa de quanto eles podem representar na conta de luz.

💻 Tecnologias utilizadas
🐍 Python
🐙 GitHub
⚡ Energia elétrica
🧮 Fórmula utilizada

O consumo mensal é calculado através da fórmula:

consumoMensal = (potencia × horasDia × 30) / 1000

O custo estimado é calculado considerando o valor de R$ 0,75 por kWh:

custoMensal = consumoMensal × 0,75
▶️ Como executar
Abra a pasta do projeto no VS Code.
Abra o terminal do VS Code.
Execute:
python app.py
Informe os dados solicitados.
Confira o consumo e o custo estimados.
📂 Estrutura do projeto
consumo-energia/
├── app.py
└── README.md
⚡ Exemplo
Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
Custo estimado: R$ 33.75 por mês
👨‍💻 Projeto

Projeto desenvolvido como atividade de iniciação em tecnologia, com o objetivo de praticar algoritmos, programação estruturada, Python, Git e GitHub.