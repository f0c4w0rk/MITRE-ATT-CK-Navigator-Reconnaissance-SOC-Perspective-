<h1 align="center">Detection Methodology – Reconnaissance (SOC Perspective)</h1> 
&emsp; Toda a análise deste projeto foi conduzida por um estudante, sob a perspectiva de um analista SOC com mentalidade Blue Team. O escopo do projeto é deliberadamente limitado às técnicas da tática Reconnaissance, utilizando exclusivamente o framework MITRE ATT&CK. Técnicas de Initial Access, Execution, Persistence e demais táticas não foram documentadas, pois não fazem parte do objetivo deste estudo.
<br/><br/>
&emsp; O projeto foi desenvolvido com finalidade educacional, visando compreender como adversários coletam informações antes de executar ataques e como essa fase pode ser observada e detectada por equipes defensivas.

#

### Por que Reconnaissance
&emsp; A fase de reconhecimento é geralmente o primeiro estágio da cadeia de ataque, caracterizada por baixa visibilidade e baixo impacto imediato. Entretanto, a detecção precoce de atividades de Reconnaissance pode reduzir significativamente o risco de comprometimento futuro, permitindo ações preventivas antes que o atacante avance para fases mais destrutivas.

#

### Critérios de Análise:
&emsp; Os seguintes critérios foram utilizados para mapear e avaliar as técnicas de Reconnaissance sob a perspectiva de um analista SOC:
- **Intenção do atacante:** *possíveis objetivos como coleta de dados sensíveis, identificação de infraestrutura, enumeração de usuários ou preparação para roubo de credenciais.*
- **Nível de ruído:** *dificuldade de distinguir a atividade maliciosa de tráfego legítimo ou comportamento normal de usuários e sistemas.*
- **Visibilidade para o SOC:** *nível de telemetria disponível para detectar a técnica (logs, SIEM, EDR, DNS, proxy, etc.).*
- **Impacto defensivo:** *consequências potenciais para a organização caso a técnica não seja detectada na fase de Reconnaissance..*

#

### Processo de Análise:
&emsp; O processo adotado para documentar as técnicas seguiu as etapas abaixo: 
1. **Identificação das técnicas no MITRE ATT&CK:** <br/>
*As técnicas da tática Reconnaissance foram identificadas utilizando o MITRE ATT&CK Navigator, filtrando o domínio Enterprise e listando todas as técnicas associadas.*

2. **Criação de layers no ATT&CK Navigator:** <br/>
*Foram criadas layers personalizadas no Navigator para classificar as técnicas, atribuir cores conforme o nível de risco e adicionar notas analíticas relevantes.*

3. **Documentação das técnicas:** <br/>
*Cada técnica foi documentada no diretório docs/, incluindo descrição, exemplos de uso por adversários, possíveis fontes de logs e ideias de detecção.*

4. **Exportação e versionamento:** <br/>
*As layers foram exportadas em formato JSON e adicionadas ao repositório GitHub como parte do portfólio técnico do projeto.*
