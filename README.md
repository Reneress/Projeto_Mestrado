# Projeto Final de Mineração de Dados - Previsão da Qualidade de Vinhos

## Descrição do Projeto

Este repositório contém o projeto final da disciplina de Mineração de Dados, desenvolvido como aluno especial do curso de Mestrado em Engenharia da Computação da UNESP. O objetivo principal do projeto é comparar diferentes algoritmos de regressão linear na previsão da qualidade de vinhos, utilizando a base de dados pública **Wine Quality Dataset**.

## Objetivos

- **Comparação de Algoritmos de Regressão Linear**: Avaliar a eficácia de diferentes algoritmos de regressão linear na previsão da qualidade dos vinhos.
- **Métricas de Desempenho**: Utilizar métricas como Erro Quadrático Médio (MSE), Erro Absoluto Médio (MAE) e Coeficiente de Determinação (R²) para avaliar a precisão dos modelos.
- **Tunning de Modelos**: Realizar ajustes nos melhores modelos para melhorar a eficácia dos resultados.
- **Validação Cruzada**: Implementar validação cruzada *k-fold* com k=5 para garantir uma avaliação mais estável e menos sujeita a *overfitting*.
- **Modelos Híbridos**: Implementar e avaliar modelos híbridos de regressão para melhorar a precisão das previsões.

## Metodologia

### Base de Dados
- **Wine Quality Dataset**: Base de dados pública contendo características físico-químicas de vinhos e suas respectivas avaliações de qualidade.

### Algoritmos Utilizados
- **Regressão Linear**
- **Suporte a Vetores de Regressão (SVR)**
- **Random Forest**
- **Gradient Boosting**

### Modelos Híbridos
- **Random Forest + Gradient Boosting (meta: Linear Regression)**
- **Random Forest + Gradient Boosting (meta: Ridge Regression)**
- **Random Forest + AdaBoost (meta: Linear Regression)**
- **Gradient Boosting + AdaBoost (meta: Ridge Regression)**

### Ferramentas e Bibliotecas
- **Python**: Linguagem de programação principal.
- **scikit-learn**: Para implementação dos algoritmos de regressão e validação cruzada.
- **pandas**: Para manipulação e análise de dados.
- **numpy**: Para cálculos numéricos.
- **matplotlib**: Para visualização dos resultados.


## Como Executar o Projeto

1. **Clonar o Repositório**:
   ```bash
   git clone https:https://github.com/Reneress/Projeto_Mestrado.git
   cd nome-do-repositorio
  
## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para sugerir melhorias ou correções.


## Contato

Para mais informações ou dúvidas, entre em contato através do email: leonardoreneres525@gmail.com

---

**Nota**: Este projeto foi desenvolvido como parte da disciplina de Mineração de Dados do Mestrado em Engenharia da Computação da UNESP. O código e as análises estão disponíveis para fins educacionais e de pesquisa.
