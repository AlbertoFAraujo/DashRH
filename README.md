![fundo](https://github.com/AlbertoFAraujo/DashEnade2021/assets/105552990/38711a77-0076-4d26-8a5e-bb9bb9a3fb34)

# 📊DASHBOARD RH

### Tecnologias utilizadas: 
| [<img align="center" alt="Python" height="60" width="60" src="https://api.iconify.design/vscode-icons/file-type-excel.svg">](https://support.microsoft.com/en-us/excel) |
|:---:|
| Excel |
<hr>

### Objetivo:

O objetivo do *dashboard* RH é apresentar o controle de indicadores de uma empresa, baseando em critérios como áreas, tipo de contratos ou por período(ano). Através do painel é possível verificar os indicadores essenciais para controle e tomadas de decisão de uma área de Recursos Humanos, tais quais, quantidades de funcionários por gêneros, cargo, área, faixa salarial, benefícios, entre outros.

**Obs:** Todos os dados são fictícios e gerados aleatoriamente. A ideia da criação desse *dashboard* é explorar recursos de funções matriciais e filtros baseados em controle de células, sem o uso de tabelas dinâmicas, apenas com tabelas comuns auxiliares.
<hr>

### Etapas do projeto:

1. Definição do objetivo da análise e geração da base de valores fictícios;
2. Tratamento dos dados (Limpeza, transformações, formatações, criação de tabelas auxiliares e filtros-chave);
3. Identificação das métricas-alvo e escolha das visualizações gráficas adequadas para cada cenário;
4. Criação do layout e composição de paleta de cores;
5. Teste de qualidade e eficácia do *dashboard* (garantir que todos os gráficos estejam funcionando corretamente e que os dados estejam sendo atualizados).
<hr>

### Tempo de Execução:

O tempo estimado para a execução de todas as etapas é de 1 dia.

### Projeto Final a ser desenvolvido:

![DashRH_print](https://github.com/AlbertoFAraujo/DashRH/assets/105552990/5f63c35c-92ce-4047-a824-601f81c35d59)
<hr>

### Execução das Etapas:

#### 1. Definição do objetivo da análise e geração da base de valores fictícios;

O objetivo do *dashboard* RH é apresentar o controle de indicadores de uma empresa, baseando em critérios como áreas, tipo de contratos ou por período(ano). Através do painel é possível verificar os indicadores essenciais para controle e tomadas de decisão de uma área de Recursos Humanos, tais quais, quantidades de funcionários por gêneros, cargo, área, faixa salarial, benefícios, entre outros.

#### 2. Tratamento dos dados (Limpeza, transformações, formatações, criação de tabelas auxiliares e filtros-chave);
- Foi gerado dados fictícios a partir do chat GPT: [ChatGPT (openai.com)](https://chat.openai.com/auth/login);
- As demais variáveis são intuitivas os nomes, portanto não há necessidade de glossário;
- Houve a necessidade de criar 7 colunas auxiliares para categorização de algumas variáveis, são elas:

    | Variáveis: | Significado: |
    | --- | --- |
    | Tempo Empresa | Extração do período em dias. |
    | Faixa Tempo Empresa | Categorizado a partir dos quartis (1,2,3,4) em dias. |
    | Faixa Salarial | Categorizado a partir dos quartis (1,2,3,4) em reais. |
    | Faixa Idade | Categorizado a partir dos quartis (1,2,3,4) em anos. |
    | Status | Situação do funcionário para casos de ausências, como Licença Maternidade, Desligamento ou outros afastamentos |
    | Ano Contratação | Extração do período em Anos |
    | Ano Desligamento | Extração do período em Anos |
<hr>

#### 3. Identificação das métricas-alvo e escolha das visualizações gráficas adequadas para cada cenário:

Os gráficos foram escolhidos conforme a disposição dos dados das variáveis e que melhor atendem ao objetivo e visualização das informações;
<hr>

#### 4. Criação do layout e composição de paleta de cores:

O layout foi pensando na disposição das informações, como o principal objetivo é obter informações de controle e gerenciamento de Recursos Humanos, foram criados alguns dos principais gráficos que remetem uma análise mais visual, rápida e contribui com a tomada de decisão diária, como novas contratações, reposições de quadros, controles de benefícios. 

- **Gráfico “Faixa Etária Idade”:** O objetivo desse gráfico é apresentar a distribuição de funcionários por faixa etária de idade, por meio de valor absoluto ou percentual;

- **Gráfico “Quantidade de Funcionários por Gênero”:** O objetivo desse gráfico é exibir de forma comparativa a distribuição da quantidade de funcionários por gêneros;

- **Gráfico “Tempo de Empresa”:** O objetivo desse gráfico é demonstrar de forma visual como está distribuído o “tempo de casa” dos funcionários, o gráfico de Radar proporciona essa visão generalista, na qual apresenta de forma muito efetiva a distribuição entre as faixa de tempo em dias;

- **Gráfico “Valores por Benefícios”:** O objetivo desse gráfico é apresentar os valores gastos por benefícios e o total geral, sendo ainda possível analisar por meio dos filtros os valores por área, contrato ou ano e tomar decisões com base nos valores;

- **Gráfico “Quantidade de Funcionários por Cargo”:** O gráfico apresenta o número de funcionários por cargo e por gênero, sendo possível realizar a comparação de distribuição;

- **Gráfico “Faixa Salarial”:** O gráfico a distribuição de salários por faixa e por gênero;

- ***Cards*:** Os *cards* na parte superior do painel apresentam o resumo de “Funcionários Ativos na empresa, desligados, *TurnOver*, Férias, Licenças Maternidade e outros”, também estando dentro dos critérios dos filtros de Área, Tipo de Contrato e Ano;

- **Paletas de cores utilizadas:** O uso de paletas de cores torna-se a visualização mais atraente, portanto deve ser escolhida seguindo uma lógica de cores, geralmente utilizo com base na logo do produto, empresa, marca e afins.

| RGB (162, 223, 242) | RGB (48, 58, 82) | RGB (243, 113, 104) | RGB (255, 255, 255) |
|-------------------|-------------------|-------------------|-------------------|
| ![162_223_242](https://github.com/AlbertoFAraujo/DashRH/assets/105552990/0da81637-049b-402b-ba45-1b5af16600e4) | ![48_58_82](https://github.com/AlbertoFAraujo/DashRH/assets/105552990/d51ba9a2-dd72-4365-bd3c-a3454103545a) | ![243_113_104](https://github.com/AlbertoFAraujo/DashRH/assets/105552990/5c85df64-0f5a-49ec-b698-8cfca2c45486) | ![255_255_255](https://github.com/AlbertoFAraujo/DashRH/assets/105552990/8bdaa061-5187-4f4d-a9a9-87cbf0697ba1) |
<hr>

#### 5. Teste de qualidade e eficácia do *dashboard* (garantir que todos os gráficos estejam funcionando corretamente e que os dados estejam sendo atualizados)

Foi realizado diversos testes para garantir que todos os gráficos estivessem sendo alterados automaticamente, assim como os rótulos não sendo impedidos de serem visualizados corretamente.
<hr>

### Resultado final

![DashRH_video](https://github.com/AlbertoFAraujo/DashRH/assets/105552990/eca5c5d1-01d0-4c7f-9ea6-64954db88d97)

