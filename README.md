## Descrição do Desafio
<p> Agora é a sua hora de brilhar! Crie uma solução que explore o conceito de Padrões de Projeto na pŕatica. Para isso, você pode reproduzir um dos projetos que criamos durante as aulas ou, caso se sinta preparado, desenvolver uma nova ideia do zero ;-)</p>

<p> Dica: Além dos projetos/repositórios que criamos para este desafio, caso queira explorar novos padrões de projeto digite no Google: “java design patterns github” ou “java design patterns examples”. Com isso, você conhecerá novos padrões e implementações de referência que podem ajudá-lo a dominar esse tema!</p>

<p> Utiizei para implementar este projeto o padrão criacionista, visto que o desafio me deixou a possibilidade de desbravar novas ideias. Vamos utilizar o padrão Builder.</p>

## Objetivos do projeto:

- Apresentar o problema geral
- Apresentar a solução classica do Builder(proposto pelo livro do GOF)
- Apresentar uma solução alternativa (fluent interface)
- Refatorar a nossa implementação para uma aborgagem funcional


### Problema
- Como uma classe pode criar diferentes representações de um mesmo objeto complexo?

### Solução
- Delegar a criação do objeto para um builder ao invés de instanciar o objeto contreto diretamente.
- Dividir a criação do objeto em partes.
- Encapsular a criação e montagem dessa partes em um builder separado.

📋
```
" Separar a construção de um objeto complexo de sua representação para
que o mesmo processo de construção possa criar representações diferentes "
GOF
```
### Diagrama UML (Antes e depois)

![Diagram](/img/diagrama_meal.png)
