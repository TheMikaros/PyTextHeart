
   Para realizar la modificacion del codigo es necesario centrarse en la 3 linea de codigo.
   considera cambiar el 'NumberHere' por la cantidad de caracteres que quieras mostrar
```
([('TextHere'[(x-y)%NumberHere ]
```

To perform the modification of the code it is necessary to focus on the 3rd line of code.
consider changing the 'NumberHere' to the number of characters you want to display.
```
([('TextHere'[(x-y)%NumberHere ]
```


Example
```
print('\n'.join
 ([''.join
   ([('Merari'[(x-y)%6]
     if((x*0.05)**2+(y*0.1)**2-1)
      **3-(x*0.05)**2*(y*0.1)
       **3<=0 else' ')
        for x in range(-30,30)])
         for y in range(15,-15,-1)]))
```
![image](https://github.com/TheMikaros/PyTextHeart/assets/39964391/9d0a34e0-e03e-406b-8dee-adc51db869fc)
