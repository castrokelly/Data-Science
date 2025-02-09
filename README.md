# Data Science
## Abordagem Ensemble para Detecção e Classificação de Anomalias em Poços de Petróleo: um Estudo Aplicado ao Dataset 3W.

### **Centro de Ciências Matemáticas Aplicadas à Indústria (CeMEAI)**</br>
### **Instituto de Ciências Matemáticas e de Computação (ICMC)**</br>
### **Universidade de São Paulo**</br>
</br>
Aluna: Kelly Christine Alvarenga de Castro</br>
Área de concentração: Ciências de Dados</br>
Orientador: Prof. Dr. Cláudio Fabiano Motta Toledo</br>
</br>
---

Este Notebook apresenta o desenvolvimento de um pipeline de aprendizado de máquina para detectar e classificar anomalias em poços de petróleo utilizando o dataset 3W. 

A abordagem utiliza um modelo ensemble que, em primeiro lugar, decide se o estado é anômalo (classificação binária: normal vs. anômalo) e, caso seja anômalo, classifica o tipo de evento (rótulos de 1 a 9). O treinamento é realizado com dados de um poço e a validação das métricas é efetuada com dados de outro poço.

