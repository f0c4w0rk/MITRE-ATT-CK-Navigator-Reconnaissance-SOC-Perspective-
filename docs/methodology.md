# Detection Methodology – Reconnaissance (SOC Perspective)
Toda a análise do projeto foi efetuada por um estudante, na perspectiva SOC baseado em Blue Team Mindset. <br/>
> *(O projeto analisa apenas as técnicas de reconhecimento utilizando somente o web-framework da MITRE, o ATT&CK, não foi documentado técnicas de Initial access, Execution, Persistence, entre as outras táticas. Trata-se de um projeto deliberadamente limitado fora da ideia teórica de estudo e aprendizado na qual teve desde o início)*

## Por que Reconnaissance
A fase de reconhecimento é a primeira façanha dos atacantes, pois garante baixa visibilidade em comparação com outras táticas.
Se for detectado qualquer técnica da fase de reconhecimento, reduz maiores riscos que poderiam ser causados.

## Critérios de Análise:
- ##### Intenção do atacante: roubar dados financeiros, nomes, credenciais, etc... 
- ##### Nível de ruído: 
- ##### Visibilidade para o SOC: Quão difícil é detectar a técnica escolhida.
- ##### Impacto defensivo: Quais impactos poderíam ter na organização se não for detectado.

## Processo de Análise:
- ##### Identificação das técnicas no MITRE
- ##### Criação de layer no Navigator
- ##### Documentação no diretório docs
- ##### Exportação JSON
