# pyTiProxy


## INSTALL

`git clone https://github.com/Vaelio/pyTiProxy.git`

### Note: 

- In order to use SSL, makebecause of socket serialization
- SSL features will work only in reverse proxy scenario
- python3 is mandatory 

## USAGE
    usage: proxy.py [-h]  sure openssl is installed on your system
                    [--ssl [Enable SSL]]
                    [--address [address of interface that should listen]]
                    [--port [Port that should be LISTENING]]
                    [--crt [crt file for ssl purpose]]
                    [--key [key file for ssl purpose]]

    pyTiProxy is a reverse proxy / transparent proxy for lulz :)

    optional arguments:
      -h, --help            show this help message and exit
      --ssl, -s
      --address [IP address of interface that should listen], -i [IP address of interface that should listen]
      --port [Port that should listen], -p [Port that should listen]
      --crt [crt file for ssl purpose], -c [crt file for ssl purpose]
      --key [key file for ssl purpose], -k [key file for ssl purpose]



