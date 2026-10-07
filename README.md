# 🌐 Site Dois Blazor - Prática de Interatividade e Navegação

Este repositório contém a entrega da lista de exercícios práticos de **Blazor Nível 2**, desenvolvida para a disciplina de Usabilidade, Dev. Web, Mobile e Jogos, sob a orientação do Professor Daniel Henrique Matos de Paiva[cite: 24].

## 📝 Sobre o Projeto
O projeto é uma aplicação web interativa desenvolvida em **.NET Blazor**[cite: 24]. A aplicação explora a leitura e manipulação de formulários (`@bind`), validações condicionais e o uso de bibliotecas nativas do C# integradas com a navegação através de componentes `<NavLink>`[cite: 24, 25, 26, 27]. Todas as novas páginas interativas utilizam a diretiva `@rendermode InteractiveServer`[cite: 24].

## ⚙️ Funcionalidades Desenvolvidas
1. **Conversor de Temperatura (`/conversor`):** Recebe um valor em graus Celsius e converte para Fahrenheit utilizando a fórmula matemática correspondente[cite: 24, 25].
2. **Calculadora de Média (`/media`):** Recebe duas notas, calcula a média aritmética e informa se o aluno está "Aprovado!" (média >= 7.0, a verde) ou "Reprovado!" (a vermelho)[cite: 25, 26].
3. **Sorteador de Números (`/sorteio`):** Utiliza a classe `System.Random` nativa do C# para gerar e exibir um número aleatório entre 1 e 100[cite: 26].
4. **Navegação Dinâmica (`NavMenu.razor`):** Menu lateral da aplicação atualizado para incluir o acesso direto às três novas rotas desenvolvidas[cite: 26, 27].

## 🚀 Como Executar
Certifique-se de que tem o **.NET SDK** instalado na sua máquina. Abra o terminal na pasta principal do projeto e execute o comando de observação:

```bash
dotnet watch
