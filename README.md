# Microservices + Spring Boot + Spring Cloud + Docker + Kubernetes

## URLS

#### Currency Exchange Service
- http://localhost:8000/currency-exchange/from/USD/to/INR

#### Currency Conversion Service
- http://localhost:8100/currency-conversion/from/USD/to/INR/quantity/10
- http://localhost:8100/currency-conversion-feign/from/USD/to/INR/quantity/10

#### Eureka
- http://localhost:8761/

#### Zipkin
- http://localhost:9411/

#### API GATEWAY
- http://localhost:8765/currency-exchange/from/USD/to/INR
- http://localhost:8765/currency-conversion/from/USD/to/INR/quantity/10
- http://localhost:8765/currency-conversion-feign/from/USD/to/INR/quantity/10
- http://localhost:8765/currency-conversion-new/from/USD/to/INR/quantity/10

## Docker Images

- Currency Exchange Service 
	- fnmabreu/microservice-currency-exchange-service:0.0.1-SNAPSHOT
- Currency Conversion Service
	- fnmabreu/microservice-currency-conversion-service:0.0.1-SNAPSHOT
- Eureka
	- fnmabreu/microservice-naming-server:0.0.1-SNAPSHOT
- API GATEWAY
	- fnmabreu/microservice-api-gateway:0.0.1-SNAPSHOT