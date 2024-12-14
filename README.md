Membros: 

Anisio Ferreira

Giovanni Gava

Julio Vicente

Evidencia captura das metricas de monitoramento do Prometheus e captura da tela do Loki 


<img width="1080" alt="image" src="https://github.com/user-attachments/assets/a29512cb-1a6f-45a6-a910-f6dfd726a150" />

![alt text](image.png)

Script de teste testando um endpoint GET da aplicação Flask com 1 thread e 100 requisições, com espaço de 10 milisegundos por disparo


![image](https://github.com/user-attachments/assets/ce1b1f55-5c80-47d6-8323-c2533f53907c)

![image](https://github.com/user-attachments/assets/2128cbbc-100e-49d7-b87b-ce5b366caa8e)

![image](https://github.com/user-attachments/assets/fad7cd1d-c057-446e-be35-bd556fd0e33f)

![image](https://github.com/user-attachments/assets/73c24191-8d7a-4e4c-b0e9-9853e1ee65ec)



Script de teste testando um endpoint GET da aplicação Flask com 100 thread e 100 requisições, com espaço de 10 milisegundos por disparo

<img width="1080" alt="image" src="https://github.com/user-attachments/assets/61118956-e40e-4ea5-befe-5ac3ca1d4296" />

![image](https://github.com/user-attachments/assets/94a98ded-a6be-44be-8f13-fa23e3f011ec)

![image](https://github.com/user-attachments/assets/30ece2f1-ccaf-4afd-96e6-406fb3daee34)

![image](https://github.com/user-attachments/assets/77a7d121-685e-4475-adf4-99344ac7691f)

![image](https://github.com/user-attachments/assets/8266cd98-0754-4b70-8022-dc0cc31b8ba7)


Script de teste testando um endpoint POST da aplicação Flask com 100 thread e 100 requisições, com espaço de 10 milisegundos por disparo.








# Montoramento de Sistemas - Projeto Final

Neste projeto final vocês podem formar as mesmas equipes do proejto anterior.
A ideia é configurar um serviço de monitoramento ativo e passivo para uma aplicação backend!

Monitoramento Passivo - Usando o Prometheus e Grafana
Monitoramento Ativo - Usando o JMeter

1) Elaborar um repositório para monitoramento ativo contendo

 - Uma instância do Prometheus
 - Uma instância do Loki
 - Uma instância do Grafana
 - Uma aplicação Flask realizando operações CRUD em uma tabela de BD (GET, POST e DELETE)
 - Monitoramento da aplicação com o módulo do Prometheus (metrics)
 - Logs da aplicação com o módulo de logs do Python

 Vocês podem se basear no repositório: https://github.com/gmcalixto/flask_loki

Além da elaboração do projeto, devem ser coletadas as seguintes evidências (pode ser por prints e depois enviado ao repositório)
 - Geração de logs
 - Explore ou Dashbord de uma das métricas enviadas pelo Prometheus.
 - Explore ou Dashboard de uma das métricas geradas pelo Loki.

2) Elaborar um repositório com monitoramento passivo com JMeter contendo

 - Uma instância do JMeter
 - Script de teste testando um endpoint GET da aplicação Flask com 1 thread e 100 requisições, com espaço de 10 milisegundos por disparo. 
 - Script de teste testando um endpoint GET da aplicação Flask com 100 thread e 100 requisições, com espaço de 10 milisegundos por disparo.
 - Script de teste testando um endpoint POST da aplicação Flask com 100 thread e 100 requisições, com espaço de 10 milisegundos por disparo.

Abrir o resultado de cada teste, capturar três gráficos e adicionar ao repositório.


  - Vocês podem se basear no repositório https://github.com/gmcalixto/jmeterdevops


  Toda entrega deve ser realizada em um único repositório do grupo.
