# Clusterização: Lidando com Dados Sem Rótulos

## Sobre o Projeto

Este projeto foi desenvolvido como parte do curso **"Clusterização: Lidando com Dados Sem Rótulos"** da Alura.

O objetivo é aplicar técnicas de **Machine Learning Não Supervisionado**, utilizando o algoritmo **K-Means**, para identificar padrões de comportamento e segmentar usuários em grupos de interesse para campanhas de marketing.

A aplicação foi construída com **Python** e **Streamlit**, permitindo que novos dados sejam enviados através de um arquivo CSV para que o modelo treinado realize previsões dos grupos aos quais cada usuário pertence.

---
## Link do Streamlit
https://cursoaluraclusteriza-o-revisaodeagrupamentosgit-7s2fgq6fwknkcj.streamlit.app/
---

## Tecnologias Utilizadas

* Python
* Pandas
* Scikit-Learn
* Streamlit
* Joblib

---

## Funcionalidades

* Upload de arquivos CSV.
* Pré-processamento dos dados utilizando Encoder e Scaler previamente treinados.
* Predição de clusters com o algoritmo K-Means.
* Visualização dos resultados diretamente na interface.
* Download do arquivo CSV contendo os grupos previstos.

---

## Estrutura do Modelo

O projeto utiliza três artefatos treinados previamente:

* `encoder.pkl` → Responsável pela codificação da variável categórica "sexo".
* `scaler.pkl` → Responsável pela normalização dos dados.
* `kmeans.pkl` → Modelo de clusterização treinado com K-Means.

---

## Grupos Identificados

### Grupo 0

Público jovem com forte interesse em moda, música e aparência.

### Grupo 1

Público com maior afinidade por esportes, especialmente futebol americano, basquete e atividades culturais como banda e rock.

### Grupo 2

Perfil mais equilibrado, apresentando interesses em música, dança e moda.

---

## Como Executar

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute a aplicação:

```bash
streamlit run app.py
```

Após iniciar, acesse a interface no navegador e envie um arquivo CSV para realizar as previsões.

---

## Objetivo Educacional

Este projeto tem fins educacionais e demonstra a aplicação prática de técnicas de clusterização para segmentação de usuários, auxiliando na tomada de decisões e na personalização de estratégias de marketing.
