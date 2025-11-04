# Learning Magnetic Lattice Structures - LMLS
### Cobalto e machine learning: uma atração magnética?
<p align="center">
 <img width="200" height="200" alt="CoX imagem" src="https://github.com/user-attachments/assets/012896bc-a56a-47c3-b13e-52f43c684471" />
</p>

O cobalto é um metal ferromagnético, o que significa que mantém sua magnetização mesmo após a remoção de um campo magnético externo. Essa propriedade deve-se aos seus elétrons desemparelhados, que se alinham criando um forte momento magnético. Sua estrutura cristalina hexagonal contribui para uma alta anisotropia magnética, tornando-o estável e confiável para aplicações magnéticas. No entanto, quando o cobalto forma compostos binários com outros elementos, suas propriedades (estrutura, eletrônicas, densidade) podem mudar drasticamente, resultando em tipos de ordenação magnética diferentes da ferromagnética.

Esse repositório contém o código-fonte referente ao projeto final da disciplina aprendizado de máquina, ministrada na Ilum - Escola de Ciência. Os códigos aqui presentes tem por objetivo prever o magnetismo de compostos que contém cobalto a partir de suas propriedades estruturais e estruturas eletrônicas, para isso não foi considerada o atributo "magnetização total" do dataset. Inicialmente, treinou-se a máquina a partir de 6 modelos distintos: k-vizinhos, regressão logística, árvore de classificação, floresta aleatória, SVC ("Support Vector Classifier") e NaiveBayes Gaussiano, medindo-se a acurácia de cada um deles. Em seguida,  otimizou-se os hiperparâmetros por meio do optuna e, por fim, comparou-se a importância de cada atributo para a previsão final de cada modelo por meio do SHAP. 

Os materiais aqui descritos são classificados em quatro níveis de magnetização: 
- FM - Ferromagnéticos
- FiM - Ferrimagnéticos
- AM - Antimagnéticos
- NM - Não magnéticos

O dataset pertence ao database Materials Project, uma base de dados aberta que fornece informações sobre materiais já conhecidos ou preditos por supercomputação alinhada a métodos já consagrados para ajudar na projeção de novos materiais. Nele, pode-se filtrar os mais de 200000 registrados de acordo com o interesse do usuário. Sob a ótica da análise anterior, foram selecionados os materiais binários que contivessem cobalto e fossem experimentalmente observáveis, para realmente trabalhar com compostos da realidade.

## Contribuidores

<p align="center">
  <img src="https://github.com/user-attachments/assets/e9785f1e-6c2a-4d5c-a014-757dc1ed01a7" alt="image1" width="180" height="200" />
  <img src="https://github.com/user-attachments/assets/3908c686-c2e3-42e7-b5fa-ebc09f966d84" alt="image2" width="180" height="200" />
  <img src="https://github.com/user-attachments/assets/11c69b63-e9eb-4f29-86f7-a1a41faef635" alt="image3" width="180" height="200" />
</p>

- Lília Helena Gavazza Pessôa
- Lívia Maria Barbosa de Aragão
- Sophia Alves da Silva

## Professor

<p align="center">
 <img width="150" height="150" alt="image" src="https://github.com/user-attachments/assets/c3fd879e-0d40-4b17-a878-147431d09807" />
<p align="center">
  <a href="https://github.com/drcassar" style="color:blue; text-decoration:underline;">Prof. Dr. Daniel R. Cassar</a><br>
  <a href="https://www.cnpem.br/" style="color:blue; text-decoration:underline;">Ilum - CNPEM</a><br>
  <a href="http://lattes.cnpq.br/1717397276752482" style="color:blue; text-decoration:underline;">Currículo Lattes</a>
</p>
