# Phishing-Kali
Ferramentas:

  -Kali Linux
  
  -setoolkit

Configurando o Phishing no Kali Linux:

  -Acesso root: sudo su
  
  -Iniciando o setoolkit: setoolkit
  
  -Tipo de ataque: Social-Engineering Attacks
  
  -Vetor de ataque: Web Site Attack Vectors
  
  -Método de ataque: Credential Harvester Attack Method 
  
  -Método de ataque: Site Cloner
  
  -Obtendo o endereço da máquina: ifconfig
  
  -URL para clone: http://www.facebook.com

O site de login do Facebook implementa uma função que tira o hash das credenciais, e usa na comunicação, apenas esse hash. Portanto para vermos as credenciais em plain text, precisamos excluir esse script
![image](https://github.com/user-attachments/assets/94c79b91-b280-4694-b17d-a40f8100d1d4)
Para contornar isso, ao invés de clonar o site, passando o url diretamente pelo setools, devemos copiar seu código fonte, excluir o script, e salvar em uma pasta local. Depois utilizando a opção 3)Custom Import, escolhemos a página copiada, sem o script.
![image](https://github.com/user-attachments/assets/c39dee42-d84e-4b8e-a383-8618596ecf64)
