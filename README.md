# GEs FIWARE para a plataforma SWAMP

## Utilizando os serviços 

Para utilizar os serviços basta clonar este repositório em seu ambientew de trabalho e uilizar o seguinte comando para iniciar os serviços. 

```bash
docker-compose up -d
```
Com este comando os serviços devem ser iniciados. Ao final da inicialização execute o comando a seguir para a confirmação de que todos os serviços estajam em execução. 


```bash
docker-compose ps
```

A seguinte tela deve ser apresentada. 

![screen shot 2019-02-11 at 20 51 29](https://user-images.githubusercontent.com/9273551/52599240-3ba50a80-2e3f-11e9-85d7-e5583fea1bf2.png)


## Serviços configurados 

- Orion Context Broker 
- Mongo DB
- Quantum Leap
- Crate DB
- Grafana 
- Redis
- IoT-Agent JSON
- NGSI-LD Wrapper

<img width="890" alt="swamp_platform_architeture_v1 2 0" src="https://user-images.githubusercontent.com/9273551/53274350-b559b580-36d5-11e9-9be5-5b8898486418.png">

## Dashboard

Este repositório também possuí um tamplate de dashboard para o grafana como o apresentado abaixo. 

![screen shot 2019-02-25 at 12 56 22](https://user-images.githubusercontent.com/9273551/53349895-d51ef280-38fc-11e9-9d18-4977ca684d3a.png)