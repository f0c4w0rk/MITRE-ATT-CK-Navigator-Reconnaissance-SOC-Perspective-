<h1 align="center">Detection Methodology – Reconnaissance (SOC Perspective)</h1> 
&emsp; Toda a análise do projeto foi efetuada por um estudante, na perspectiva <br/>
SOC baseado em Blue Team Mindset. O projeto analisa apenas as técnicas de <br/>
reconhecimento utilizando somente o web-framework da MITRE, o ATT&CK, não <br/>
foi documentado técnicas de Initial access, Execution, Persistence, entre <br/>
as outras táticas. <br/>
<br/>
&emsp; Trata-se de um projeto deliberadamente limitado fora da ideia teórica de <br/>
estudo e aprendizado na qual teve desde o início

#

### Por que Reconnaissance
&emsp; A fase de reconhecimento é o primeiro estágio dos atacantes, <br/> 
pois garante baixa visibilidade em comparação com outras táticas. <br/>
Se for detectado qualquer técnica da fase de reconhecimento, <br/>
reduz maiores riscos que poderiam ser causados.

#

### Critérios de Análise:
&emsp; Estes são os critérios seguidos por um analista SOC no <br/>
mapeamento das técnicas:
- **Intenção do atacante:** *roubar dados financeiros, <br/>
nomes, credenciais, etc...*
- **Nível de ruído:** *Dificuldade de identificar se é <br/>
uma ação maliciosa ou apenas uma requisição legítima confundida.*
- **Visibilidade para o SOC:** *A visibilidade diz o quão <br/>
difícil é detectar a técnica utilizada pelo atacante.*
- **Impacto defensivo:** *Quais impactos poderíam ter na <br/>
organização se não for detectado ainda na fase de reconhecimento.*

#

### Processo de Análise:
&emsp; 
- **Identificação das técnicas no MITRE:** *Foi utilizado o MITRE ATT&CK Navigator <br/>
no navegador, então foi filtrado por "Reconnaissance" e suas técnicas foram listadas.*
- **Criação de layer no Navigator:** *Criar layers "Enterprise", onde pode ser marcada <br/>
as técnicas com cores diferentes para classificar-las e adicionado notas.*
- **Exportação JSON:** *A layer pode ser exportada em arquivo JSON e adicionado em um <br/>
portfólio do GitHub.*
