# MenuSpanish
esta carpeta sera sobre escrita en la carpeta original de tu compilación reemplazando los ficheros 
existentes de sm64ex-coop, asi que primero ` REALIZAR LOS PASOS DE COMPILACIÓN. PARAR EN EL COMANDO (make) Y VOLVER AQUI PARA REALIZAR ESTE CAMBIO DE MENU PAUSA A TU JUEGO `

## proceso de ejecución
una vez realices tu proceso de descarga para compilar sm64excoop desde termux y antes de dsr make ejecutar estos comandos
### entrar a termux y poner
```
git clone https://github.com/XxCmbRxX/MenuSpanish.git
```
```
cd MenuSpanish
```
```
cp -r  sm64ex-coop ~
```
```
cd
```
```
cd sm64ex-coop
```
* aqui pondras cual sea de los dos comandos de compilación ya sea ` make ` o ` make -j$(nproc) ` si si alguno de los dos no te sirve ejecutar ` make clean ` y poner el otro.....

### comandos 

```
make
```

```
make -j$(nproc)
```
