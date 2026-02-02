# Análise de Preferências Musicais: Springfield vs Shelbyville

## Objetivo do Projeto
O projeto visa comparar as preferências musicais dos habitantes de Springfield e Shelbyville, testando a hipótese de que a atividade dos usuários difere dependendo do dia da semana e da cidade. O problema de negócio é entender se há diferenças significativas no comportamento de escuta de música entre essas duas cidades para informar decisões de marketing ou personalização de serviços de streaming.

## Resultado
A análise revelou diferenças na atividade musical entre as cidades e dias da semana:
- Springfield teve um total de 42.741 faixas ouvidas, enquanto Shelbyville teve 18.512, indicando maior atividade em Springfield.
- Em termos de dias: sexta-feira liderou com 21.840 faixas, seguida por segunda-feira (21.354) e quarta-feira (18.059).
- A hipótese foi confirmada: a atividade dos usuários varia por cidade e dia da semana, com Springfield sendo mais ativo e sexta-feira o dia de pico.

Esses insights ajudam a identificar padrões de consumo e potencial para campanhas direcionadas.

## Ferramentas Utilizadas
- **Bibliotecas**: Pandas (para manipulação e análise de dados).
- **Tecnologias**: Jupyter Notebook (para execução interativa do código), Python (linguagem de programação).

## O que Aprendeu
Neste projeto, adquiri habilidades em:
- Pré-processamento de dados com Pandas: tratamento de valores ausentes, remoção de duplicados e correção de inconsistências (como gêneros musicais implícitos).
- Análise exploratória de dados: agrupamento, filtragem e agregação para testar hipóteses.
- Estruturação de notebooks para análise de dados: organização de células para fluxo lógico de trabalho.
- Interpretação de resultados: extração de insights acionáveis de dados agregados.

## Metodologia
1. **Visão Geral dos Dados**: Carregamento do arquivo CSV e inspeção inicial (tipos de dados, valores ausentes, duplicados).
2. **Pré-processamento**:
   - Padronização de cabeçalhos (conversão para snake_case).
   - Tratamento de valores ausentes (remoção ou preenchimento conforme contexto).
   - Remoção de duplicados explícitos.
   - Correção de duplicados implícitos em gêneros musicais usando funções customizadas.
3. **Teste da Hipótese**: Agrupamento de dados por cidade e dia da semana, cálculo de métricas de atividade (número de faixas ouvidas) e comparação dos resultados.

## Como Executar o Projeto
1. Certifique-se de ter Python instalado (versão 3.x recomendada).
2. Instale a biblioteca Pandas: `pip install pandas`.
3. Abra o arquivo `Análise de Preferências Musicais Springfield vs Shelbyville.ipynb` no VS Code (com extensão Jupyter) ou Jupyter Notebook/Lab.
4. Execute as células em ordem sequencial, começando pela importação de bibliotecas e carregamento de dados.
5. O arquivo de dados `music_project_en.csv` deve estar no mesmo diretório do notebook.

## Melhorias Futuras
- Implementar testes estatísticos formais (como teste t ou ANOVA) para validar hipóteses com maior rigor.
- Adicionar visualizações (usando Matplotlib ou Seaborn) para representar graficamente as diferenças de atividade.
- Expandir a análise para incluir mais variáveis, como gêneros musicais preferidos por cidade/dia.
- Integrar dados de outras fontes para uma visão mais completa do comportamento do usuário.
- Automatizar o pré-processamento com scripts modulares para reutilização em projetos similares.