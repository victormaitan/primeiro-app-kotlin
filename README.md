# Primeiro App Kotlin

Aplicativo criado para o aprendizado da linguagem Kotlin aplicada ao Android.

Basicamente o aplicativo é um gerador de números randômicos.

No app contém apenas um botão e um texto que é mostrado dinamicamente conforme o numero gerado.

## Imagens

<p float="left">
	<kbd>
<img src="app/src/main/res/prints/1.png" border="1" alt="Print 1"/>	
	</kbd>
</p>
<p float="right">
	<kbd>
<img src="app/src/main/res/prints/2.png" border="1" alt="Print 1"/>	
	</kbd>
</p>

## Aprendizado

O que aprendi construindo esse app.

### Estrutura de pastas

A estrutura de pastas ficou mais clara de entender depois de começar a brincar um pouco com o app.

A `manifests` contém o `AndroidManifest.xml` onde é possível configurar as permissões que o app precisará para funcionar, nome do app, ícone, arquivo de entrada de estilos, as fontes, arquivo main do projeto e entre outras configurações.

A  `java` é onde fica localizada os arquivos kotlin onde estão localizados os códigos e a main.

A  `res` é a pasta onde ficam localizados os recursos ou "resources", como se fosse a pasta `assets` na programação web. Nela contem os arquivos `xml` de fontes, temas, cores, layout e outros.

### Estilização

No arquivo `themes.xml` é possível configurar estilos individuais para qualquer componente, após isso, basta referenciar na tag do componente  a propriedade `style` passando o nome do arquivo e o nome do estilo criado na activity. Será herdado todo o estilo aplicado. Assim como uma classe CSS.

É possivel definir individualmente para cada componente também diretamente na tag do componente na activity. 

Por padrão também é criado um arquivo `Colors.xml` onde é possível criar quantas cores quiser para utilizar no app. Basta criar um novo item, passando o nome que será dado para a cor e seu codigo hexadecimal.

### Código

Variáveis que não podem sofrer mutações em seu valor são declaradas como `val` em kotlin, que é o equivalente ao `final` no java e em outras linguagens.

Variaveis segue o mesmo nome que em outras linguagens `var`

As funções em kotlin são declaradas como `fun`

Para se obter as propriedades de um componente é possível acessar utilizando a segunte maneira `R.propriedade.nomeDoComponente`

Também foi possível aprender como adicionar um evento de click a um componente e fazer disparar uma função que modificasse diretamente outro componente. Como o texto, por exemplo.

## Tecnologias utilizadas

<span>
<img src="https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
</span>
Obrigado!
