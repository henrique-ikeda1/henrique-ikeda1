#  ⚡Calculadora de gastos mensais com energia elética

<img alt="Static Badge" src="https://img.shields.io/badge/version-1.0.0-blue">
<img alt="Static Badge" src="https://img.shields.io/badge/Python-3.8%252B-3776AB?logo=python&logoColor=white">
<img alt="Static Badge" src="https://img.shields.io/badge/GitHub-Reposit%C3%B3rio-181717?logo=github&logoColor=white">
<img alt="Static Badge" src="https://img.shields.io/badge/Energia-C%C3%A1lculo%2520El%C3%A9trico-FFD700?logo=flash&logoColor=black">
<img alt="Static Badge" src="https://img.shields.io/badge/status-Conclu%C3%ADdo-brightgreen">

📖 Objetivo do Sistema
<!-- PREENCHER: Descreva de forma clara e resumida qual é a finalidade do seu programa. -->
Exemplo: Este programa tem como objetivo calcular o gasto médio mensal de energia elétrica de aparelhos domésticos, ajudando o usuário a identificar quais equipamentos mais impactam na conta de luz e a tomar decisões para economizar energia.

🛠️ Tecnologias Utilizadas
Linguagem: Python 3.8+

Bibliotecas: (Se usou alguma, ex: math, datetime. Se não, escreva "Nenhuma, apenas Python padrão".)

Versionamento: Git e GitHub

🧮 Fórmula Utilizada para o Cálculo
<!-- PREENCHER: Explique a fórmula matemática que o programa usa. -->
Exemplo:
O cálculo do consumo mensal é baseado na seguinte fórmula:

Consumo (kWh)
=
Pot
e
ˆ
ncia (W)
×
Horas por dia
×
Dias por m
e
ˆ
s
1000
Consumo (kWh)= 
1000
Pot 
e
ˆ
 ncia (W)×Horas por dia×Dias por m 
e
ˆ
 s
​
 
E o custo final em reais é:

Custo (R$)
=
Consumo (kWh)
×
Valor do kWh (R$)
Custo (R$)=Consumo (kWh)×Valor do kWh (R$)
(Substitua pela fórmula exata que você usou no seu código)

💻 Como Executar o Programa
<!-- PREENCHER: Crie um passo a passo claro para que qualquer pessoa consiga rodar seu programa. -->
Pré-requisitos:

Ter o Python instalado (versão 3.8 ou superior).

(Opcional) Ter o pip para instalar dependências.

Passos para executar:

Clone este repositório:

bash
git clone [URL_DO_SEU_REPOSITORIO]
Acesse a pasta do projeto:

bash
cd [NOME_DA_PASTA]
(Se houver dependências) Instale as bibliotecas necessárias:

bash
pip install -r requirements.txt
(Se não houver, apague esta linha)

Execute o programa principal:

bash
python [NOME_DO_ARQUIVO_PRINCIPAL].py
Siga as instruções exibidas no terminal para inserir os dados dos aparelhos.

📂 Estrutura do Projeto (Opcional)
<!-- PREENCHER se quiser mostrar a árvore de pastas -->
text
.
├── [main.py]          # Arquivo principal
├── [utils.py]         # Funções auxiliares (se houver)
└── README.md
🧪 Exemplo de Uso (Opcional)
<!-- PREENCHER: Mostre um exemplo prático de entrada e saída do programa. -->
Entrada do usuário:

Aparelho: Ar-condicionado

Potência: 1500 W

Horas/dia: 8

Dias/mês: 30

Valor do kWh: R$ 0,85

Saída do programa:

text
Consumo mensal: 360.00 kWh
Custo estimado: R$ 306.00
