## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```## Questão 1:➖
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2= readln().toDouble()
    var diferenca = num1 - num2
   
    print("A diferença é: " + diferenca)

   
}
```
## Questão 2:🔠
```kotlin
fun main(){
   
    val nome = readln()
    val sobrenome = readln()
    print("Seu nome completo é " + nome + sobrenome)

   
}
```
## Questão 3:🟰
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var soma = num1 + num2
    var diferenca = num1 - num2
    var divisao = num1 / num2
    var mult = num1 * num2
    print("A soma é " + soma + ", a difereça é " + diferenca + ", a divisao é " + divisao + ", a mult é " + mult)
   

   
}
```
## Questão 4:⏹️
```kotlin
fun main(){
   
    val num1 = readln().toDouble()
    val num2 = readln().toDouble()
    var area = num1 * num2
    print("A area do quadrado é: " + area)
   

   
}
```
## Questão 5:🔼
```kotlin
fun main(){
   
    val base = readln().toDouble()
    val altura = readln().toDouble()
    var area_tri = (base * altura) / 2
    print("A area do triangulo é: " + area_tri)
   
   
}
```
## Questão 6:⚖️
```kotlin
fun main(){
   
    val peso = readln().toDouble()
    val altura = readln().toDouble()
    var imc = peso / (altura * altura)
    print("Seu IMC é" + imc)
   
   
   
}
```
## Questão 7:🪪
```kotlin
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```
## Questão 8:🧮
```kotlin
fun main(){
   
    val nota1 = readln().toDouble()
    val nota2 = readln().toDouble()
    val nota3 = readln().toDouble()
    var media = (nota1 + nota2 + nota3) / 3
    print("Sua média é: " + media)
   
}
```
## Questão 9:📅
```kotlin
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## Questão 10:📈
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## Questão 11:🔢
```kotlin
import kotlin.math.pow

fun main() {

    val A = readln().toInt()
    val B = readln().toInt()
    val C = readln().toInt()

    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)

    val D = (R + S) / 2

    println("O valor de D é: $D")
}
```
## Questão 12:🚗
```kotlin
fun main() {

    val custoFabrica = readln().toDouble()

    val distribuidor = custoFabrica * 0.28
    val impostos = custoFabrica * 0.45

    val custoFinal = custoFabrica + distribuidor + impostos

    print("O custo ao consumidor é: R$" + custoFinal)
}
```
## Questão 13:📊
```kotlin
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## Questão 14:💳
```kotlin
fun main() {

    val salario = readln().toDouble()
    var novo_salario = salario * 1.25
    print("O novo salario é:" + novo_salario)

}
```
## Questão 15:💵
```kotlin
fun main() {

    val salario = readln().toDouble()
    val percentual = readln().toDouble()
    var novo_salario = salario * (1 + percentual / 100)
    print("O novo salario é:" + novo_salario)

}
```
## Questão 16:🗓️
```kotlin
fun main()
{
    var nascimento = readln().toDouble()
    var ano_atual = readln().toDouble()
    val idade = ano_atual - nascimento
    val idade_meses = idade * 12
    val idade_semanas = idade * 52
    val idade_dias = idade * 365
    println("Sua idade em anos Ã© " + idade)
    println("Sua idade em meses Ã© " + idade_meses)
    println("Sua idade em semana Ã© " + idade_semanas)
    println("Sua idade em dias Ã© " + idade_dias)
   
}
```
## Questão 17:🐈
```kotlin
fun main()
{
    var peso_sacokg = readln().toDouble()
    var racao_gatog = readln().toDouble()
    val totalGramas = peso_sacokg * 1000
    val consumoDia = racao_gatog * 2
    val consumo5Dias = consumoDia * 5
    val restante = totalGramas - consumo5Dias
    print("A quantidade de ração que sobrou foi: " + restante)


   
   
}
```
## Questão 18:⬅️
```kotlin
fun main()
{
    var A = readln().toDouble()
    var B = readln().toDouble()
    val temp = A
    A = B
    B = temp
    println("Após a troca: ")
    println("A = " + A)
    println("B = " + B)

}
```
## Questão 19:📦
```kotlin
fun main()
{
    var comprimento = readln().toDouble()
    var largura = readln().toDouble()
    var altura = readln().toDouble()
    val volume = comprimento * altura * largura
    print("O volume da caixa é: " + volume)
}
```
## Questão 20:🫚
```kotlin
fun main()
{
    var numA = readln().toDouble()
    var numB = readln().toDouble()
    val diferenca = numA - numB
    val quadrado = diferenca * diferenca
    print("O quadrado da diferença é: " + quadrado)
}
```
## Questão 21:💵
```kotlin
fun main()
{
    var dolar = readln().toDouble()
    var cotacao = 5.20
    val real = dolar * cotacao
    print("O valor do Real referente a esse valor em dolar é: " + real)
   
}
```
## Questão 22:🟥
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    var num3 = readln().toDouble()
    val soma = num1 + num2 + num3
    val quadrado = soma * soma
    print("O quadrado da soma desses tres valores é:" + quadrado)
   
   
}
```
## Questão 23:➗
```kotlin
fun main()
{
    var num1 = readln().toDouble()
    var num2 = readln().toDouble()
    val soma = num1 + num2
    val sub = num1 - num2
    val mult = num1 * num2
    val div = num2 / num2
    print(" A soma é: " + soma + ", a subtração é: " + sub + ", a multiplicação é: " + mult + ", a divisão é: " + div)
   
   
}
```
## Questão 24:⚽
```kotlin
fun main()
{
    var raio = readln().toDouble()
    var PI = 3.14159
    var raio3 = raio * raio * raio
    val volume = 4/3 * PI * raio3
    print("O volume da esfera é: " + volume)
   
   
   
}
```
## Questão 25:🔚
```kotlin
fun main()
{
    var num = readln().toDouble()
    val sucessor = num + 1
    val antecessor = num - 1
    print("O valor é: " + num + ", o sucessor é: " + sucessor + ", e o antecessor é: " + antecessor)
   
   
   
}
```
