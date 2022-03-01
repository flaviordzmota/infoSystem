#infoSystem


##Python conversando com o Sistema Operacional


Esse código aponta que precisamos importar o pacote “platform” para obtermos informações como:


•platform(): método que retorna a distribuição exata do sistema operacional que  está  sendo  executado.Muito  útil  para  que  possamos  desenvolver ferramentas  de  inventário  ou  ferramentas  que  podem  servir  para  apontar computadores que não estão atualizados.

•system(): este método retorna simplesmente o sistema operacional que está sendo  executado.Isso  pode  auxiliar  sua  ferramenta  a  executar,  por exemplo,  comandos  de  Windows  no  Windows,e  comandos  do  Linux  no Linux, tornando-a multiplataforma.

•release():   retorna   a   versão   do   sistema   operacional   que   está   sendo executada.•architecture(): exibe a arquitetura que está em uso pela máquina.

•node(): retorna o nome do computador na rede. Mais uma vez,essa é uma informação muito importante para o inventário. Lembra quando nós fizemos uma ferramenta em que o usuário deveria digitar? Pois é, podemos deixar nossas ferramentas mais independentes do usuário e,consequentemente,com maior padronização e fidelidade dos dados recuperados.

•machine():  retorna  o tipo  da  máquina,  e  é  muito  utilizada  com  o  método processor(),que retorna o processadorque está sendo executado, o quepode ser muito útil,por exemplo, para providenciarmos atualizações sobre falhas de segurança para processadores de um fabricante em específico. Por  exemplo,  no  ano  de  2018,tivemos  a  divulgação  das  falhas  desegurança:   Meltdown   e   Spectre,representando vulnerabilidades   que podem  ser  exploradas  de  acordo  com  os  fabricantes  de  processadores, atingindo  os  maioresplayersde  mercado  como:  Intel,  Apple  e  AMD.A identificação do processador pode lhe permitir o direcionamento de patchsde atualização para cada computador que faz parte da sua rede corporativa.

•python_version():irá   retornar   a   versão   do   Python   que   está sendo executada. Esse método também pode ser muito importante para garantir a plena  execução  da  sua  ferramenta,  uma  vez  que  existe  uma  grande diferença entre o Python versão 2.x e o 3.x, além de diferenças menores entre as versões intermediárias.
