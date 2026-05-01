# Miniguia de estudo sobre vida e obra de Ada Lovelace: a primeira programadora | utilizando NotebookLM
### Desenvolvedor: Guilherme Curiel

**Projeto**: https://notebooklm.google.com/notebook/8d74d255-d929-4a5b-8db7-3df280a88bf1/preview

## 📌 Resumo

O projeto consiste em um caderno de estudo sobre vida e obra de Ada Lovelace. O diferencial é que ao estudar, o usuário irá aprender com um engrama de Ada, com base em um treinamento do modelo para responder como se fosse ela.

## 📜 Glossário
* Treinamento de modelo;
* Engenharia de Prompt;
* Técnicas de Prompt;
* Informações acerca de vida e obra de Ada Lovelace:
  - Nasceu em Londres em 1815;
  - Filha de um poeta e uma matemática;
  - Foi educada voltada às ciências exatas;
  - Casou-se em 1935;
  - Principal contribuição foi com Charles Babbage, criador da máquina diferencial, Ada desenvolveu o algoritmo para cálculo da sequência de Bernoulli.

## 📎 Prompts reutilizáveis
1. "Escreva em formato de tópicos, os principais pontos da vida de Ada Lovelace, passando por sua infância, juventude e anos finais.";
2. "Explique, em uma tabela com detalhes, o que foi o algoritmo para calcular a sequência de Bernoulli desenvolvido por você." -> parte do treinamento da persona;
3. "Explique, em uma tabela, as principais diferenças entre seu pai e sua mãe, e no final compare tais diferenças e como impactaram sua vida." -> parte do treinamento da persona;
4. "Como tais pesquisas realizadas por Lovelace impactaram em tecnologias atuais? Destrinche e compare as pesquisas feitas por ela com as tecnologias atuais, demonstrando como teve impacto na sociedade contemporânea." -> pergunta mais difícil e que teve de ser feita duas vezes para obter resposta;

## 💻 Complemento: treinamento engrama Ada Lovelace | perguntas estratégicas

* **Troubleshoot**: a principal dificuldade encontrada foi treinar o modelo para se passar por Ada Lovelace. De priemira, o modelo só respondia de forma pessoal se o usuário também o tratasse dessa maneira e, quando tratado de forma impessoal, o modelo respondia de forma também impessoal. Para sanar isso, o treinamento foi remodelado para que não importa como as perguntas fossem feitas, o modelo sempre deveria incorporar Ada Lovelace. Também foi identificado que apesar de incorporar a persona da programadora, o modelo ainda fornecia respostas de maneira robótica e técnica, e o objetivo era tornar a conversa leve e fluída, por essa razão o treinamento também deixou claro que toda a conversa deveria soar natural ao usuário. Por mais treinamento que fosse fornecido, e apesar do modelo responder de forma pessoal mesmo tendo input impessoal, a quantidade de acertos conforme treinamento era quando as perguntas fossem também pessoais.
