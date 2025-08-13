# DesvioPadrao
DesvioPadrão
📊 Tutorial: Cálculo de Desvio Padrão no Excel
✨ Objetivo
Aprender a usar as funções DESVPAD e DESVPAD.P no Excel para analisar a variação de investimentos de duas pessoas fictícias: Antonelly e Manuella.

📝 Passo 1 — Preparar a Tabela de Dados
Abra o Excel e crie uma planilha com duas tabelas lado a lado:

📌 Tabela 1: Nome da pessoa (Antonelly), coluna de Mês (Jan a Dez), coluna de Investimento.

📌 Tabela 2: Nome da pessoa (Manuella), coluna de Mês (Jan a Dez), coluna de Investimento.

Preencha os valores de investimento mês a mês.
(Ex.: Antonelly: Jan → 120, Fev → 180... | Manuella: Jan → 450, Fev → 100...)

📐 Passo 2 — Cálculo com DESVPAD (Amostra)
O DESVPAD é usado quando você quer calcular o desvio padrão considerando que seus dados são uma amostra de um conjunto maior.

💡 Fórmula:

Copiar
Editar
=DESVPAD(intervalo)
🔹 Exemplo:

Para Antonelly:

makefile
Copiar
Editar
=DESVPAD(C2:C5)
Para Manuella:

makefile
Copiar
Editar
=DESVPAD(F2:F5)
📊 Isso retorna a variação média dos investimentos considerando que os dados representam apenas parte da população.

📏 Passo 3 — Cálculo com DESVPAD.P (População)
O DESVPAD.P é usado quando você quer calcular o desvio padrão considerando que seus dados são a população inteira.

💡 Fórmula:

Copiar
Editar
=DESVPAD.P(intervalo)
🔹 Exemplo:

Para Antonelly:

makefile
Copiar
Editar
=DESVPAD.P(C2:C5)
Para Manuella:

makefile
Copiar
Editar
=DESVPAD.P(F2:F5)
📊 Isso retorna a variação média considerando todos os dados possíveis da população.

🔍 Diferença Entre DESVPAD e DESVPAD.P
DESVPAD → Amostra (divide por n-1).

DESVPAD.P → População (divide por n).

🎯 Passo 4 — Interpretando os Resultados
Um valor de desvio padrão baixo significa que os dados estão próximos da média.

Um valor alto significa que há muita variação entre os valores.

💬 Exemplo prático:
Se o desvio padrão da Antonelly for menor que o da Manuella, significa que os investimentos da Antonelly são mais constantes ao longo dos meses.

✅ Conclusão
Agora você sabe:

Como montar a tabela 📋

Como usar DESVPAD e DESVPAD.P 🧮

Como interpretar o resultado 📊
