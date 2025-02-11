<h1>plantUML</h1>

Voit ladata sen sivulta <a href="https://plantuml.com/download" target="_blank">https://plantuml.com/download</a>. 

Riittää siis, että lataat tuon jar-tiedoston, mutta sovelluksen ajamiseksi tarvitset Javan.

Minulla on esimerkiksi tiedosto <b>myComponent.puml</b> ja voin generoida siitä png-kuvan komennolla

<pre>
java -jar plantuml-1.2025.0.jar myComponent.puml
</pre>

Repossa on on koodit 
<ul>
    <li>käyttöönottokaaviolle myBase.puml</li>
    <li>komponenttikaaviolle myComponent.puml</li>
    <li>käyttötapauskaaviolle myUseCase.puml</li>
    <li>Qt:n luokkakaaviolle myPeppiClass.puml</li>
    <li>REST API:n luokkakaaviolle myRestApiClass.puml</li>
</ul>

<h2>plantUML koodiopas</h2>

Opas löytyy sivulta <a href="https://plantuml.com/guide" target="_blank">https://plantuml.com/guide</a>

<h2>Esimerkkikoodien kuvat</h2>
    <h3>käyttöönottokaaviolle </h3> <img src="myBase.png">
    <h3>komponenttikaaviolle </h3> <img src="myComponent.png">
    <h3>käyttötapauskaaviolle </h3> <img src="myUseCase.png">
    <h3>Qt:n luokkakaaviolle </h3> <img src="myPeppiClass.png">
    <h3>REST API:n luokkakaaviolle </h3> <img src="myRestApiClass.png">