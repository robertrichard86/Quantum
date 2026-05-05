# Experimentos de Computação Quântica com IBM Qiskit

Este repositório abriga uma coleção de experimentos e algoritmos em **Computação Quântica**, implementados utilizando **Python** e o framework **IBM Qiskit**. O projeto visa explorar os fundamentos físicos quânticos através de simulações e execuções em hardware quântico real.

## 🔬 Foco dos Experimentos
Os notebooks (Jupyter/Python) contêm implementações detalhadas que abordam:

*   **Emaranhamento Quântico (Quantum Entanglement):** Simulação da criação de estados de Bell e análise das propriedades correlacionadas de qubits, incluindo simulações aplicadas (como "Estado da Água" e "Estações do Ano").
*   **Teletransporte Quântico:** Implementação do protocolo de teletransporte quântico, demonstrando a transferência do estado de um qubit para outro sem movimentação física do estado.
*   **Execução Híbrida:** Códigos preparados tanto para execução no `Aer_Simulator` local quanto para submissão de *jobs* em **Dispositivos Reais da IBM Quantum**.

## 💻 Python no Ecossistema Quântico
A utilização intensiva de **Python** (via Jupyter Notebooks) é a espinha dorsal deste projeto. O Python atua como a linguagem de interface de alto nível que permite aos pesquisadores e engenheiros abstrair a complexidade do hardware quântico. Através de bibliotecas matemáticas e de visualização, Python possibilita analisar os resultados estatísticos dos circuitos quânticos e traçar o *Statevector* ou histogramas de medição.

## 📊 Perspectivas Reais e Gerenciamento de Dados (SQL)
No avanço de pesquisas quânticas aplicadas a problemas de otimização logística e portuária, os algoritmos quânticos não rodam sozinhos. Eles necessitam de pipelines robustos:
*   **Arquitetura de Dados:** Em cenários do mundo real (como otimização de rotas de navios com IA Quântica), é essencial o uso de bancos de dados **SQL** para o pré-processamento clássico. 
*   **Uso de SQL:** Os dados históricos de roteamento, manifestos de carga e restrições portuárias são tipicamente extraídos via `SELECT` complexes em um *Data Warehouse*. Esses dados alimentam os modelos quânticos escritos em Python. Além disso, os resultados probabilísticos gerados pelo Qiskit são pós-processados e persistidos novamente em tabelas SQL para consumo por sistemas de BI (Business Intelligence).

## 🚀 Como Executar

1. Certifique-se de ter Python instalado e configure seu ambiente.
2. Instale o Qiskit via pip:
   ```bash
   pip install qiskit qiskit-aer matplotlib
   ```
3. (Opcional) Configure sua API Token da IBM Quantum no arquivo `Configurar IBM Quantum na IDE` para submeter jobs em hardware real.
4. Abra os arquivos `.ipynb` utilizando o Jupyter Notebook ou VSCode.

## 💼 Contexto Acadêmico / FATEC
Este repositório integra as pesquisas avançadas em Ciência de Dados e IA da FATEC Rubens Lara, mapeando o futuro da computação aplicada.
