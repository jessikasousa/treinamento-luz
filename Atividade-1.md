
![CRUD](https://i.imgur.com/ZkGPHkM.png "CRUD")


<b>O que é o WPF?</b>
Segundo a documentação da Microsoft, WPF (Windows Presentation Foundation) é uma estrutura de interface do usuário que cria aplicativos cliente de desktop. Sua plataforma de desenvolvimento dá suporte a um amplo conjunto de recursos de desenvolvimento de aplicativos, incluindo um modelo de aplicativo, recursos, controles, gráficos, layouts, associação de dados, documentos e segurança. O WPF usa a linguagem XAML para fornecer um modelo declarativo para programação de aplicativos.


<b>Explique o Padrão Arquitetural MVVM</b>
O MVVM (Model View ViewModel) foi criado em 2005 para fazer data binding em aplicações WPF usando XAML; ele é um padrão de design de arquitetura de interface do usuário para desacoplamento da interface do usuário e de código que não é da interface do usuário.


<b>O que é fazer um Binding?</b>
Com o Binding é possível ligar as propriedades de um componente visual, como um TextBox, às propriedades de um objeto que existe apenas no código, ou seja, uma instância de uma classe, bem como também é possível ligar as propriedades de dois componentes visuais.



<b>Em suas palavras, explique o Padrão de Projeto Observer.</b>
O Padrão de Projeto Observer é um padrão comportamental que apresenta uma relação 1-N(um pra muitos) entre os objetos; assim, quando um objeto altera seu estado, os objetos dependentes serão notificados e atualizados automaticamente. 
Ele diminui acoplamento.



<b>Qual o papel da interface INotifyPropertyChanged?</b>
A interface INotifyPropertyChanged proporciona um mecanismo unificado para definir em um único evento as propriedades Changed que queremos definir em nosso objetos.


<b>Qual a diferença entre INotifyPropertyChanged e a INotifyCollectionChanged?</b>
O INotifyCollectionChanged é uma interface que a coleção deve implementar, e são para notificações de eventos de adição e remoção.


<b>Qual a diferença entre uma List, um ObservableCollection e um BindingList?</b>
A diferença prática é que BindingList é para WinForms e ObservableCollection é para WPF. De uma perspectiva do WPF, o BindingList não é suportado adequadamente, não sendo utilizado em um projeto WPF, a menos que fosse realmente necessário. 
Uma das principais diferenças do List para o ObservableCollection é que ObservableCollection não possui o método AddRange, o que pode ter algumas implicações.


<b>O que é vazamento de memória?</b>
Os "vazamentos de memória" ou "memory leak", são nomes dados quando uma porção de memória, alocada para uma determinada operação, não é liberada quando não é mais necessária. A ocorrência de vazamentos de memória é quase sempre relacionada a erros de programação. Apesar de um programa continuar sendo executado, normalmente o vazamento de memória pode resultar em perda de memória devido a maior atividade do coletor de lixo ou a uma maior ocupação da memória. Além disso, vazamentos de memória podem causar problemas mais graves como paginação em disco e falhas no programa como OutOfMemoryError.


<b>O que é Garbage Collector e como ele funciona?</b>
É um mecanismo complexo de gerenciamento de memória que é responsável pela alocação e liberação da memória. É ele que decide onde colocar os objetos no heap e ele decide também quando liberar a memória e de que forma.
O mecanismo usado é de verificação do estado da memória para identificar o que está em uso e o que não está mais. Desta forma, não se corre o risco de algo ficar para trás.


<b>Cite duas linguagens, uma que também tenha e outra que não tenha Garbage Collector.</b>
C e C++ não possuem. Já Java e C# possuem.
