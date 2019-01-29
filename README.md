# micro-services-config-repo
Configuration repository for Micro Services. Accessed by Spring Cloud Config Server


Micro Serice URLs & Ports :



Currency Converter :
	Port :	8100
http://localhost:8100/currency-converter/proxy/from/USD/to/INR/quantity/20

Zuul API Gateway :
	Port	: 8765
	URL		: http://localhost:8765/{app-name}/{uri}
	
http://localhost:8765/currency-exchange-micro-service/currency-exchange/from/USD/to/INR
http://localhost:8765/currency-conversion-micro-service/currency-converter/proxy/from/USD/to/INR/quantity/200

H2 Console :
http://localhost:8080/h2-console/

Swagger :
http://localhost:8080/swagger-ui.html#/

HAL Browser :
Actuator 
http://localhost:8080/browser/index.html#/actuator
