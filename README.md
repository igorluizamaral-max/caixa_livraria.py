# Criando o arquivo README.md localmente com o conteúdo estruturado para o GitHub do usuário
readme_content = """# 📚 Sistema de Caixa - Livraria Geek (Python)

Este projeto simula o funcionamento do caixa de uma livraria ou espaço cultural. Desenvolvido durante o **Dia 4** da jornada intensiva de aprendizado em Python, o objetivo principal foi dominar o uso de estruturas de repetição aplicadas a cenários do mundo real.

## ⚙️ Funcionamento do Programa
O sistema permite o registro contínuo de mercadorias em uma única venda:
1. O operador insere a **quantidade de livros** do lote atual.
2. Se a quantidade digitada for `0`, o sistema entende que a venda foi concluída e encerra o atendimento.
3. Se a quantidade for maior que zero, o sistema solicita o **preço unitário** do livro.
4. O programa calcula o valor acumulado (`quantidade * preço`) e exibe o subtotal em tempo real com formatação monetária (`R$`).
5. Ao encerrar, o valor total da compra é exibido na tela.

## 🛠️ Conceitos Praticados:
- **Estruturas de Repetição Dinâmicas:** Uso do `while True` para criar loops contínuos de atendimento.
- **Controle de Fluxo Avançado:** Aplicação do comando `break` para interrupção imediata e segura do laço (saída de emergência).
- **Lógica Condicional:** Uso de `if` para validação de encerramento de venda.
- **Operadores de Atribuição Avançada:** Acumulação de valores usando o operador `+=`.
- **Formatação de Dados:** Uso de f-strings com o modificador `:.2f` para exibição correta de casas decimais em valores monetários.

---
*Projeto desenvolvido de forma independente para consolidação de lógica de programação e transição de código estruturado (Portugol) para o ambiente de desenvolvimento profissional (Python).*
"""

