<!--- Objetivo do projeto --->
# Visão Geral do Projeto:

&emsp; O Projeto MITRE ATT&CK Navigator é um mapeamento defensivo de técnicas da tática Reconnaissance, efetuado na perspectiva defensiva Blue Team. <br/>

&emsp; Sua estrutura consiste em uma layer personalizada criada por mim. Essa layer é utilizada para gap analysis entre as técnicas de Reconnaissance do MITRE ATT&CK e fontes de logs, métodos de detecção realistas, o que pode ser detectado em um ambiente corporativo típico e quais técnicas ficariam invisíveis para um SOC. Além disso, na pasta "docs" estão documentadas as premissas do threat model, limitações e a lógica de detecção seguida por uma equipe Blue Team, incluindo a avaliação de detection coverage. <br/>

&emsp; Esse projeto desenvolve um engineering mindset focado na fase inicial da kill chain, mapeando telemetry sources, possíveis detecções e blind spots. Além disso, serve como demonstração de portfolio, exibindo cada técnica específica do ATT&CK e documentando-as em um modelo defensivo operacional.
<br/>

## O Que O Projeto Não É:

Definição de limites do projeto: <br/>
- *Não se trata de uma implementação real de SOC.* <br/>
- *Não é uma detecção de produção.* <br/>
- *Projeto de pesquisa educacional.* <br/>
- *Sem SIEM real* <br/>

Mais informações sobre os limites do projeto estão no arquivo "limitations.md", dentro da pasta "docs".

## Objetivo do Projeto:

&emsp;  O objetivo central do projeto são:
- *Mapear técnicas de Reconnaissance, identificando as principais práticas que os atacantes utilizam na primeira fase da kill chain.* <br/>
- *Identificação de telemetry sources relevantes para detecção.* <br/>
- *Avaliar detection coverage e documentar detecções hipotéticas.* <br/>
- *Documentar boas práticas para detectar potencial ataque ou falsos positivos.* <br/>

## Estrutura do Repositório:

A estrutura do projeto e os conteúdos de cada parte:

- */layers - ATT&CK Navigator layer (.json).* <br/>
- */docs - "threat model", "methodology", "detection rationale" e "limitations".* <br/>
- */docs/techniques - documentação de técnica por técnica da tática reconnaissance.* <br/>
- *README.md - Visão Geral do Projeto.*
