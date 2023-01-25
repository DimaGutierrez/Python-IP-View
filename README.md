# Python-IP-View
![https://github.com/dimagutierrez](https://github.com/DimaGutierrez/Python-IP-View/blob/main/ipview.png)
</br>

## Run IP View >
`BuscarIP.py`

Code:
```Ruby
import socket

hostname = socket.gethostname()
ip = socket.gethostbyname(hostname)

print("El nombre de tu ordenador es: " + hostname)
print("Tu direccion de IP es: " + ip)

```

## Run Port Scanner >
`Port Scanner.py`

Code:
```Ruby
import sys
import socket

objetivo = socket.gethotname(imput("Inserte la direccion IP: "))

print("Escaneando objetivo: " + objetivo)

try:
    for port in range(1,150)
        s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
        socket.setdefaulttimeout(1)
        resultado = s.connect_ex((objetivo, port))
        if resultado == 0:
            print("El puerto {} esta abierto".format(port))
        s.close()
except:
     print("\n Saliendo...")
     sys.exit(0)

```
<br> <br>

[![Python](https://img.shields.io/badge/Python-0095D5?style=for-the-badge&logo=Python&logoColor=white&labelColor=101010)]()
<br>

## Portfolio:
[![Wix](https://img.shields.io/badge/wix🔥🔥🔥-DIMA>>JOBBOX-FA7343?style=for-the-badge&logo=Wix&logoColor=white&labelColor=101010)](https://diegosurf.wixsite.com/diegorgutierrez)
<br>

## Contacto:
[![Email](https://img.shields.io/badge/diegorgutierrez@live.com.ar-email_personal-FA7343?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](mailto:diegorgutierrez@live.com.ar)
</br>
