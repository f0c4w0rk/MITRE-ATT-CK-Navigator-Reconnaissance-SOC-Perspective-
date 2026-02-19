## 1.	Escopo e Premissas
&emsp;	Todo o projeto é articulado num modelo home lab windows pessoal. Não estamos falando de ambientes Corporativos Cloud,	<br/>
SIEM (Security Information and Event Management), infraestrutura corporativa, sistemas reais em funcionamento, etc.

&emsp;	**1.1.  Por que esses ambientes não estão incluso no projeto?** <br/>
&emsp;	&emsp; Porque seria mentira, não tenho acesso a esses sistemas e ambientes.

## 2.  Suposições tomadas pelo Projeto:
&emsp;	O projeto supõe um ambiente corporativo simplificado com um Endpoint Windows, que assume a telemetria básica disponível. O projeto também supõe que o atacante tenha inicialmente apenas acesso externo ao ambiente "corporativo", realizando táticas de reconnainssance como Active scanning (port scanning, service discovery), DNS enumeration, OSINT e footprinting, etc.

&emsp;	**2.1. Por que essas suposições?**	<br/>
&emsp;	&emsp;	Novamente: porque o projeto é focado em engenharia de detecção apenas da tática de reconnaissance.
