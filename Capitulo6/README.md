## Sobre: 

Exercício feito com o objetivo de testar os conhecimentos aprendidos sobre como a memória dentro de aplicações java é usada e como isso afeta o uso de variáveis. Para resolver esse teste foi necessário saber o funcionamento das duas partes da memória:
* **STACK** - Pilha onde as variáveis locais são guardadas durante a execucação do bloco de código onde residem acontece. Cada __thread__ possui sua própria stack, o que ajuda no gerenciamento da memória de forma organizada e rápida.
* **HEAP** - Local da memória mais amplo onde objetos são criados e armazenados, sendo acessados por referência. A memória heap é gerenciada pela JVM e inclui a __garbage collection__ para liberar memória de objetos que não são mais referenciados.
