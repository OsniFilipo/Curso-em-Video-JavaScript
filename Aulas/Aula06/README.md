<img src="https://wiki.tino.org/wp-content/uploads/2022/03/word-image-56.png">

# 📈 <a href="https://youtu.be/OJgu_KCCUSY?t=168"><i>Dois tipos Primitivos</i></a><span>

``Number`` e  ``String`` vão ser a tipos primitivo, usado nesta aula 

## <a href="https://github.com/OsniFilipo/Curso-em-Video-JavaScript/tree/main/Aulas/Aula04"><i>Conteúdo da aula 04</i></a><span>

```
  
<script>

        window.prompt('Qual é o seu nome?')

 </script>
  

```

Somente usando o código de acima não é armazenado, para ele guarda precisa declara um variável 

O igual ``=`` é Recebe, quando falamos em JavaScrit

## <a href="https://youtu.be/OJgu_KCCUSY?t=430"><i>Agora vai ter o nome guardado dentro da variável</i></a><span>
        
```
  
<script>

        var nome =  window.prompt('Qual é o seu nome?')

</script>
  
```


O mais ``+`` é Concatenação, quando falamos em JavaScrit

## <a href="https://youtu.be/OJgu_KCCUSY?t=615"><i>Usando o nome guardado dentro da variável no alarme vai aparece com  o nome.</i></a><span>

```
  
<script>

        window.alert('É um grande prazer em te conhecer, ' + nome '!' );

</script>
  
```

## <a href="https://youtu.be/OJgu_KCCUSY?t=725"><i>Exercício 03.</i></a><span>

Fazendo como o ex abaixo vai dar um erro.

```
  
<script>

        var n1 = window.prompt('Digite um número')
        var n2 = window.prompt('Digite outro número')
        var s = n1 + n2 
        window.alert('A somo dos valores é ' + s)

</script>
  
```

<a href="https://youtu.be/OJgu_KCCUSY?t=817"><i>Exemplo 4 + 2 = o resuldado vai dar 42</i></a><span>

```
  
  O mais + pode ser adição ou para concatenação.
  
```

<a href="https://youtu.be/OJgu_KCCUSY?t=906"><i>O certo a fazer é assim :</i></a><span>

```
   (number + number) para adição 
   (string + string) para concatenação
   (number > string) convertação posso usar o String(n); ou se usar o n.toString();
  
```

## <a href="https://youtu.be/OJgu_KCCUSY?t=960"><i>String > Número.</i></a><span>

Conversão de um ``número inteiro``

```
  
    Number.parseInt(n)
  
```

Conversão de um ``número real``

```
  
    Number.parseFlot(n)
  
```

## <a href="https://youtu.be/OJgu_KCCUSY?t=1023"><i>Treinando usando conversor.</i></a><span>

```

        var n1 = Number.parseFloat(window.prompt('Digite um número')); 
        var n2 = Number.parseFloat(window.prompt('Digite outro número')); 
        var s = n1 + n2 ;
        window.alert('A somo dos valores é ' + String(s));
        
```

ou tambem pode usar o.

```

        var n1 = Number(window.prompt('Digite um número')); 
        var n2 = Number(window.prompt('Digite outro número')); 
        var s = n1 + n2 ;
        window.alert('A somo dos valores é ' + s);
        
```

<a href="https://youtu.be/OJgu_KCCUSY?t=1142"><i>O number ele se vira e vai saber quando é real ou inteiro.</i></a><span>

## <a href="https://youtu.be/OJgu_KCCUSY?t=1214"><i>Número > String.</i></a><span>

```

    String(n)

```

ou 

```

    n.toString()

```

o resultado sendo uma String

```

        var n1 = Number.parseFloat(window.prompt('Digite um número'));
        var n2 = Number(window.prompt('Digite outro número'));
        var s = n1 + n2 ;
        window.alert('A somo dos valores é ' + String(s));

```

## <a href="https://youtu.be/OJgu_KCCUSY?t=1414"><i>Limpar o terminal no Node.js</i></a><span>


```

    Ctrl + L 

```

## <a href="https://youtu.be/OJgu_KCCUSY?t=1441"><i>Se for para escrever "O aluno Osni, de 23 anos tirou 5,5" no Node.js</i></a><span>

Jeito errado


```

    'O aluno ' + nome + ' com ' + idade + ' anos tirou a nota ' + nota

```

![Resume cv](/Imagens/06.png)

## <a href="https://youtu.be/OJgu_KCCUSY?t=1488"><i>Template Strigns o formatados de Strigns.</i></a><span>


![Resume cv](/Imagens/07.png)


```

    `O aluno ${nome} com ${idade} anos tirou a nota ${nota}`

```

## <a href="https://youtu.be/OJgu_KCCUSY?t=1597"><i>Template Strigns no ex03.</i></a><span>
  
```

        var n1 = Number.parseFloat(window.prompt('Digite um número'));
        var n2 = Number(window.prompt('Digite outro número'));
        var s = n1 + n2 ;
        window.alert(`A Soma entre ${n1} e ${n2} é igual a ${s}`);

```
  

## <a href="https://youtu.be/OJgu_KCCUSY?t=1673"><i>Formatados de Strigns.</i></a><span>
  
Quantos caracteres a string tem .
  
```

    s.length

```
  
Tudo para 'MAIÚSCULAS' .
  
```

    s.toUpperCase()

```
  
Tudo para 'minúsculas' .
  
```

    s.toLowerCase()

```
  
![Resume cv](/Imagens/08.png)
  
## <a href="https://youtu.be/OJgu_KCCUSY?t=1730"><i>Exercício 4.</i></a><span>

Começo do projeto.
  
```
  
<Script>

        var nome = window.prompt('Qual é o seu nome?')
        document.write(`Seu nome tem ${nome.length} letras.` )

</Script>
  
```

No final do projeto.

```

    <Script>

        var nome = window.prompt('Qual é o seu nome?')
        document.write(`Olá, ${nome}! Seu nome tem ${nome.length} letras.<br/>` )
        document.write(`Seu nome em maiúsculas é ${nome.toUpperCase()}<br/>`)
        document.write(`Seu nome em minúsculas é ${nome.toLowerCase()}<br/>`)

    </Script>

```

## <a href="https://youtu.be/OJgu_KCCUSY?t=1955"><i>Break row = quebre para a linha de baixo</i></a><span>

```
  
    <br/>
  
```
