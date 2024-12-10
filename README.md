# Automação de Análise com Nuclei

## Visão Geral

Este projeto implementa um script em Python para automatizar a execução de análises de segurança em URLs utilizando a ferramenta Nuclei. Ele permite que múltiplos sites sejam analisados de forma programática, e os resultados sejam salvos em um arquivo de saída para posterior revisão.

## Requisitos
### **1. Ferramentas Necessárias**

Python (versão 3.8 ou superior)

[Nuclei](https://github.com/projectdiscovery/nuclei) (instalado e configurado no PATH do sistema)

### **2. Dependências**
O script utiliza a biblioteca padrão do Python, *subprocess*, que não requer instalação adicional.

## Estrutura do Código
O script contém as seguintes partes principais:

1. Função *run_nuclei*

* Recebe uma lista de URLs e um arquivo de saída (opcional).
*Para cada URL:
  * Executa o Nuclei usando o comando CLI.
  * Salva os resultados no arquivo especificado.
* Lida com erros e exibe mensagens no console.

2. Lista *rls_to_analyze*

* Define as URLs a serem analisadas.

3. Chamada da Função

* Inicia o processo com a lista fornecida.

# Conclusão
Este script oferece uma abordagem simples e eficiente para automatizar o uso do Nuclei em análises de segurança de sites. Com a flexibilidade do Python, ele pode ser facilmente estendido para atender a casos de uso específicos.
