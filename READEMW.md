

# Olá! Seja bem-vindo ao arquivo README desse projeto.

Sobre o projeto
Neste projeto, identificamos que os códigos das classes NegociacoesView e MensagemView possuíam trechos em comum. Para evitar repetição de código, isolamos essas partes em uma classe separada chamada View, juntamente com o construtor que recebe o elemento e o método update(). Agora, ambas as Views herdam da classe View, eliminando a duplicação do código em comum.

No entanto, é importante ressaltar que as classes filhas são responsáveis por implementar o método template(), que define o modelo de renderização específico de cada View.

Além disso, implementamos uma "armadilha" para evitar que os desenvolvedores se esqueçam de incluir o método template(). Caso o método não seja sobrescrito nas classes filhas, uma mensagem de erro será exibida no Console, alertando sobre a necessidade de implementação. Lembre-se de que um método na classe filha substitui os métodos da classe pai.

Também adicionamos o construtor() nas classes filhas utilizando a palavra-chave super, que permite passar os parâmetros para a classe pai. Fizemos um pequeno ajuste, removendo o prefixo _ do método template(), que anteriormente era privado. Essa alteração foi necessária para permitir que os métodos template() de NegociacoesView e MensagemView sobrescrevam o método na classe View.
<div style="https://img.freepik.com/fotos-premium/superficie-em-branco-texturizada-suja-fundo-cinza-abstrato-papel-de-parede-de-cartaz-sujo-com-sto-granulado-aspero_124507-10829.jpg">

# Como executar o projeto
* Faça o download ou clone este repositório em sua máquina local.<br>
* Abra o projeto em seu editor de código preferido.<br>
* Execute o arquivo principal.<br>
* Acompanhe as informações e interaja com as views presentes no projeto.
</div>