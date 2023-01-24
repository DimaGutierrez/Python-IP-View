# Python-IP-View
![https://github.com/dimagutierrez](https://github.com/DimaGutierrez/Python-IP-View/blob/main/ipview.png)
</br>

## Run IP View >
`BuscarIP.py`

```
import socket

hostname = socket.gethostname()
ip = socket.gethostbyname(hostname)

print("El nombre de tu ordenador es: " + hostname)
print("Tu direccion de IP es: " + ip)

```

## Run Port Scanner >
`Port Scanner.py`

```
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
     print("\n Saliento...")
     sys.exit(0)

```
