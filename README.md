# Lista 1
### Exercício lista Kotlin


1- Construa um programa que calcule o IMC – Índice de Massa Corporal e ainda exiba a classificação de acordo com a tabela de classificação da OMS.


fun main() {

    val peso = 45

    val altura = 1.56

    

    val imc = peso / (altura * altura)

    

    if (imc < 18.5){

        print(" $imc = Peso baixo")

    } 

    else if(imc > 18.5){

        print(" $imc = Peso normal")

    }

    else if(imc > 25){

        print(" $imc = Sobrepeso")

    }

    else if(imc >30){

        print(" $imc = Obesidade")

    } 

}


2) a)

fun main() {

    val largura =

    val altura =

    

    val area = largura * altura

    print("$area metros quadrados")

}

b)

fun main() {

    val area = 30

    val mestres  = 1

    val serventes = (area / 10) * 2

    val engenheiro = (area / 100)


    if (area < 10) {

        println("Área insuficiente para contratação")

    } else if (area >= 10 && area < 100) {

        println("$mestres e $serventes")

        

    } else if (area >= 100)

    println("$mestres, $serventes e $engenheiro")

}

c)

fun main() {

    val area = 100

    val valor_area = (area/10) * 4500

    val sem_suite  = 12000

    val area_servico = 15000

    val piscina = 27550

    val com_suite = 17000

    val banheiro = 5000


    val valor_total =valor_area + sem_suite + area_servico + piscina + com_suite + banheiro

    

    println("O valor total é: $valor_total")

}

d)

fun main() {

    val comprimento = readIn().toDouble()

    val largura = readIn().toDouble()

    

    var area = comprimento * largura

    var mestres = 1

    var serventes = (area / 10) * 2

    var engenheiros = area / 100

    

    var valor_mestre = mestre * 3500

    var valor_serventes = serventes * 1900

    var valor_engenheiros = engenheiros * 11000

    var valor_trabalho = valor_engenheiros + valor_serventes + valor_mestres

    

    println("Valor total da mão de obra: $valor_trabalho")

}

e)

fun main() {

    val comprimento = readIn().toDouble()

    val largura = readIn().toDouble()

    

    var area = comprimeto * largura

    var mestres = 1

    var serventes = (area / 10) * 2

    var engenheiros = area / 100

}
