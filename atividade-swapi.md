#Atividade
João Vitor da Silva Batista 97021

Atividade de QA com APIs — SWAPI (versão do aluno)  
Tempo estimado: 30–40 minutos  
Ferramenta: Google Colab  
Objetivo: explorar uma API pública, analisar respostas JSON e criar testes simples com Python.

Este notebook tenta consultar o SWAPI online. Se a internet falhar, ele usa um modo de fallback local para você conseguir concluir a atividade.

Instruções  
atividade, você vai:

consultar endpoints da SWAPI  
observar o código de status  
ler o JSON retornado  
pensar como QA  
automatizar pelo menos 3 validações com assert  

---

Parte 1 — Explorando a API  
Consulte os endpoints abaixo:

https://swapi.dev/api/people/10/  
https://swapi.dev/api/people/13/  
https://swapi.dev/api/planets/2/  
https://swapi.dev/api/starships/10/  

Complete a célula abaixo.

![imagem](https://github.com/user-attachments/assets/d2078819-2175-48d7-a5a7-f870bc4c0ef2)
![imagem](https://github.com/user-attachments/assets/181cf987-a13b-42fb-862e-04b27a1d48a1)

---

Parte 2 — Análise QA da resposta  
Responda para cada endpoint:

Qual foi o código de status?  
O JSON parece completo?  
Quais campos?  
Qual campo você considera mais importante para validação?  

Escreva suas respostas na célula abaixo.

![imagem](https://github.com/user-attachments/assets/b943b548-54a6-41d1-95da-bf54cd5df446)
![imagem](https://github.com/user-attachments/assets/4fd2d44c-4a96-482a-8487-4da2e89e64c4)

---

Parte 3 — Pensando como QA  
Escolha um endpoint e proponha 5 validações que deveriam existir.

Exemplos de ideias:

código de status deve ser 200  
o campo name deve existir  
o nome não pode estar ela  
um campo numérico deve conter número  
uma resposta inválida deve retornar 404  

![imagem](https://github.com/user-attachments/assets/2ea5f096-3c1a-457b-8b47-9465d445bcca)

---

Parte 4 — Testes automatizados com assert  
Implemente pelo menos 3 testes automatizados usando assert.

Você pode usar um dos endpoints da atividade.

![imagem](https://github.com/user-attachments/assets/dfbebc80-5fdc-4277-9607-84db64cfee5b)

---

Bônus — Teste negativo  
Agora teste um endpoint inválido:

https://swapi.dev/api/people/9999/

O que você espera receber?

![imagem](https://github.com/user-attachments/assets/31c03522-0a1c-4bb0-a1be-9ad71d858591)
