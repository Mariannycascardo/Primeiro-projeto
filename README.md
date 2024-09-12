# **Documentação de Flutter e Dart**

## **Flutter**

### **O que é Flutter ?**

#### O Flutter é um framework de desenvolvimento de software de código aberto criado pelo Google. Ele permite que os desenvolvedores criem aplicativos nativos para várias plataformas (Android, iOS, web e desktop) a partir de um único código-fonte.

## Características principais:

### **Cross-platform:**

#### Cross-platform é uma abordagem de desenvolvimento de software que permite que um mesmo código-fonte seja utilizado para criar aplicativos que funcionam em várias plataformas diferentes. Isso significa que você pode escrever o código uma vez e depois utilizá-lo para gerar versões do aplicativo para sistemas operacionais distintos, como Android, iOS, Windows, macOS, Linux, e até mesmo para a web, sem a necessidade de reescrever o código para cada plataforma específica.


### **Alta performance:**

 #### Alta performance em desenvolvimento de software, especialmente no contexto de frameworks como o Flutter, refere-se à capacidade de um aplicativo operar de maneira rápida e eficiente, com um bom tempo de resposta e sem atrasos ou problemas de desempenho.


### **Hot reload:**

####  A funcionalidade de Hot Reload do Flutter permite que os desenvolvedores vejam as mudanças feitas no código quase instantaneamente, sem precisar recompilar o aplicativo inteiro. Isso não apenas acelera o desenvolvimento, mas também permite que os desenvolvedores façam ajustes e otimizem o código para melhorar o desempenho enquanto testam o aplicativo em tempo real.


## **Os conceitos do Flutter**

### **UI em código:**

#### No Flutter, a interface do usuário é criada e configurada usando código Dart. Ao invés de usar uma ferramenta visual para desenhar a interface, você define a aparência e o comportamento da UI programaticamente.

### **Árvore de Widgets:**

####  A Árvore de Widgets é uma estrutura hierárquica que representa a organização dos widgets em um aplicativo Flutter. Cada widget na árvore pode ter widgets filhos, formando uma estrutura em árvore onde cada widget pode ser considerado um "nó" na árvore.

### **Única base de código:**

#### é um conceito fundamental no desenvolvimento de aplicativos usando Flutter. Esse conceito refere-se à capacidade de escrever e manter um único conjunto de código-fonte que pode ser usado para construir aplicativos em várias plataformas, como iOS, Android, web e desktop.

## **Widgets no Flutter**

### **O que são Widgets?**

####  são os componentes principais usados para construir a interface de usuário (UI) do aplicativo. Tudo no Flutter é baseado em widgets, e isso inclui elementos visuais, como textos, imagens, botões, e até mesmo layouts e interações complexas.

### **Exemplos de Widgets**

#### **Text:** E usado para exibe o texto na tela.
#### **ElevatedButton:** E usado para cria um botão elevado.
#### **Row e Column:** E usado para organizar widgets em linhas e colunas, respectivamente.

## **Como executar Flutter com VS Code**

### **Passos detalhados:**

#### Abri o terminal no VS Code, Cria um novo projeto Flutter com "flutter create" e coloque o nome_do_projeto, Navegue  até a pasta do projeto com "cd nome_do_projeto". Abri o projeto no VS Code usando "code .." , Localize o código principal na pasta lib e abri o arquivo "main.dart" Execute o aplicativo com "flutter run".

## **Material Design em apps nativas**

## **O que é Material Design?**

#### É um sistema de design desenvolvido pelo Google em 2014, com o objetivo de criar uma experiência de usuário (UI) visualmente agradável, coerente e intuitiva em diferentes dispositivos e plataformas. Ele combina conceitos de design gráfico tradicionais, como camadas e profundidade, com as capacidades interativas do mundo digital, oferecendo diretrizes específicas para criar interfaces funcionais e visualmente harmoniosas.

### **Widgets Material Design**

#### **AppBar:** Ela combina com uma variedade de elementos úteis, como títulos, ícones de ação e botões de navegação, permitindo que os usuários interajam de forma intuitiva com a aplicação.
#### **Scaffold:** É um dos widgets mais essenciais no Flutter, pois fornece a estrutura básica para a maioria das telas em aplicativos.
#### **Cupertino Widgets:** É usado para criar interfaces com estilo do iOS.

### **Como resolver problemas no Flutter?**

#### Primeiro vc vai ver aonde estar o erro vai aparecer no terminal em problem, você vai aperta em cima do ploblema que está aparecendo e ele vai te falar qual e o ploblema é e so você ler e resolver.

# Dart

### **O que é Dart?**

#### É uma linguagem de programação desenvolvida pelo Google, criada para otimizar o desenvolvimento de interfaces de usuário (UI) em aplicações frontend, tanto móveis quanto web.

## **Principais Características do Dart**

#### **Focada em UI:** Dart é desenhado para facilitar o desenvolvimento de interfaces ricas e interativas.

#### **Suporte para desenvolvimento assíncrono:** Oferece suporte nativo para manipulação de operações assíncronas.

#### **Orientação a objetos:** Dart é uma linguagem orientada a objetos com suporte para classes, interfaces e outras características típicas de linguagens modernas.

## **Tipos de Dados e Operações em Dart**

### **Tipos de Dados Comuns:**

#### **Int:** Números inteiros.
#### **Double:** Números com casas decimais.
#### **String:** Texto.
#### **Bool:** Valores booleanos (true ou false).

## **Funções e Métodos Comuns**

#### **Print:** Exibe informações no console.
#### **Add:** Adiciona um novo elemento a uma coleção.
#### **Length:** Retorna o tamanho de uma coleção ou string.
#### **ElementAt:** Retorna o elemento em um índice específico.

## **Palavras-chave e Conceitos**

#### **Import:** Inclui funcionalidades de outros arquivos, módulos ou bibliotecas.
#### **Main:** Função principal do programa.
#### **Class:** Define um tipo de dado com propriedades e métodos.
#### **Extends:** Indica que uma classe herda de outra classe.
#### **@override:** Indica que um método está sendo substituído.
#### **Final:** Indica que uma variável ou referência não será alterada após a atribuição.

## **Outros Conceitos em Dart e Flutter:**

#### **SetState:** Método fundamental em Flutter para atualizar o estado de um widget.
#### **StatelessWidget:** Classe base para widgets que não têm estado mutável.
#### **StatefulWidget e State:** Classe e instância usadas para widgets com estado mutável.
#### **Map, keys, values:** Utilizados para trabalhar com coleções de pares chave-valor.

