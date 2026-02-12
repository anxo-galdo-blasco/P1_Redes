# P1_Redes

La URL completa y funcional del subdominio es : [a link] (https://galdo-blasco-anxo.mooo.com)

Captura del Tráfico: 
He aplicado el filtro "(dns.qry.name == "galdo-blasco-anxo.mooo.com" && dns.qry.type == 1) || (dns.resp.name == "galdo-blasco-anxo.mooo.coms" && dns.resp.type == 1)" en Wireshark sobre el tráfico del adaptador correspondiente a WiFi
(Este filtro utiliza una query buscando el nombre del subdominio en DNS y luego muestrea si es una petición o una respuesta). Tuve que pedirle a una IA Generativa la segunda parte para acotar a que sólo me saliesen la petición y la respuesta específicas.


<img width="1918" height="587" alt="Trafico" src="https://github.com/user-attachments/assets/fb5dc4f4-d679-43d8-a59c-890d0a972b34" />
