<!--- Objetivo do projeto --->
# O Que É o Projeto?
&emsp; O Projeto MITRE ATT&CK Navigator é um mapeamento defensivo de técnicas da tática **Reconnaissance**, desenvolvido sob a perspectiva de um **SOC Analyst**. <br/>
&emsp; Sua estrutura consiste em uma **custom layer** criada por mim. Essa layer é utilizada para **gap analysis** entre as técnicas de Reconnaissance do **MITRE ATT&CK**, fontes de logs, métodos de detecção realistas e o que realmente pode ser detectado em um ambiente corporativo típico, incluindo técnicas que permaneceriam invisíveis para um SOC. Além disso, na pasta `docs` estão documentadas as premissas do **threat model**, limitações e a **detection logic** seguida por uma equipe **Blue Team**, bem como a avaliação de **defensive coverage**.<br/>
&emsp; Este projeto desenvolve um **engineering mindset** focado na fase inicial da **attack chain**, mapeando **telemetry sources**, possíveis detecções e **blind spots**. Além disso, serve como demonstração de portfólio, exibindo cada técnica específica do ATT&CK e documentando-as em um **defensive operational model**.
<br/>

## O Que o Projeto Não É:
Definição dos limites do projeto:  <br/>
- *Não se trata de uma implementação real de SOC.*  <br/>
- *Não é uma detecção de produção (production detection).*  <br/>
- *Projeto de pesquisa educacional (research-oriented).*  <br/>

Mais informações sobre as limitações estão no arquivo `limitations.md`, dentro da pasta `docs`.
