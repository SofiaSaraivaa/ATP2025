# Relatório do TPC5  
**Autor:** Sofia Saraiva  

# Aplicação de Gestão de Dados Meteorológicos

Este TPC permite **analisar e gerir dados meteorológicos**, possibilitando o cálculo de estatísticas, consulta de informações, visualização de gráficos, bem como a gravação e leitura dos dados a partir de um ficheiro.

## Funcionalidades

A aplicação disponibiliza as seguintes opções:

### Processamento de dados
- **Temperatura média diária**  
  Calcula a média entre a temperatura mínima e máxima para cada dia registado.
- **Temperatura mínima absoluta**  
  Determina a menor temperatura mínima registada na tabela.
- **Amplitude térmica diária**  
  Calcula a diferença entre a temperatura máxima e mínima de cada dia.
- **Dia com maior precipitação**  
  Identifica o dia em que houve maior quantidade de chuva.
- **Dias com precipitação acima de um valor p**  
  Lista os dias em que a precipitação ultrapassa um valor fornecido pelo utilizador.
- **Maior período consecutivo com precipitação abaixo de p**  
  Calcula o número máximo de dias consecutivos com precipitação inferior a um limite definido pelo utilizador.

### Ficheiros
- **Guardar dados em ficheiro**  
  Exporta a tabela meteorológica para um ficheiro de texto.
- **Carregar dados de ficheiro**  
  Lê os dados de um ficheiro de texto e recria a tabela em memória.

### Visualização
- **Gráficos**  
  Gera gráficos das temperaturas mínimas e máximas ao longo do tempo e da precipitação diária.
