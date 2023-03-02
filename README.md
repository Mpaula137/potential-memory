  # RETO #4: navegando por codigos desconocidos y peligrosos
  
En este repo mostrare el proceso que costo mucho pensar y plasmar por este medio, en este reto e nos pedia realizar un pseudocodigo y luego de este crear un diagrama de flujo
A continuacion les mostrare mi humilde intento
   
   ## ALGORITMO PARA NUMEROS PRIMOS
Primero hice un algoritmo en el cuaderno el cual es un tipo de borrador para despues intentar hacer el pseudocodigo de la mejor manera posible, por el momento senti un avance haciendolo y creo que logre entender mas al fondo.
 
 ```
 [variables]
 i:entero
 grupo k: numeros multiplos del numero tomado
 n: int
  [Inicio]
 1. Hacer una lista de numeros comprendidos entre 2 y n
 2. Se toma el primer numero en este caso i:2
     si (i ∈ Grupo k) hacer
     remove(Grupo K)
  3. Se revisa que el siguiente numero despues del numero primo
   si i>n 
     print ("logaritmo terminado")
   sino i<n
    print (i)
    i: n+1
    [fin]
    
  ```
    

[![](https://mermaid.ink/img/pako:eNpVkktvwjAQhP_KyqcgwYUjh0otoYU-OLTcCIdVbMCtY6d-tKIR_71jmlIaKfJmdzz5xkknaieVmIitcZ_1nn2kVVlZouviWbHRX-wpWSajQ2SSimxqlHeBate0XlmpJZOy0Ssa0wHSXkB2MBpd3axXroGDMr_t8SabYzTtZoGaZKJujYPxWRGxQ7ojJGURNKk_1aCyU7RnhXX_2ujdroOCyWtmIdPj4lUlZnd55lXU_hTgPMVoXpxGHzpwZgx6lzTC_Ka8lNN7QtsRNuz5kB91BCeYbrNRZedYFt3snIMN1Ymlh-hEywfnicnmZPdIhp0LlA_FMpvco3zMoDn-33llyGk-MVwPqJ_W1-AwBh8g8-CWbC8zI4P9YfMnWmfP5xQ2vdETjJZFCxycfGQbf3St140Lg17UL7jEUAClYS3xm3S5X4m4V42qxASlZP9WicoeoeMU3cvB1mISfVJDkVrJUZWad54bMdmyCer4DXNo0XQ?type=png)](https://mermaid.live/edit#pako:eNpVkktvwjAQhP_KyqcgwYUjh0otoYU-OLTcCIdVbMCtY6d-tKIR_71jmlIaKfJmdzz5xkknaieVmIitcZ_1nn2kVVlZouviWbHRX-wpWSajQ2SSimxqlHeBate0XlmpJZOy0Ssa0wHSXkB2MBpd3axXroGDMr_t8SabYzTtZoGaZKJujYPxWRGxQ7ojJGURNKk_1aCyU7RnhXX_2ujdroOCyWtmIdPj4lUlZnd55lXU_hTgPMVoXpxGHzpwZgx6lzTC_Ka8lNN7QtsRNuz5kB91BCeYbrNRZedYFt3snIMN1Ymlh-hEywfnicnmZPdIhp0LlA_FMpvco3zMoDn-33llyGk-MVwPqJ_W1-AwBh8g8-CWbC8zI4P9YfMnWmfP5xQ2vdETjJZFCxycfGQbf3St140Lg17UL7jEUAClYS3xm3S5X4m4V42qxASlZP9WicoeoeMU3cvB1mISfVJDkVrJUZWad54bMdmyCer4DXNo0XQ)


## ALGORTIMO DE RAIZ CUADRADA
Vamos a crear un pseudocodigo explicando el procedimiento matematico para hallar raice cuadradas,
iremos a pedir ayuda a google academico ya que necesitare una guia para realizar el algoritmo
encontre el metodo el cual utilizare como base para crear el algoritmo, el enlace de la pagina lo dejare aqui :https://www.matesfacil.com/ESO/numeros/raices/calcular-raiz-cuadrada-metodo-ejemplos-decimales-exacto-pasos.html
Para lograr esto necesite un pseudocodigo y este fue el que logre realizar:

```
[variables]
i :entero
n: entero
b: entero

[INICIO]
Si (n ∈ R ) entonces
 
 1. Agrupamos a n en pares y si es impar agregamos un o al principio de la raiz
 2. Buscamos un numero cuyo cuadrado se aproxime al primer par
  b= netero ( raiz cuadrada (Grupo[1])
   res= Grupo[1] - b**2
   resultado = [a]
 3. repetimos este proceso hasta que no hallan pares y que el resultado de la diferencia de 0
 si e4s el caso contrario sacamos decimales
   res= res*100 + grupos[1]
   4. si no es cero escribimos una coma y bajamos un par de ceros para continuar 
   5. trataremos de encontrar asi sea minimo 3 decimales despues
   
         [FIN]
    
 ```

 

Entrare a mermaid live editor y realizare el algoritmo que pondre a continuacion:

[![](https://mermaid.ink/img/pako:eNq9lMlOG0EQhl-lNScjmYizD5FYnEWEEIncxhzKPYVppxfTC4lBPEyeIbdcebH81eOxHUSukSxP90wtX_1V3Y-NDh03k-bGhu_6lmJWX89mXqnj9ngRy4pcSMpSUtrcRDzYqxVFTqpj_CLDRZEyD3fFcOxorJJR-GocrBRbVWw2LsDE7lmpu8IdRVIp2HAt2Q4P3560JyXpmg9-jtYhKv_823EMSpe1_FEXqQsqsaJVDD-Mw8KqVTTVCEQWzhVvLLtdPhpYh2Sn7afCi-rDXgefY4_rSw1lA4rQ0cxNxfFCj7h5V_NapbIj6nhOS3lsI4ALRQqq3dJuSz0babK62I24CsCZKkvKeNOFdLCxnLbTPQ6LT3PLtVJ4kXkYljUAOIvH2i9s8ADh-_Aa-0Dxrj2h5aB3Mgto5WFVG7fntVVx8Hv_Pxv14YUAcMFISfBXGdGXyGTNQ8UrfiPNEO1jO61eQxd7xXqlet3SX43fE7yHH9S9RrDlP_WTr1NJucTi_PG0kAewD-qW1hBsU7oK88TxvkaQU9MXV2vL5OZGCsSIyF6KkJFUR0-IaEfJ1AE5x-Zi5EPdWGw-t1cCm-HLal3P2d5Uh3lmb3rp2L6oqA6v7YdZxKkjvBtwqnzUGS21QM8LpLvcb46IrYOjV6I___JozAoXjRjiqGDESr1IRFkNtrSR7BKPLyM0qZOsmlKoNfg6NEcSeiMFumb8QoIUn8N4Gzwx-hBrDtF8e1fVJICoGoDLPf-U99o4spzeHDTjBriOTIe78FH0nDX5lh3PmgmWuK2-zZqZf4IdlRyu1l43kxwLj5uy6ijzmaFFJNdMbsgmfvoD8vnisg?type=png)](https://mermaid.live/edit#pako:eNq9lMlOG0EQhl-lNScjmYizD5FYnEWEEIncxhzKPYVppxfTC4lBPEyeIbdcebH81eOxHUSukSxP90wtX_1V3Y-NDh03k-bGhu_6lmJWX89mXqnj9ngRy4pcSMpSUtrcRDzYqxVFTqpj_CLDRZEyD3fFcOxorJJR-GocrBRbVWw2LsDE7lmpu8IdRVIp2HAt2Q4P3560JyXpmg9-jtYhKv_823EMSpe1_FEXqQsqsaJVDD-Mw8KqVTTVCEQWzhVvLLtdPhpYh2Sn7afCi-rDXgefY4_rSw1lA4rQ0cxNxfFCj7h5V_NapbIj6nhOS3lsI4ALRQqq3dJuSz0babK62I24CsCZKkvKeNOFdLCxnLbTPQ6LT3PLtVJ4kXkYljUAOIvH2i9s8ADh-_Aa-0Dxrj2h5aB3Mgto5WFVG7fntVVx8Hv_Pxv14YUAcMFISfBXGdGXyGTNQ8UrfiPNEO1jO61eQxd7xXqlet3SX43fE7yHH9S9RrDlP_WTr1NJucTi_PG0kAewD-qW1hBsU7oK88TxvkaQU9MXV2vL5OZGCsSIyF6KkJFUR0-IaEfJ1AE5x-Zi5EPdWGw-t1cCm-HLal3P2d5Uh3lmb3rp2L6oqA6v7YdZxKkjvBtwqnzUGS21QM8LpLvcb46IrYOjV6I___JozAoXjRjiqGDESr1IRFkNtrSR7BKPLyM0qZOsmlKoNfg6NEcSeiMFumb8QoIUn8N4Gzwx-hBrDtF8e1fVJICoGoDLPf-U99o4spzeHDTjBriOTIe78FH0nDX5lh3PmgmWuK2-zZqZf4IdlRyu1l43kxwLj5uy6ijzmaFFJNdMbsgmfvoD8vnisg)

## Este fue mi humile intento, pronto veran otro en un nuevo reto.
