# **Documentação de Flutter e Dart**

## **Flutter**

### **O que é Flutter ?**

#### E um framework de código aberto desenvolvido pelo Google para a construção de aplicações nativas para iOS, Android, web e desktop a partir de um único código-fonte

## Características principais:

### **Cross-platform:**

#### Um único código pode ser utilizado para criar apps para diferentes plataformas.


### **Alta performance:**

 #### As aplicações Flutter são compiladas diretamente para código nativo, oferecendo uma performance comparável a aplicativos desenvolvidos de forma nativa.


### **Hot reload:**

#### Permite ver as mudanças no código quase instantaneamente durante o desenvolvimento, sem a necessidade de recompilar a aplicação.


## **Os conceitos do Flutter**

### **UI em código:**

#### Flutter, a interface de usuário é construída diretamente no código através de uma hierarquia de widgets.

### **Árvore de Widgets:**

#### A interface do aplicativo Flutter é organizada em uma estrutura hierárquica chamada "árvore de widgets".

### **Única base de código:**

#### Dependentemente da plataforma de destino (iOS, Android, web, desktop), você escreve um único código que é compilado para diferentes plataformas.

## **Widgets no Flutter**

### **O que são Widgets?**

#### São os blocos de construção fundamentais em Flutter que descrevem a aparência e o comportamento de qualquer elemento na interface do aplicativo.

### **Exemplos de Widgets**

#### **Text:** Exibe texto na tela.
#### **ElevatedButton:** Cria um botão elevado.
#### **Row e Column:** Organizam widgets em linhas e colunas, respectivamente.

## **Como executar Flutter com VS Code**

### **Passos detalhados:**

#### Abrir o terminal no VS Code, Criar um novo projeto Flutter com "flutter create" e coloque o nome_do_projeto, Navegue  até a pasta do projeto com "cd nome_do_projeto". Abri o projeto no VS Code usando "code .." , Localize o código principal na pasta lib e abrir o arquivo main.dart. Execute o aplicativo com "flutter run".

## **Material Design em apps nativas**

## **O que é Material Design?**

#### É um sistema de design desenvolvido pelo Google, utilizado amplamente em aplicativos Android, mas disponível para outras plataformas.

### **Widgets Material Design**

#### **AppBar:** Barra superior em um aplicativo.
#### **Scaffold:** Estrutura básica para layout de tela.
#### **Cupertino Widgets:** Para criar interfaces com estilo do iOS.

### **Como resolver problemas no Flutter?**

#### Verifique as dependências e o código para possíveis erros de sintaxe ou lógica.

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

