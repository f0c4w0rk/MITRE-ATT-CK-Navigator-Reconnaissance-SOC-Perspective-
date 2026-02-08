# Detection Methodology – Reconnaissance (SOC Perspective)
Toda a análise do projeto foi efetuada por um estudante, <br/>
na perspectiva SOC baseado em Blue Team Mindset. O projeto analisa <br/>
apenas as técnicas de reconhecimento utilizando somente o web-framework <br/>
da MITRE, o ATT&CK, não foi documentado técnicas de Initial access, <br/>
Execution, Persistence, entre as outras táticas. <br/>
Trata-se de um projeto deliberadamente limitado fora da ideia <br/>
teórica de estudo e aprendizado na qual teve desde o início

#

### Por que Reconnaissance
A fase de reconhecimento é o primeiro estágio dos atacantes, <br/> 
pois garante baixa visibilidade em comparação com outras táticas. <br/>
Se for detectado qualquer técnica da fase de reconhecimento, <br/>
reduz maiores riscos que poderiam ser causados.

#

### Critérios de Análise:
Estes são os critérios seguidos por um analista SOC no <br/>
mapeamento das técnicas:
- ##### Intenção do atacante: roubar dados financeiros, <br/>
nomes, credenciais, etc... 
- ##### Nível de ruído: Dificuldade de identificar se é <br/>
uma ação maliciosa ou apenas uma requisição legítima confundida.
- ##### Visibilidade para o SOC: A visibilidade diz o quão <br/>
difícil é detectar a técnica utilizada pelo atacante.
- ##### Impacto defensivo: Quais impactos poderíam ter na <br/>
organização se não for detectado ainda na fase de reconhecimento.

#

### Processo de Análise:
- ##### Identificação das técnicas no MITRE :
- ##### Criação de layer no Navigator
- ##### Documentação no diretório docs
- ##### Exportação JSON
