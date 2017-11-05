# Swift Fundamentals II

    /
    /: Playground - noun: a place where people can play
    
    
    
    import UIKit
    
    
    
    //===================================================
    
    // Operadores de Atribuição
    
    //===================================================
    
    var numero = 1000
    
    numero = 150
    
    
    
    // operadore LET náo pode ter seu valor modificado !
    
    
    
    var (numero1, numero2, numero3) = (100, 200, 300)
    
    
    
    
    
    //===================================================
    
    // Operadores Aritméticos
    
    //===================================================
    
    
    
    let soma = 2 + 2
    
    print ("Resultado é \(soma)")
    
    
    
    let subtracao = 10 - 7
    
    print ("Resultado é \(subtracao)")
    
    
    
    let multiplicacao = 100 * 5
    
    print ("Resultado é \(multiplicacao)")
    
    
    
    let divisao = 200 / 4
    
    print ("Resultado é \(divisao)")
    
    
    
    let resto = 33 % 5
    
    print ("Resultado é \(resto)")
    
    
    
    var numero5 = 100
    
    print (-numero5)
    
    
    
    
    
    
    
    //===================================================
    
    // Operadores Compostos
    
    //===================================================
    
    
    
    var valor = 100
    
    valor = valor + 10
    
    //O resultado será 110
    
    
    
    valor += 10
    
    //O resultado também será 110
    
    
    
    var preco = 300.00
    
    //O preço é igual a preço mais 59.90
    
    preco += 59.90
    
    
    
    print(preco)
    
    
    
    //O preço é igual a preço vezes 1.78
    
    preco *= 1.78
    
    
    
    //O preço é igual a preço dividido por 3
    
    preco /= 3
    
    
    
    var teraResto = 7
    
    teraResto %= 2
    
    
    
    
    
    //===================================================
    
    // Operadores de Comparação
    
    //===================================================
    
    
    
    //------------------------------------------------------------
    
    // Operador Descrição
    
    //------------------------------------------------------------
    
    // a == b a é igual a b
    
    // a != b a é diferente de b
    
    // a <b a é menor que b
    
    // a >b a é maior que b
    
    // a <= b a é menor ou igual a b
    
    // a >= b a é maior ou igual a b
    
    // a === b os objetos são idênticos
    
    // a !== b os objetos são diferentes
    
    
    
    
    
    var a = 1
    
    var b = 3
    
    a == b //falso
    
    
    
    a != b
    
    //verdadeiro
    
    
    
    a > b
    
    //falso
    
    
    
    a < b
    
    //verdadeiro
    
    
    
    a >= 1
    
    //verdadeiro
    
    
    
    a >= 2
    
    //falso
    
    
    
    a <= 1
    
    //verdadeiro
    
    
    
    a <= 3
    
    //verdadeiro
    
    
    
    a <= 0
    
    //falso
    
    
    
    
    
    //===================================================
    
    // Operador Ternário
    
    //===================================================
    
    
    
    // Sintaxe
    
    // (condição) ? acaoVerdadeira : acaoFalsa
    
    
    
    nome = "Antônio"
    
    resultado = (nome == "Geraldo") ? "Seja bem vindo" : "Desconhecido"
    
    
    
    var parOuImpar = (10 % 2 == 0) ? "Par" : "Impar" //Retornará par
    
    
    
    parOuImpar = (3 % 2 == 0) ? "Par" : "Impar" //Retornará ímpar
