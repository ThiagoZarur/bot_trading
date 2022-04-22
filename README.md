# bot_trading 
The code it´s on the branch master
El codigo esta en la rama master

This is a trading bot develop in python for Binance exhange

English:
## Entry for longs and shorts signals
This is a trading bot tasked with spotting a moving average crossover (SMA) for your entry.
If it crosses the 20-period moving average to the 30-period moving average, we buy or if it crosses the 20-period moving average to the 200.
If it crosses the 20-period moving average down to the 30-period moving average, we sell or if it crosses down the 20-period moving average to the 200.
## Take profit
We have our take profit with moving average crossovers for long.
If the 8-period moving average crosses to the 20-period low, or if price its equal to 200-period moving average we close our long.
We have our take profit with moving average crossovers for short.
If the 8-period moving average crosses to the 20-period upside, or if price its equal to 200-period moving average we close our short.

Español:
## Señales de entradas para longs y shorts
Este es un bot de trading encargado de detectar un cruce de medias móviles (SMA) para su entrada.
Si cruza a la alza la media móvil de 20 periodos a la de 30, o si la media móvil de 20 cruza a la alza de 200, compramos.
Si cruza a la baja la media móvil de 20 periodos a la de 30, o si la media móvil de 20 cruza a la baja la 200, vendemos.
## Take profit 
Tenemos nuestra toma de ganancias con cruces de medias móviles para long.
Si la media móvil de 8 periodos cruza a la baja de 20 periodos, o si el precio es igual a la 200, cerramos nuestro long.
Tenemos nuestra toma de ganancias con cruces de medias móviles para short.
Si la media móvil de 8 periodos cruza a la alza de 20 periodos, cerramos nuestro short.

## Binance SET-UP
-    Create a Binance account, verify it and put the 2FA authenticator on it
-    Create your API KEY so you can access all the features of the bot
-    Select your favorite cryptocurrency and wait for notifications

-    Crea una cuenta de Binance, verificala y ponle el autenticador 2FA
-    Crea tu API KEY para que puedas acceder a todas las funcionalidades del bot
-    Selecciona tu criptomoneda favorita y espera las notificaciones 

##Install python dependencies 

Run the following line in the terminal: `pip install -r requirements.txt`.

Corre el siguiente comando en tu terminal para instalar las dependencias necesarias `pip install -r requirements.txt`.

## Run code

Run with the next line in the terminal: `py simple_sma.ipynb`.

Corre el siguiente comando en tu terminal para correr el código: `py simple_sma.ipynb`.
