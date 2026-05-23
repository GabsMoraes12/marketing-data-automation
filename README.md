# Automação de Relatórios de Marketing com Python

Este projeto demonstra a aplicação prática da programação e inteligência de dados na otimização de processos de Marketing Digital. O script automatiza a leitura de dados brutos de campanhas de tráfego pago, realiza o cálculo de métricas de retorno sobre investimento (ROI) e gera um relatório estilizado diretamente em formato Microsoft Excel, incluindo gráficos nativos.

---

## Tecnologias e Ferramentas Utilizadas

* **Python:** Linguagem base para manipulação da lógica e dos dados.
* **Pandas:** Biblioteca utilizada para estruturação, limpeza e modelagem dos dados de tráfego (DataFrames).
* **OpenPyXL:** Ferramenta responsável pela engenharia do arquivo Excel, aplicação de estilos visuais corporativos e inserção do gráfico nativo.
* **Google Colab:** Ambiente em nuvem utilizado para o desenvolvimento e execução do script.

---

## Funcionalidades do Script

1. **Processamento de Dados:** Simula a ingestão de um banco de dados bruto contendo investimentos e retornos financeiros de campanhas de tráfego (como Meta Ads ou Google Ads).
2. **Cálculo de Métricas (ROI):** Executa o cálculo automático do Retorno Sobre o Investimento de cada linha operacional através da fórmula:
   
   $$\text{ROI} = \frac{\text{Retorno}}{\text{Investimento}}$$

3. **Design e Estilização:** Formata a planilha gerada aplicando padrões de design corporativo (títulos destacados em cores personalizadas e tipografia limpa), garantindo uma apresentação profissional para tomada de decisão.
4. **Data Visualization:** Cria e acopla de forma 100% automatizada um gráfico de barras nativo no Excel para facilitar a leitura visual do desempenho das campanhas.

---

## Como o resultado se parece?

O script gera um arquivo final chamado `Relatorio_Performance_Marketing.xlsx`. Ao ser aberto no Microsoft Excel ou Planilhas Google, o usuário encontra:
* Uma tabela organizada e limpa com os dados originais e o ROI calculado.
* Cabeçalhos customizados em azul escuro com fontes destacadas.
* Um gráfico de barras dinâmico posicionado ao lado dos dados, ilustrando o retorno financeiro por campanha.

---

## Contexto do Projeto

Desenvolvido como projeto prático focado em demonstrar a viabilidade de integração entre **Ciência da Computação** e **Marketing Digital**, automatizando rotinas que antes eram manuais, repetitivas e suscetíveis a erros humanos.
