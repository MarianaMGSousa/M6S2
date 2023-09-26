# M6S2

</span>

Atividade do Módulo 6 da Semana do 2 curso da Ultima School - Django 


Exercício:


Usando como base a página de contato, crie uma página para fazer a reserva do banho para os Pets. Nesta página você irá ter um formulário com os seguintes campos:

- Nome do Pet (campo de texto — CharField)
- Telefone (campo de texto - CharField)
- Dia da reserva (campo de texto - CharField ou campo de data DateField)
- Observações (campo de texto mas com o widget Textarea).

Seguindo o exemplo da página de contato, crie a view, a url, o form e o template. Ao submeter o formulário de efetivar a reserva, é preciso fazer a mesma validação da página de contato e exibir uma mensagem de sucesso!

Para conseguir rodar e visualizar a página precisamos de um ambiente virtual, se ainda não tiver basta seguir os seguintes passos abaixo para criação.

No terminal você deve digitar:

1 - python -m venv nome-do-ambiente

2 - nome-do-ambiente\scripts\activate

3 - pip install django

4 - python .\manage.py runserver

Caso você já possua um ambiente virtual criando basta seguir do passo 2 ao 4.
