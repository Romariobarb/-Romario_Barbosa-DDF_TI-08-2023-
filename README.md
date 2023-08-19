#### CASE-1
##### -É importante salientar que a coleta de uma variedade de fontes disponiveis pelos sistemas de atendimento gera um visão abrangente da experiência que o cliente tem com os atendimentos prestados.
##### -exemplos de dados que podem ser coletados: Formulários de pesquisa,e-mails, interações do suporte, dados de vendas e dados de marketing...
##### -Com a utilização desses serviços citados, eu iria rastrear a taxa de satisfação do cliente, tempo médio de resolução dos problemas, taxa de resolução no primeiro contato, taxa de abandono dos clientes ao serviço prestado sem resolver o problema e taxa de fidelização. Com esseas métricas identificaria areas onde pode ser melhorado a experiência do cliente, aumentar a satisfação e também identificar a eficiência e eficácia do suporte prestado.
##### -Para a melhoria do atendimento ao cliente é importante identificar padrões e tendencias, medir os resultados das ações, tomar as medidas para melhorar a satisfação e eficiencia e por fim, repetir o processo regularmente para melhorar continuamente.
####  CASE-2

-Configurar a solução MDM para atender às necessidades da Dadosfera. Isso incluirá a criação de usuários e grupos, o mapeamento de recursos e a configuração de políticas de segurança.
-Implementar a solução de gerenciamento de diretório em nuvem SSO. Depois de configurar a solução, implementa-la na Dadosfera envolverá a distribuição de dispositivos para seus usuários e a configuração de sua solução de gerenciamento de diretório em nuvem para gerenciar esses dispositivos.
-Para ter um implementação e transição eficientes é necessario treinar os usuários sobre o uso da solução de gerenciamento de diretório em nuvem. É importante para que eles saibam como acessar recursos, proteger seus dispositivos e cumprir as políticas de segurança.
-É importante monitorar sua solução de gerenciamento de diretório em nuvem para garantir que ela esteja funcionando conforme o esperado. Isso envolverá a verificação dos logs de auditoria, a execução de testes de penetração e a investigação de quaisquer alertas.

#### CASE-3
##### -Usar autenticação multifatorial (MFA). A MFA exige que os usuários forneçam mais de um fator de autenticação, como uma senha, um código de verificação ou uma impressão digital, antes de terem acesso a um recurso. Isso torna mais difícil para os invasores roubarem credenciais e acessar dados confidenciais.
##### -Implementar uma solução de gerenciamento de identidade e acesso (IAM). Uma solução de IAM ajudará a Dadosfera a gerenciar quem tem acesso a quais recursos e em que nível de acesso. Isso pode ajudar a proteger os dados contra acesso não autorizado.
##### -Usar uma solução de gerenciamento de dispositivos móveis (MDM) como foi citado anteriormente. Uma solução de MDM irá ajudar a Dadosfera a gerenciar dispositivos móveis, como smartphones e tablets, que são usados pelos funcionários. Isso pode ajudar a proteger os dados e a conformidade.
##### -Usar criptografia para proteger os dados. A criptografia torna os dados ilegíveis para qualquer pessoa que não tenha a chave de criptografia. Isso pode ajudar a proteger os dados contra acesso não autorizado, mesmo que os dados sejam roubados.
##### -Monitorar a  sua rede para atividades suspeitas. Você pode usar uma solução de monitoramento de rede para identificar atividades suspeitas na sua rede. Isso pode ajudar a detectar ataques antes que eles causem danos.
##### -Treinar os funcionários sobre segurança. Os funcionários são a linha de defesa mais importante contra ataques. É importante treinar os funcionários sobre segurança para que eles saibam como proteger seus dados e a rede da Dadosfera.

#### CASE-4
 -Usaria o chatbot para fornecer suporte ao cliente 24 horas por dia, 7 dias por semana. Os chatbots podem ser usados para responder a perguntas comuns, resolver problemas simples e fornecer suporte básico ao cliente. Isso pode liberar seus agentes humanos para lidar com questões mais complexas.
 -Coletaria feedback do cliente com essa ferramenta. Os chatbots podem ser usados para perguntar aos clientes sobre suas experiências, opiniões e preferências. Isso pode ajudá-lo a melhorar seus produtos, serviços e atendimento ao cliente.  
 -Promoveria os serviços da Dadosfera com os chatbots. Eles podem ser usados para responder a perguntas sobre produtos e serviços.

 #### CASE-5
 
##### SELECT email FROM user_emails
##### WHERE created_at > NOW() - INTERVAL 30 DAY;

A consulta primeiro seleciona todos os usuários na tabela "user_emails". Depois, ele usa a linha "WHERE" para filtrar os usuários cujo campo "created_at" é maior do que a data atual menos 30 dias. A data atual é retornada pela função NOW(). A linha "INTERVAL 30 DAY" é usada para adicionar 30 dias à data atual.
