# Desvendando o mistério da imagem
![Desafio](https://scontent.fcpq8-1.fna.fbcdn.net/v/t1.0-9/93570806_2861867407237361_6692581936579215360_n.jpg?_nc_cat=103&_nc_sid=110474&_nc_eui2=AeG9hVdI-USMOV20tdNaw6DUVMnn0eG9qyFUyefR4b2rIfbst57BabNv9fCctwa9VOM&_nc_ohc=Qa1zN8BJBcgAX9sRnq4&_nc_ht=scontent.fcpq8-1.fna&oh=a4dc464011b390462e474d6bb56151ad&oe=5EBFC771)

Desvendando valor de Tigre
```python
tigre = 30 / 2;
print ("tigre=", tigre)
```
    tigre= 15.0
    
Desvendando valor de Gato
```python
gato = 12/2
print("gato=", gato)
```
    gato= 6.0

Desvendando valor de Rato
Esse tem que ligar o teco, prestar atenção na ordem (multiplicação primeiro), vamos na "tentativa e erro" até descobrir o valor
```python
rato = 1  # testando com rato igual a 1 e esperando como resultado 12
print (rato + (rato*3))
```
    4
```python
rato = 2  # testando com rato igual a 2 e esperando como resultado 12
print (rato + (rato*3))
```
    8
```python
rato = 3  # testando com rato igual a 3 e esperando como resultado 12
print (rato + (rato*3))
```
    12
Achamos o valor - Rato = 3, vamos fazer a subistituição da ultima linha, lembrando da pegadinha que observando a imagem, percebemos que temos um tigre+gato (olha o rabo levantado do gato) e depois um (gato+tigre) observando o rabo pra baixo no gato
```python
resultado = (gato+tigre) + ((gato+tigre)*rato)
print(resultado)
```
    84.0
