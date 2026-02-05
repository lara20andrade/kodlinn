# Kodlin
### 1 Estrutura_Sequencial
fun main() {
    var entrada_celsius = 30
   
    //F = C * 9/5 + 32
    var F = entrada_celsius * 9 / 5 + 32
   
    print(F)
}

### 2 Estrutura_Sequencial
fun main() {
   
    var entrada_Fahrenheit = 77
   
    // C = (F - 32) * 5/9
   
 
    var Celsius = (entrada_Fahrenheit - 32) * 5 / 9
   
    print(Celsius)
}

### 3 Estrutura_Sequencial
fun main() {
   
    var raio_base = 5
    var altura_lata = 10
   
    // V = 3 * raio_base^2 * altura,
    var volume = Math.PI * raio_base * 2 * altura_lata

   
    print(volume)
}

### 4 Estrutura_Sequencial
fun main() {
   
    var distancia_quilometros =240
    var consumo_litros= 12
   
   
    var quilometros = distancia_quilometros / consumo_litros

   
    print(quilometros)
}
### 5 Estrutura_Sequencial
fun main() {
   
    var valor_prestacao =1500
    var meses_atrasado= 3
    var taxa_juros= 1.0
    var valor = valor_prestacao * (1 + (taxa_juros / 100) * meses_atrasado)

### 6 Estrutura_Sequencial
fun main() {
    var a = 4
    var b = 5
    var troca = a
    a = b
    b = troca
    print( "Após a troca - a = $a, b = $b")
   
}
### 7 Estrutura_Sequencial
fun main() {
    
    var variavel_1 = 1
    var variavel_2 = 2
    var variavel_3 = 3
    var variavel_4 = 4
    
    
    var adição = (variavel_1 + variavel_2 + variavel_3 + variavel_4)

    var multiplicação = (variavel_1 * variavel_2 * variavel_3 * variavel_4)
    
    println("O resultado da adição é: $adição")
    
    println("O resultado da multiplicação é: $multiplicação")
}

### 8 Estrutura_Sequencial
fun main() {
   
    var comprimento = 5
    var largura = 3
    var altura = 2
   

    var volume = comprimento * largura * altura

   
    print(volume)
}

### 9 Estrutura_Sequencial
fun main() {
   
    var um = 5

    var resul = um * um

   
    print(resul)
}

### 10 Estrutura_Sequencial
fun main() {
   
    var um = 10
    var dois = 5
   

    var resul = um - dois

   
    print(resul)
}

### 11 Estrutura_Sequencial
fun main() {
   
    var dolar = 50

    var resultado = dolar * 5.60

   
    print(resultado)
}

### 12 Estrutura_Sequencial
fun main() {
   
    var real = 100

    var resultado = real / 5.60

   
    print(resultado)
}

### 13 Estrutura_Sequencial
fun main() {
    
    var valor_númerico1 = 1
    var valor_númerico2 = 5
    var valor_númerico3 = 6
    
    var soma_dos_quadrados = (valor_númerico1 * valor_númerico1) + (valor_númerico2 * valor_númerico2)  + (valor_númerico3 * valor_númerico3)
    

    print(soma_dos_quadrados)
  
}

### 14 Estrutura_Sequencial
fun main() {
    
    var valor_númerico1 = 2
    var valor_númerico2 = 3
    var valor_númerico3 = 4
    
    var soma_dos_valores = (valor_númerico1 + valor_númerico2 + valor_númerico3)
    
    var resultado = (soma_dos_valores * soma_dos_valores)
    

    print(resultado)
  
}

### 15 Estrutura_Sequencial
fun main() {
    
    var valor_1 = 2
    var valor_2 = 3
    var valor_3 = 4
    var valor_4 = 5
    
    var produto = (valor_1 * valor_3)
    
    var soma = (valor_2 + valor_4)
    

    println("Produto é igual: $produto, Soma é igual: $soma")
   
}


### 16 Estrutura_Sequencial
fun main() {
   
    var salario = 1000
    var porcentagem = 10.0

    var aumento = salario * (porcentagem / 100)
    var novo_salario = salario + aumento

   
    println("Aumento: $aumento")
    println("Novo salário: $novo_salario")
}
### 17 Estrutura_Sequencial
fun main() {
    var raio = 5
   
    var resultado = Math.PI * raio * raio
   
    println(resultado)
}
### 18 Estrutura_Sequencial

fun main() {
    
    var candidato_1 = 200
    var candidato_2 = 150
    var candidato_3 = 100
    var votos_nulos = 50
    var votos_em_branco = 30
    
    
    var total_eleitores = candidato_1 + candidato_2 + candidato_3 + votos_nulos + votos_em_branco
    
    println("O total de eleitores é de: $total_eleitores")
    
    println("Percentual de votos válidos:")
    var percentual_candidato1 = (candidato_1 * 100.0) / total_eleitores
    var percentual_candidato2 = ( candidato_2 * 100.0) / total_eleitores
    var percentual_candidato3 = ( candidato_3 * 100.0) / total_eleitores
    var percentual_nulos = (votos_nulos * 100.0) / total_eleitores
    var percentual_branco = (votos_em_branco * 100.0) / total_eleitores
    
    println("candidato 1 = %.2f%%".format(percentual_candidato1))
    println("candidato 2 = %.2f%%".format(percentual_candidato2))
    println("candidato 3 = %.2f%%".format(percentual_candidato3))
    println("Percentual de votos nulos = %.2f%%".format(percentual_nulos))
    println("Percentual de votos em branco = %.2f%%".format(percentual_branco))
}
### 19 Estrutura_Sequencial
fun main() {
    var a = 10
    var b = 5
   
    var soma = a + b
    var subtracao = a - b
    var divisao = a / b
    var multiplcacao = a * b
   
    println("Soma: $soma")
    println("Subtracao: $subtracao")
    println("Divisao: $divisao")
    println("Multiplicacao: $multiplcacao")
}

### 20 Estrutura_Sequencial
fun main() {
    val distancia = 100.0
    val tempo = 2.0
   
    val velocidade = distancia / tempo / 3.6
   
    println(velocidade)
}

### 21 EStrutura_Sequencial
fun main() {

    val valorBase = 2
    val valorExpoente = 3

    var potencia = 1

    for (i in 1..valorExpoente) {
        potencia *= valorBase
    }

    print(potencia)
   
}
### 22 Estrutura_Sequencial
fun main() {
    val raio = 5.0
   
    val resultado = (4.0/3.0) * Math.PI * (raio * raio * raio)
   
    print(resultado)
}

### 23 Estrutura_Sequencial
fun main() {
    val pes = 5.0
   
    val resultado = pes * 0.3048
   
    print(resultado)
}

### 25 Estrutura_Sequencial
fun main() {
    val numero = 5.0
   
    val antecessor = numero - 1
    val posterior = numero + 1
    println("Antecessor: $antecessor")
    println("Sucessor: $posterior")
}
### 26 Estrutura_Sequencial
fun main() {

    var valor_númerico1 = 10
    var valor_númerico2 = 2
    
    //Calcule a divisão do primeiro número pelo segundo número.
    var resultado_divisão = valor_númerico1 / valor_númerico2 
    
    //Calcule o quadrado do resultado da divisão.
    var resultado_quadrado = resultado_divisão * resultado_divisão
    
    print(resultado_quadrado)
    println ("($valor_númerico1 / $valor_númerico2 = $resultado_divisão, $resultado_divisão * $resultado_divisão = $resultado_quadrado)")

}

### 28 Estrutura_Sequencial
fun main() {

val numero = -5

if (numero > 0) {
    println("O número é positivo")
} else if (numero < 0) {
    println("O número é negativo")
} else {
    println("O número é neutro (zero)")
}

### 29 Estrutura_Sequencial
fun main() {

val nota1 = 7
val nota2 = 6
val nota3 = 4
val nota4 = 5

val media = (nota1 + nota2 + nota3 + nota4) / 4.0

if (media >= 5) {
    println("Média: $media, aprovada")
} else {
    println("Média: $media, reprovada")
}


