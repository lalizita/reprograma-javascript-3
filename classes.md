## Javascript Módulo III

### Classes em javascript - 03/06

* [Paradigma de Orientação a Objetos](#orientacao-a-objetos)

### Breve introdução a Orientação à objetos

Orientação à Objetos, conhecida como OOP (Object Oriented Programming) é um paradigma de programação, que nos permite criar modelos a partir de abstrações do mundo real. Na verdade a palavra que mais identifica este paradigma é a palavra *modelo*. Por exemplo: Quando você vai ao banco e o "Sidnelson" te mostra simulações de um consórcio a partir de modelos que já existem, com calculos pré preparados que podem ser aplicados em outras modalidades.
Existem diversas discussões sobre javascript ser uma linguagem orientada à objetos ou não. Tem razão, em comparação à outras linguagens talvez javascript não seja tão forte em alguns requisitos, mas estamos caminhando para isso. O por quê dessa discussão.

Abaixo algumas características de uma linguagem orientada à objetos:

#### Namespaces
    Um recipiente que permite empacotar todas as funcionalidades em um nome único e específico da aplicação.

#### Classe
    Define as características de um objeto. Uma classe é uma definição modelo das propriedades e métodos de um objeto. Ela é formada por dados e comportamentos.

#### Objeto
    Um exemplar dentro de uma classe, esse exemplar contém características como tipo.

#### Atributo
    Carcaterística do objeto, como a cor dos cabelos, cor dos olhos, cor da pele de uma pessoa.

#### Método
    Ação do objeto, como ligar, desligar, pular, abaixar. Uma função associada à uma Classe.

#### Construtor
    É um método no qual você define as propiedades de uma classe. Abstração desse modelo.

#### Herança
    Herdar características de outra classe.

#### Encapsulamento 
    Uma maneira de agrupar os dados e os métodos que usam os dados.

#### Abstração 
    A conjunção de herança complexa, métodos, propriedades de um objeto devem refletir adequadamente um modelo da realidade.

#### Polimorfismo
    Diferentes classes podem definir o mesmo método ou propriedade.

***

### Classes
    Como vimos à cima a Classe é um modelo. Imaginamos que o guarda-roupas é uma classe e cada gaveta é um método, e dentro desses métodos temos nossas roupas que são representadas pelos objetos, e essas roupas tem atributos que são suas características como cores, tamanho, condicionais se são velhas ou não, estão rasgadas ou não?

    A partir do ES2015 (ES6) ficou ainda mais fácil materializar a estrutura da nossa classe com a introdução da sintaxe *class* na linguagem javascript

    ```
    class Heroi { 
        // Classe Heroi criada!
    }

    ```

#### Método contrutor()
    Continuando a nossa classe herói, sabemos que todos heróis têm algumas características em comum, como poderes, planetas e força.

    ```
    class Heroi {
        constructor(){
            this.poder = 'voar',
            this.forca = 0,
            this.planeta = 'Terra'
        }
    }
    ```