<h1>Aula SetTimeout setInterval</h1>

<h2>setTimeout</h2>

O setTimeout() é um método JavaScript que chama uma função após alguns milissegundos.


O setTimeout é uma função(método) em JavaScript que permite executar uma determinada função ou trecho de código após um período específico de tempo (definido em milissegundos). Ele é bastante útil quando você deseja atrasar a execução de algo, como mostrar uma mensagem de alerta, mostrar um modal na tela, entre outras aplicações.

Exemplos práticos: <a href="https://www.estadao.com.br/">página do estadão</a> , <a href="https://www.globo.com/">globo.com</a>

Essa é a sintaxe do setTimeout

setTimeout(função, tempo até executar)

A função será a ação executada que o setTimeout vai fazer ou a função que ele vai chamar

e o tempo até executar, será quanto tempo ele irá demorar para executar essa ação esse tempo é medido em milissegundos.

Os milissegundos na verdade são segundos só que elevados na base 1000, o que isso significa?

que 

1000 milissegundos = 1 segundos<br/>
2000 milissegundos = 2 segundos<br/>
3000 milissegundos = 3 segundos<br/>
4000 milissegundos = 4 segundos<br/>
5000 milissegundos = 5 segundos e assim sucessivamente...

Sintaxe do setTimeOut 

    setTimeout( ()=>{ 

        console.log("Executando após 3 segundos")
        
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

 O setInterval é uma função (método) incorporada do JavaScript que é usada para executar repetidamente uma função ou trecho de código com um intervalo de tempo fixo entre cada execução. Ele é comumente usado para atualizações regulares na UI (User Interface), animações, ou para verificar periodicamente as alterações de estado ou dados.

Ou seja ele irá executar ações repetidas em um determinado período de tempo, ele também funciona utilizando o sistema de milissegundos.

Podemos utilizar o setInterval em Slideshows e Carrosséis de Imagens: setInterval é comumente usado para mudar automaticamente as imagens ou slides em um slideshow ou carrossel a intervalos regulares.

Exemplo prático(carrosel de imagens): <a href="https://www.mercadolivre.com.br/">MercadoLivre</a>

 Sintaxe setInterval

    setInterval( ()=>{

        console.log("Executando após 3 segundos")
        
    }, 3000)

- Exemplos para mostrar durante a aula

Contador automático (sem clearInterval): <a href="https://codesandbox.io/s/magical-haze-6w4m3q?file=/src/Contador.js">Contador</a>