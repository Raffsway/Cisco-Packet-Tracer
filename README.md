# Static Route: Packet Tracer
Projetei esta rede hipotética com o objetivo de estudos. Utilizando roteamento estático e conceitos de sub-redes, tentei elaborar um laboratório com o seguinte cenário.
Crie uma infraestrutura em uma rede na qual tinha como objetivo conectar os departamentos a sub-redes distintas. Essa minha ideia surgiu com finalidade de promover segurança e reduzir o numero de hosts disponiveis a fim de promover uma melhor qualidade de gerenciamento de IP's. Com isso, apenas uma quantidade estabelecida de hosts podem estar contida dentro da sub-rede, como veremos posteriormente.
## Departamentos: 3
Cada Switch representa um departamento.
  - Departamento: A
  - Departamento: B
  - Departamento: C
## Roteadores: 3
  - Roteador - A
  - Roteador - B
  - Roteador - C
## Endereçamento: Classe C
Os enderementos foram divididos da seguinte forma:

### Departamento: A		   
  - Int: 192.168.100.0 até 192.168.100.7           
  - Rede: 192.168.100.0
  - Broadcast: 192.168.100.7
  - Hosts disponiveis: 6
    
### Departamento: B
  - Int: 192.168.100.8 até 192.168.100.15
  - Rede: 192.168.100.8
  - Broadcast: 192.168.100.15
  - Hosts: 6
    
### Departameto: C
  - Int: 192.168.100.16 até 192.168.100.23
  - Rede: 192.168.100.16
  - Broadcast: 192.168.100.23
  - Hosts: 6

### Roteador: A
	- Int: 200.168.100.0 até 200.168.100.3
 	- Rede: 200.168.100.0
	- Broadcast: 200.168.100.3
  - Hosts disponiveis: 2
    
### Roteador: A
	- Int: 200.168.100.0 até 200.168.100.3
 	- Rede: 200.168.100.0
	- Broadcast: 200.168.100.3
  - Hosts: 2
  
