<h1>Aula SetTimeout setInterval</h1>

<h2>setTimeout</h2>

O setTimeout() é um método JavaScript que chama uma função após alguns milissegundos.


O setTimeout é uma função(método) em JavaScript que permite executar uma determinada função ou trecho de código após um período específico de tempo (definido em milissegundos). Ele é bastante útil quando você deseja atrasar a execução de algo, como mostrar uma mensagem de alerta, mostrar um modal na tela, entre outras aplicações.

Mostrar exemplos práticos, página do estadão, globo.com, pagina do Coco Bambu

Essa é a sintaxe do setTimeout

setTimeout(função, tempo até executar)

A função será a ação executada que o setTimeout vai fazer ou a função que ele vai chamar

e o tempo até executar, será quanto tempo ele irá demorar para executar essa ação esse tempo é medido em milissegundos.

Os milissegundos na verdade são segundos só que elevados na base 1000, o que isso significa?

que 

1000 milissegundos = 1 segundos
2000 milissegundos = 2 segundos
3000 milissegundos = 3 segundos
4000 milissegundos = 4 segundos
5000 milissegundos = 5 segundos e assim sucessivamente...

Sintaxe do setTimeOut 

setTimeout( ()=>{ <br/>
    console.log("Executando após 3 segundos")
    <br/>
}, 3000)

Esse é o setTimeout na prática, em vez de chamarmos uma função de fora, uma função exterior que tornaria a lógica mais complicada, nós na verdade criamos uma função dentro do próprio setTimeout que o torna mais otizimado para executar a ação, essa função que criamos dentro do setTimeout se chama função anônima que em sua realidade é uma arrow function, porém que não possui nome. 

(caso perguntem essa função anônima também pode ser chamada de callback que é uma função passada dentro de um método).

- Exemplos para mostrar durante a aula

    Aparecer uma mensagem na tela após um período de tempo:
    <a href="https://codesandbox.io/s/magical-haze-6w4m3q?file=/src/Mensagem.js">Aparecer mensagem</a>

    Fazer uma contagem após um período de tempo
    <a href="https://codesandbox.io/s/magical-haze-6w4m3q?file=/src/App.js">Contagem</a>
    

    Exibir um modal após um período de tempo
    <a href="https://codesandbox.io/s/focused-dirac-8mndw8?file=/src/App.js">Modal</a>



 <h2>setInterval</h2>

 atualizando...