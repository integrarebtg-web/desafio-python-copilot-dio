# desafio-python-copilot-dio
Projeto desenvolvido para o desafio da DIO sobre uso de IA (GitHub Copilot) para otimização de algoritmos em Python
Resolvendo Códigos em Python com GitHub Copilot 🚀
Este repositório documenta a resolução de desafios de lógica de programação em Python, desenvolvidos como parte da formação na DIO (Digital Innovation One). O objetivo principal foi aplicar conceitos fundamentais da linguagem utilizando o GitHub Copilot como assistente de codificação, visando produtividade e a adoção de boas práticas.

📝 Sobre o Projeto
Ao longo deste desafio, busquei não apenas resolver os problemas propostos, mas refinar a lógica de cada solução. A colaboração com o GitHub Copilot foi fundamental para aprender boas práticas, como o tratamento de exceções (para evitar travamentos) e a utilização de métodos nativos do Python que tornam o código mais performático.
| Desafio | Arquivo | Objetivo | Destaque Técnico |
| :--- | :--- | :--- | :--- |
| **01** | `01_concatenacao.py` | Unir dados do usuário. | Uso de `f-strings`. |
| **02** | `02_repeticao.py` | Repetir strings N vezes. | Uso de `.join()` e List Comprehension. |
| **03** | `03_operacoes.py` | Cálculos básicos (+, -, *, /). | Estrutura `elif` e verificação de divisão por zero. |
| **04** | `04_pares_impares.py` | Verificar paridade de um número. | Loop `while` com `try-except` para validação. |
| **05** | `05_media.py` | Calcular média de notas. | Validação de entrada entre 0 e 10. |
| **06** | `06_palindromos.py` | Verificar palíndromos. | Slicing `[::-1]` para inversão de string. |
🚀 Como executar os códigos
Para testar cada desafio, abra o seu terminal na pasta do projeto e execute o arquivo correspondente utilizando o comando python:

Concatenar Dados: python 01_concatenacao.py

Repetir Textos: python 02_repeticao.py

Operações Matemáticas: python 03_operacoes.py

Pares e Ímpares: python 04_pares_impares.py

Média de Notas: python 05_media.py

Verificar Palíndromos: python 06_palindromos.py

Nota: O readme.md é um arquivo de documentação e não contém código executável.

💡 Aprendizado com GitHub Copilot
O uso de IA transformou a minha forma de codificar. Os principais ganhos foram:

Robustez no Código: Com o auxílio do Copilot, aprendi a implementar blocos try-except. Isso garante que, se o usuário digitar um valor inválido, o programa apresente uma mensagem de erro amigável em vez de travar o sistema.

Refatoração Inteligente: A IA sugeriu substituições de loops manuais por métodos nativos do Python (como o .join() e o slicing), que são mais eficientes e seguem o padrão da linguagem.

Conversão de Dados: O Copilot foi essencial para identificar a necessidade de conversão de tipos (ex: int(input())), evitando erros de tipos incompatíveis durante a execução.

Projeto desenvolvido como parte do desafio técnico da DIO.
