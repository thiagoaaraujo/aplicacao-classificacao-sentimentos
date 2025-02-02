# 📝 Classificação de Sentimentos com Processamento de Linguagem Natural (PLN)

## 📄 Descrição

Este projeto foi desenvolvido como parte de um curso da **Alura**, com o objetivo de criar um modelo de **classificação de sentimentos** utilizando técnicas de **Processamento de Linguagem Natural (PLN)** e **Machine Learning**.  

A análise de sentimentos é muito utilizada para identificar a polaridade de textos (positiva, negativa ou neutra), sendo aplicada em avaliações de produtos, redes sociais e outras áreas que envolvem feedback textual.

---

## 📂 Estrutura do Projeto

```bash
📂 classificacao-sentimentos-pln
│-- 📂 data               # Conjunto de dados original e processado
│-- 📂 models             # Modelos e arquivos serializados
│-- 📂 notebooks          # Jupyter Notebooks com análises e modelagem
│-- 📄 requirements.txt   # Dependências do projeto
📄 README.md          # Documentação do projeto
```

---

## 🛠 Técnicas e Ferramentas Utilizadas

✔ **Análise de frequência de palavras** – Identificação das palavras mais comuns nos textos.  
✔ **Pré-processamento e normalização** – Limpeza de textos, remoção de stopwords e padronização.  
✔ **Stemming** – Redução das palavras à sua raiz para generalização.  
✔ **Conversão de textos em representações numéricas** – Transformação de texto em dados utilizáveis para Machine Learning.  
✔ **TF-IDF** – Avaliação da relevância de termos nos textos.  
✔ **N-grams** – Captura de contextos através de combinações de palavras.  
✔ **Modelagem com Machine Learning** – Treinamento de modelos para prever sentimentos em novos textos.  

As bibliotecas utilizadas foram **Pandas, Scikit-learn, NLTK, Matplotlib e NumPy**.

---

## ⚙️ Instalação e Uso

### **Pré-requisitos:**

1. Clone o repositório:  
   ```bash
   git clone https://github.com/thiagoaaraujo/aplicacao-classificacao-sentimentos.git
   cd aplicacao-classificacao-sentimentos
   ```
2. Crie e ative um ambiente virtual:  
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```
3. Instale as dependências:  
   ```bash
   pip install -r requirements.txt
   ```

---

### **Execução:**

Para rodar o notebook principal:  
```bash
jupyter notebook notebooks/NLP_analise_de_sentimentos.ipynb
```

---


## 📊 Resultados

O modelo foi treinado e avaliado com a métrica de **Acurácia**. O melhore resultado foi obtido com o uso da técnica **TF-IDF** para representação dos textos e um modelo baseado em **Logistic Regression**.

### **Principal métrica do melhor modelo:**  
- **Acurácia:** 91.85% 

---

## 🤝 Contribuição

Contribuições são bem-vindas! Para colaborar:

1. Faça um **fork** do repositório  
2. Crie uma **branch** com sua funcionalidade (`git checkout -b feature-nova`)  
3. Faça o **commit** das suas alterações (`git commit -m "Adiciona nova feature"`)  
4. Envie para o repositório remoto (`git push origin feature-nova`)  
5. Abra um **Pull Request**  

---

## 📧 Contato

Desenvolvido por [Thiago Aparecido de Araujo](https://www.linkedin.com/in/thiago-aparecido-de-araujo-1931341b4).  
Entre em contato via e-mail: thiagoaparecidoaraujo23@gmail.com  

---
