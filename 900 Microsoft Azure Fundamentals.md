# 900: Microsoft Azure Fundamentals Perguntas e respostas

1. o que é a plataforma Microsoft Azure? 

é uma plataforma de computação em nuvem com um conjunto de serviços em constante expansão para ajudar você a criar soluções para atingir suas metas de negócio.

2. Quais são os serviços disponíveis?

- armazenamento remoto;
- hospedagem de bando de dados;
- gerenciamento de contas;
- IA (inteligência artificial) e serviços de IoT(internet das coisas)

3. O que é computação em nuvem?

É a entrega de serviços de computação pela internet e esta restrita pela infraestrutura física, já que faz uso de internet. As vantagens são que você pode solicitar aumento dos recursos apenas ajustando o serviço comprado a sua demanda ao invés de investir em novos equipamentos servidores e ter que lidar com as possíveis demandas de manutenção do mesmo.

4. O que é o modelo de responsabilidade compartilhada.

Esse conceito se fundamenta em dividir as responsabilidades pelo serviço, uma vez que o consumidor não precisará mais manter esse servidor fisicamente e nem se preocupar com as manutenções e atualizações que um servidor exige, quem ficará responsável por essa parte será o provedor. 

Já da parte do contratante/ consumidor cabe as responsabilidades dos dados e informações armazenadas na nuvem, segurança de acesso- definir quais pessoas e maquinas podem se conectar ao serviço.

5. Quais são as responsabilidades do consumidor/ contratante?

- 
     informações e dados armazenados;

-    dispositivos que tem acesso;

-    contas e identidades das pessoas, serviços e dispositivos em uma organização;


6. Responsabilidades do servidor:

-  Datacenter físico;
- Rede física;
- Hosts físicos; 

7. O que o contratante pode definir?

- sistemas operacionais;
- controle de rede
- aplicativos
- identidade e infraestrutura

8. Quais os modelos de nuvem?

Privada, pública, híbrida ou várias nuvens.

9. O que é Azure Arc?

É um conjunto de tecnologias que ajuda a gerencias seu ambiente de nuvem independente do tipo de nuvem que vc tenha escolhido para sua empresa.

| **Nuvem pública**                                            | **Nuvem privada**                                            | **Nuvem híbrida**                                            |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| Nenhuma despesa de capital para escalar verticalmente        | As organizações têm controle total sobre os recursos e a segurança | Fornece a maior flexibilidade                                |
| Os aplicativos podem ser provisionados e desprovisionados rapidamente | Os dados não são colocados com os dados de outras organizações | As organizações determinam o local para executar os aplicativos |
| As organizações pagam apenas pelo que utilizam               | O hardware deve ser comprado para o início e a manutenção    | As organizações controlam a segurança, a conformidade ou os requisitos legais |
| As organizações não têm controle total sobre os recursos e a segurança | As organizações são responsáveis pela manutenção e pelas atualizações de hardware |                                                              |


Tabela extraída do site: https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/5-define-cloud-models

11. O que é solução VMware no Azure?

Um serviço que permite troca de tipos de nuvem com integração e escalabilidade total.

12. O que é um modelo de despesa baseado no consumo?

São despesas operacionais que são continuas, ou seja, de longo prazo. Aqui no caso dos serviços Azure vc paga pelo que esta utilizando, sem ter que se preocupar com a infraestrutura por trás ou recursos necessários (espaço físico para o servidor ou eletricidade). Esse modelo oferece vantagens de:

- não ter custo prévio;
- não haver necessidade de manter recursos que já não fazem sentido;
- pagar apenas pelos recursos necessários;
- poder parar de pagar a qualquer momento por um serviço específico;

13. Que garantias o contrato de nível de serviço pode informar?

Disponibilidade, que informa o quanto esse serviço tem de garantia de disponibilidade informando porcentagens da taxa média de disponibilidade do serviço garantindo que o mesmo esteja disponível para uso sempre que necessário.

Escalabilidade, que garante que o serviço se adeque as necessidades sem grandes impactos. A escalabilidade pode ser horizontal, permitindo contratar ou descontratar novos serviços; e também pode ser vertical permitindo aumentar os recursos de um serviço já contratado ou diminuir conforme a demanda/ necessidade.

Confiabilidade, capacidade do sistema de se recuperar de falhas e continuar operando. Os serviços da Microsoft utiliza de servidores em varias regiões do mundo e em alguns casos nem será necessário o contratante realizar algum ajuste para o serviço ser assumido por outro servidor, garantindo assim a sua operação continua.

Previsibilidade, aplica-se aos custos e também o desempenho. Sobre o desempenho pode haver uma gestão eficiente sobre a redistribuição de demandas para evitar sobrecargas localizadas, assim como o redimensionamento automatizado de recursos que podem subir ou baixar conforme demanda. Por todos essas adaptações de recursos poderem ser acompanhados em tempo real a previsão de valores é algo real. Além disso existem ferramentas como TCO(custo total da propriedade) e a calculadora de preços para uma melhor gestão e estimativa de valores.

Governança, dependendo do modelo operacional, as atualizações podem ocorrer de maneira automática o que facilita a tarefa de governança do serviço.

Segurança, a segurança também pode ser gerenciada de maneira manual pela empresa contratante ou automatizada, esses ambientes também são adequados a passar por ataques DDos(negação de serviço distribuído)

14. Sobre o gerenciamento da nuvem, podemos:

- Escalar automaticamente a implantação de recursos com base na necessidade.
- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
- Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
- Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real

15. Sobre o gerenciamento na nuvem, podemos:

- Por meio de um portal da Web.
- Usando uma interface de linha de comando.
- Usando APIs.
- Usando o PowerShell.

16. O que é Infraestrutura como serviço?

IaaS (infraestrutura como serviço), oferece máximo controle dos recursos para a empresa contratante. Aqui o serviço oferecido é estrutura física de hardware, rede(acesso a internet) e segurança física. Já todo o restante como configurações, atualizações e sistema operacional é de responsabilidade da empresa contratante.

Para esse modelo:

- Migração lift-and-shift: você conta com recursos de nuvem semelhantes aos do datacenter local e apenas migra os elementos em execução local para execução na infraestrutura IaaS.
- Teste e desenvolvimento: você estabeleceu configurações para ambientes de desenvolvimento e teste que precisa replicar rapidamente. Você pode ativar ou desativar os diferentes ambientes rapidamente com uma estrutura de IaaS, mantendo o controle completo.

17. O que é Plataforma como serviço?

PaaS (Plataforma como serviço), é um intermédio entre o infraestrutura como serviços e o software como serviço, aqui além de ter a infraestrutura como responsabilidade do serviço também se tem o sistema operacional, ferramentas de desenvolvimento e banco de dados. Esse tipo de serviço ainda mantem certa autonomia, porém com mais facilidades já que algumas atualizações de sistema operacional e outras podem ficar por conta do serviço de nuvem.

- Estrutura de desenvolvimento: O PaaS fornece uma estrutura que os desenvolvedores podem usar como base para desenvolver ou personalizar aplicativos baseados em nuvem. Semelhante à forma como você cria uma macro do Excel, o PaaS permite aos desenvolvedores criar aplicativos usando componentes de software internos. São incluídos recursos de nuvem, como escalabilidade, alta disponibilidade e a funcionalidade de multilocatário, reduzindo a quantidade de codificação que os desenvolvedores precisam realizar.
- Análise ou business intelligence: as ferramentas fornecidas como serviço com o PaaS permitem que as organizações analisem e minerem dados, encontrando insights e padrões e prevendo resultados para aprimorar a previsão, as decisões de design de produto, o retornos sobre investimentos e outras decisões de negócios.

18. O que é software como serviço?

SaaS (software como serviço), aqui você esta alugando um serviço de software totalmente desenvolvido, esse serviço pode ser um serviço de e-mail, envio de mensagens, gestão financeira...

A maior parte da responsabilidade aqui fica a parte do serviço de nuvem, ficando como responsabilidade da empresa contratante apenas a gestão dos dados e permissões de acesso ao software.

- Email e mensagens.
- Aplicativos de produtividade empresarial.
- Controle de finanças e despesas.

19. O que pode afetar os custos de utilizar um serviço de nuvem?

- Tipo de recurso
- Consumo
- Manutenção
- painel Geografia do app's selecionado
- Tipo de assinatura
- Azure Marketplace

20. Custos dicas:

- é necessário ficar atente aos recursos que realmente é necessário manter ou não para evitar custos desnecessários, também é possível estabelecer um teto no valor do custo para evitar surpresas.
- existem calculadora de custos para ajudar no controle de custos.
- o pagamento é feito conforme o consumo, se você fizer maior uso dos recursos em um período para esse pagará mais caro.
- é permitido que o usuário se comprometa a fazer um uso de recursos com antecedência e assim ganhar alguns descontos para esse serviço de até 72%.
- a reserva de uso de serviços com antecedência  é feita  por um período de 1 a 3 anos. Caso o uso ultrapassar o valor pago pelo valor que precisará acrescentar.
- Custos de entrada de dados - para alguns operações de entrada de dados o custo pode ser gratuito.
- Custos de saída de dados - para a saída de dados, o valor definido é baseado por zonas, onde uma zona é um agrupamento geográfico de regiões do Azure, site: https://azure.microsoft.com/pt-br/pricing/details/bandwidth/;
- tipo de assinatura, alguns tipos de assinatura podem incluir concessões de uso, exemplo assinatura de avaliação gratuita, inclui 12 meses de acesso grátis e mais um valor de credito para uso nos primeiros 30 dias.
- através do Azure não estão a venda apenas os serviços da microsoft, você pode comparar também serviços de terceiros/fornecedores os valores cobrados no Azure Marketplace, essas soluções também são certificadas e estão de acordo com os padrões Azure.

21. Quais são as diferenças entre a Calculadora de Preço e Custo Total de propriedade(TCO)?

As duas calculadoras ajudam a estimar valores de investimentos nos serviços Azure, mas as duas tem propósitos diferentes.

- calculadora de preço é para calcular valores de recursos individuais, seu foco é no custo de recursos provisionados da Azure e tem fins informativo. Ajuda a gerar uma estimativa de valores e nenhum serviço cotado ali será cobrado. Link: https://azure.microsoft.com/pt-br/pricing/calculator/
- calculadora TCO, tem o foco em comparar valores entre uma estrutura local e a solução Azure, onde vc inclui as configurações do servidor físico, banco de dados e SO e recebe o valor desse mesmo servidor pelo Azure. Você consegue inclusive informar valores estimados com mão de obra e/ou energia elétrica. Site: https://azure.microsoft.com/pt-br/pricing/tco/calculator/ para esse calculo teremos 3 passos: 1definir as cargas de trabalho, 2 ajustar as pressuposições e 3 exibir relatório.

22. O que é o gerenciamento de custos?

O Gerenciamento de Custos permite verificar rapidamente os custos de recursos do Azure, criar alertas com base nos gastos com recursos e criar orçamentos que podem ser usados para automatizar o gerenciamento de recursos. Permite ver os custos totais por ciclo de cobrança, região, recurso etc.

23. Quais os tipos de alertas de custos?

- Alertas de orçamento
- Alertas de crédito
- Alertas de cota de gastos do departamento.

24. Alerta de orçamento, notificam você quando os gastos, com base em uso ou custos, atingem ou excedem o valor definido na condição de alerta do orçamento. Os orçamentos do Gerenciamento de Custos são criados usando o portal do Azure ou a API de Consumo do Azure.

25. Os alertas de crédito notificam você quando seus compromissos monetários de crédito do Azure são consumidos. Os compromissos monetários se destinam a organizações que têm EAs (Contratos Enterprise). Os alertas de crédito são gerados automaticamente a 90% e a 100% do saldo de crédito do Azure. Sempre que um alerta é gerado, ele se reflete nos alertas de custo e no email enviado aos proprietários da conta.

26. Os alertas de crédito notificam você quando seus compromissos monetários de crédito do Azure são consumidos. Os compromissos monetários se destinam a organizações que têm EAs (Contratos Enterprise). Os alertas de crédito são gerados automaticamente a 90% e a 100% do saldo de crédito do Azure. Sempre que um alerta é gerado, ele se reflete nos alertas de custo e no email enviado aos proprietários da conta.

27. orçamento que você define um limite de gastos para o Azure. Você pode definir orçamentos com base em uma assinatura, grupo de recursos, tipo de serviço ou outros critérios. Ao definir um orçamento, você também define um alerta de orçamento. Quando o orçamento atinge o nível de alerta do orçamento, ele dispara um alerta de orçamento que aparece na área de alertas de custo. Se configurados, os alertas de orçamento também enviarão uma notificação por email de que um limite de alerta de orçamento foi disparado.

    Um uso mais avançado de orçamentos permite que as condições orçamentárias disparem a automação que suspende ou modifica recursos depois que a condição de gatilho ocorre.

28. O que são marcas?

É uma forma de organizar serviços nomeando e descrevendo como o mesmo vai se comportar, essa organização é essencial para garantir sucesso na gestão de recursos e valores. 

As marcas fornecem informações extras ou metadados sobre os recursos.

Esses metadados são úteis para:

- **Gerenciamento de recursos** As marcas permitem que você localize em recursos associados a cargas de trabalho, ambientes, unidades de negócios e proprietários específicos e realize ações nesses recursos.
- **Gerenciamento e otimização de recursos** As marcas permitem agrupar os recursos para que você possa relatar custos, alocar centros de custos internos, acompanhar orçamentos e prever o custo estimado.
- **Gerenciamento de operações** As marcas permitem que você agrupe os recursos de acordo com o grau de importância da disponibilidade deles para os seus negócios. Esse agrupamento ajuda você a formular SLAs (Contratos de Nível de Serviço). Um SLA é uma garantia de tempo de atividade ou desempenho acordada entre você e seus usuários.
- **Segurança** As marcas permitem que você classifique os dados pelo nível de segurança, como público ou confidencial.
- **Governança e conformidade regulatória** As marcas permitem que você identifique recursos que se alinham com os requisitos de conformidade regulatória ou de governança, como a ISO 27001. Elas também podem fazer parte dos seus esforços de imposição de padrões. Por exemplo, você pode exigir que todos os recursos sejam marcados com um proprietário ou um nome de departamento.
- **Automação e otimização de carga de trabalho** As marcas podem ajudar você a visualizar todos os recursos que participam de implantações complexas. Por exemplo, você pode marcar um recurso com o nome da carga de trabalho ou do aplicativo associado e usar um software como o Azure DevOps para executar tarefas automatizadas nesses recursos.

exemplo de metadados:

**Nome** 						**Valor**

AppName					O nome do aplicativo do qual o recurso faz parte.

CostCenter				O código do centro de custo interno.

Proprietário			 	nome do proprietário de negócios responsável pelo recurso.

Ambiente					Um nome de ambiente, como "Prod", "Dev" ou "Test".

Impacto						O grau de importância do recurso para as operações de negócios, como "Crítico", "De 										alto impacto" ou "De baixo impacto".

fonte: https://learn.microsoft.com/pt-br/training/modules/describe-cost-management-azure/7-describe-purpose-of-tags

29. O que são Maquinas virtuais no Azure?

São como maquinas físicas, onde pode-se:

- Controle total sobre o SO (sistema operacional).
- Capacidade para executar um software personalizado.
- Usar configurações personalizadas de hospedagem.

pode-se agrupar VMs, desevolver tarefas secundárias

30. como criar uma vm?

NA area restrita No Cloud Shell, execute o comando `az vm create` 

```
az vm create --name  MyVm --generate-ssh-keys --resource-group learn-d7ed86b3-01a9-4a12-8945-f639a13c15f1 --image  UbuntuLTS --admin-username azureuser 
```

execute comando az vm extension set

```
az vm extension set --resource-group learn-d7ed86b3-01a9-4a12-8945-f639a13c15f1 --vm-name MyVm --name customScript --publisher Microsoft.Azure.Extensions --version 2.1 --settings '{"fileUris":["https://raw.githubusercontent.com/MicrosoftDocs/mslearn-welcome-to-azure/master/configure-nginx.sh"]}' --protected-settings '{"commandToExecute": "./configure-nginx.sh"}'
```

esse ultimo comando:

1. Executa `apt-get update` para baixar as informações mais recentes do pacote da Internet. Esta etapa ajuda a garantir que o próximo comando possa localizar a versão mais recente do pacote Nginx.
2. Instala o Nginx.
3. Define a home page, */var/www/html/index.html*, para imprimir uma mensagem de boas-vindas que inclui o nome de host da VM.

https://learn.microsoft.com/pt-br/training/modules/describe-azure-compute-networking-services/4-virtual-desktop

31. Conta estudando gratuita do Azure, como funciona?

    Oferece acesso gratuito a determinados produtos do Azure por 12 meses.

    Um crédito a ser usado nos primeiros 12 meses e acesso gratuito a determinadas ferramentas para desenvolvedores de software. 

    também oferede crédito de $100 em ferramentas para desenvolvedores gratuitas, além de permitir se inscrever sem cartão de credito.

    link: https://azure.microsoft.com/free/students/

32. Conta Microsoft Learn, como funciona?

    É a área restrita que tem um recurso da Microsoft de aprendizagem para os produtos e serviços por meio de aprendizagem interativa, baseada em tarefas com mais de 80h de conteúdo gratuito. No final do treinamento essa plataforma reseta os testes para que você tenha um acesso limpo aos recursos e serviços sem os testes realizados durante seu desenvolvimento.

33. Como acessar o Microsoft Learn?

- acesse o link: https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/
  
- clique no botão Aceitar os termos/condições
  
- aguarde a plataforma carregar do lado direito da tela o PowerShell
  
- use o comando `get-date` no powerShell, para exibir a data nesse novo CLI(interface de linha de comando). -> retorno esperado é a data do sistema: `Tuesday, January 17, 2023 10:15:41 PM`
  
- digite o comando `az version` para verificar a versão do Azure do CLI(interface de linha de comando). -> retorno esperado são as versões da Interface CLI, verão do CORE, versão do TELEMETRY e EXTENSIONS
  
    Exemplo:
    
    - ```
      {
        "azure-cli": "2.43.0",
        "azure-cli-core": "2.43.0",
        "azure-cli-telemetry": "1.0.8",
        "extensions": {
          "ai-examples": "0.2.5",
          "ml": "2.11.0",
          "ssh": "1.1.3"
        }
      }
      ```
    
- digite o comando bash na CLI -> retorno esperado é seu nome de usuário e alterar para o modo CLI para o bash
  
     `ti_jacque [ ~ ] $`
    
- para o modo Bash, deve executar o comando date e não `Get-date` para retornar a data, comando `date` - > retorno esperado: Tue Jan 17 10:28:48 PM UTC 2023
  
- execute o comando az upgrade para atualizar e retornar ao modo PowerShell
  
34. Zonas de disponibilidade, são datacenters separados fisicamente dentro de uma região do Azure. As zonas de disponibilidade permitem isolamento no funcionamento, de maneira que se uma zona ficar inativa, as outras continuarão funcionando.

35. Redundância: Para garantir e proteger seus dados e a disponibilidade dos mesmos, é importante pensar em uma estrutura que ao hospedar sua infraestrutura, incluir a redundância, o que exigirá a criação de ambientes de hardware duplicados.  As zonas de disponibilidade permitem alta disponibilidade, colocando os recursos em uma zona de disponibilidade e replicando em outras zonas de disponibilidade. Pode haver um custo para duplicar seus serviços.

36. Zonas de disponibilidade são aplicáveis em: Máquinas virtuais, balanceadores de carga e bancos de dados SQL. 

37. Quais os serviços que dão suporte as zonas de disponibilidade?

- Serviços em zonas: VMS, Discos gerenciados, Endereços IP

- Serviços de redundâncias de zona: armazenamento com redundância de zona, Banco de dados SQL.

- Serviços não regionais: os serviços que estão sempre disponíveis em geografias do Azure e são resilientes a interrupções em toda zona.

38. Pares de regiões: Serve como apoio para quando um evento atinge várias zonas de disponibilidade. Exemplo EUA, Europa ou Ásia são emparelhadas (cerca de 480km de distancia entre sí para as áreas.) OBS a recuperação e replicação devem ser configuradas pelo cliente em alguns serviços.

39. Recursos: são todos e qualquer serviço Azure que você venha a implementar, criar, provisionar...

40. Grupos de recursos: um recurso é um bloco de construção básico do Azure. Os grupos de recurso são simplesmente agrupamento de recursos. quando se cria um recurso, é necessário inclui-lo em um grupo de recursos. Podemos mover um recurso de um grupo para outro, porém não podemos adicionar um grupo ou outro, exemplo: grupo de recursos a pertence a grupo de recursos c.

41. Vantagens dos grupos de recursos: quando vc adicionar uma ação a um grupo, todos os recursos desse grupo recebem essa ação, quando se da permissão de acesso a um grupo de recursos, todos os recursos desse grupo se tornam acessíveis, e quando se exclui um grupo, todos os recursos são excluídos.

42. Assinaturas(subscriptions) do azure, são uma unidade de gerenciamento, cobrança e escala, facilita a cobrança. Uma conta pode ter várias assinaturas. 

43. Limites para assinatura:

- Limite de cobrança-> é cobrada pelo uso do Azure e pode ser gerado diversos relatórios para as assinaturas diferentes e faturas separadas tbm. 

- Limite de controle de acesso: permite separar/ setorizar os acessos por um controle de assinaturas específicas. 

44. Assinaturas adicionais Azure:

- Ambientes -> separa ambientes exemplo: para desenvolvimento e testes. 

- Estruturas organizacionais-> exemplo separar os setores de uma empresa e colocando a cada setor os recursos e limitar alguns afim de customizar os custos.

- Cobrança-> para melhor acompanhar os custos vc pode separar a cobrança em assinaturas distintas, exemplo uma assinatura para gerar cobrança para o desenvolvimento e testes e outra assinatura para as demandas de produção.

45. Hierarquia Azure: Recursos-> grupos de recursos -> assinaturas -> Grupos de gerenciamento

46. O que são grupos de gerenciamento?

    As assinaturas podem ser organizadas em contêineres, com isso todas as assinaturas de um grupo de gerenciamento herdam todas as configurações desse contêiner. Os grupos de gerenciamento podem ser alinhados.

    imagem do site Learn Microsoft:

    ![/imagem de exemplo de uma hierarquia de grupo de gerenciamento](https://learn.microsoft.com/pt-br/training/wwl-azure/describe-core-architectural-components-of-azure/media/management-groups-subscriptions-dfd5a108.png)

    

      
    
47. Sobre grupos de gerenciamento: 

- 10.000 grupos de gerenciamento podem ter suporte em um único diretório

- uma arvore de grupo de gerenciamento pode dar suporte a até seis níveis de profundidade. Esse limite não inclui o nível raiz nem o nível da assinatura

- cada grupo de gerenciamento e assinatura podem dar suporte a somente um pai.

48. criando um recurso:

- acessar o link: https://portal.azure.com/learn.docs.microsoft.com

- Criar um recurso >  Máquina Virtual > Criar.

- Começar com uma avaliação gratuita do Azure - iniciar

- inicio gratuito

- preencher formulário com dados pessoais

49. O que é computação em nuvem?

- é uma gama de produtos que é entregue a você pela internet(servidor, armazenamentos, banco de dados, redes, software, análises e inteligência. Oferece inovação mais rápida, recursos flexíveis e economias de escala.)

50. o que é o Azure monitor?

- é um painel para monitoramento dos recursos, assinaturas ...

51. Integridade de serviço?

- painel que te da acesso a integridade, alertas de problemas/manutenções, avisos de manutenções 

52. Central de segurança da Azure - microsoft defender para a nuvem

- é um serviço de monitoramento de todos os serviços da azure, ajuda a garantir uma postura -  o quanto seu ambiente esta seguro conforme leis, compliance. exemplo para PCI DSS - Padrão de segurança de dados de setor de cartão de pagamento

53. Azure Sentinel - é um Siem(centraliza os alertas de todos os servidores da sua aplicação) que permite coleta de dados de todos os usuários, dispositivos, aplicativos e infraestrutura. Minimiza falsos positivos usando a análise abrangente e a inteligencia contra ameaças da Microsoft.

54. O que é o firewall do azure? é a configuração de Fireware que permite especificar portas de acesso para servidores e permissões.

55. O que é ataque de DDOS?

- é um ataque de negação de serviços distribuídos, tenta sobrecarregar e esgotar os recursos de um aplicativo.

56. O que é o MFA? é um método de autenticação em duas ou mais etapas (mensagem de email ou whatsapp ou sms por exemplo além da senha no aplicativo)
57. O que é o Acesso condicional? é uma ferramenta da Azure Active Directory para permitir ou negar o acesso a recursos com base em sinais de identidade;
58. O que é bloqueio de recursos?  é um bloqueio que impede que os recursos configurados sejam excluídos ou alterados por acidente.
59. Quais categorias de conformidade estão disponíveis no azure? conformidade com leis, Isos...
60. O que é o Azure governamental? Atende as necessidades e leis e se adapta as necessidades de onde esta sendo implementada
61. O que é a calculadora de TCO(Custo total de propriedade) = é um recurso onde ajuda a estimar a economia de custos de operar sua solução no Azure ao longo do tempo(considerando uma estrutura física como contrapeso)
62. Que tipos de assinatura o Azure possui? Gratuíta; Pago conforme uso; Ofertas de membro;
63. O que são SLAS(Contrato de nível de serviço)? é um contrato formal entre uma empresa de serviços e o cliente. Na Azure esse contrato define os padrões de desempenho com os quais  Microsoft se compromete a fornecer para você (cliente).
64. O que é ciclo de vida? Produtos em teste(podem sair do ar a qualquer momento),;
65. Em quantos grupos de recursos um recurso pode estar ao mesmo tempo? 

- em um 

66. Qual recurso do Azure replica recursos entre regiões que estão a pelo menos 480 km umas das outras?

- Pares de regiões

67. O que acontece com os recursos dentro de um grupo de recursos quando uma ação ou configuração no nível do Grupo de Recursos é aplicada?

- A configuração é aplicada a recursos atuais e futuros.

68. Containers do Azure

- é um ambiente de virtualização que permite a execução de vários "sistemas" em um só host físico.
- diferente das máquinas virtuais que executará apenas um sistema operacional por vez, no container vc consegue executar de forma separadas os recursos de seu aplicativo (backend, front e Banco de dados) e até mesmo realizar mudanças em um desses sem afetar o desempenho ou execução do outro.
- instancias de containers é a maneira mais rápida e simples de executar um conteiner Azure PaaS(plataforma como serviço)

69. O que é Azure Functions?

- é uma opção de computação sem servidor controlada por eventos que não requer a manutenção de máquinas virtuais ou containers.  Para uma aplicação em container ou VM precisamos ter esses recursos em execução para o funcionamento da aplicação. Um Azure Functions terá um evento que desperta a função, reduzindo a necessidade de manter os recursos provisionados quando não há eventos.
- vantagens: foco no código e não na plataforma ou infraestrutura; funções são entregues conforme a demanda automaticamente; 

70. Serviço de aplicativo Azure:

- permite que você crie e hospede aplicativos Web. É o serviço de hospedagem robusta que você pode usar para hospedar seus aplicativos no Azure. Linguagens: .Net, .Net core, Java, Ruby, Node.JS, PHP Python

71. Tipos de serviços de aplicativos:

- Aplicativos Web: da suporte para hospedagem de aplicativos web nas linguagens:  Asp.net, Asp.net core, Java, Ruby, Node.js, PHP ou Python.
- Aplicativos de API: hospeda apis em rest usando a linguagem e estrutura que você quiser. Suporte de Swagger e capacidade de empacotar e publicar sua api no azure marketplace.
- Webjobs: pode-se executar um script ( .cmd, .bat, PowerShell ou Bash) ou um programa (Java, PHP, Python ou Node.js) 
- Aplicativos móveis: Criar back-end de aplicativos iOS e Android, armazenar dados de um aplicativo movel no banco de dados, autenticar clientes no google, twitter e Facebook, evitar notificações por push, Executar lógica personalizada de back-end no c# ou Node.js.

72. Redes virtuais, permite que os recursos se comuniquem uns com os outros, e ainda permite ou não acesso de usuários na internet.

- segmentação e isolamento, a rede virtual do Azure permite criar redes isoladas. Exe: tais recursos se comunicam entre si e os outros trabalharam em outro seguimento...
- comunicações com a internet, você permite se um recurso vai ter acesso a internet fora daquele container ou vm.
- Comunicação entre recursos, permite a comunicação e a validação desse segurança da rede.
- Comunicação com recursos locais, é possível comunicação entre um recurso local com os recursos do Azure por VPM. O Router permite que essa conecxão não passe pela internet.
- Rotear trafego de rede - por padrão o Azure faz o roteamento de tráfego entre sub-redes em redes virtuais conectadas, em redes locais e na internet. Mas tbm pode ser feita as configurações pelo cliente.
- Filtrar trafego de rede - através de grupos de segurança de rede com regras de segurança de entrada ou saída, pode ser configurado pelo adm, exemplo informar os ips das máquinas com acesso.
- Conectar redes virtuais, emparelhamento permite que duas redes virtuais conectem diretamente entre sí, nunca entrando na internet publica.

73. VPN - rede virtual privada: usa um túnel criptografada dentro de outra rede. as VPNs costumam ser implantadas para conectar duas ou mais redes privadas confiáveis entre si em uma rede não confiável(internet).
74. Gateways de VPN: é um tipo de gateway de rede virtual.

- Conexões entre redes virtuais
- Conexões ponto a site
- Conexões multissite
- Coexistência com um gateway do Azure ExpressRoute

75. Cenários de alta disponibilidade: é importante manter suas informações seguras, ter certeza de que ela é uma configuração VPN altamente disponível e tolerante a falhas.
76. Ativo / Em espera 

- Por padrão de VPM são implantados como duas instâncias em uma configuração (ativo)(em espera)
- Durante esse failover, as conexões são interrompidas, mas normalmente são restauradas em alguns segundos para manutenção planejada e dentro de 90 segundos em caso de interrupções não planejadas.

77. O que é ExpressRoute?

    ![Resultado de imagem para o que é Failover do ExpressRoute](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQHSgpVwRn5TEG65qMmwyZiGMHEbEsg8IOw6rX0l2XL&s)

    O **ExpressRoute** permite que você estenda suas redes locais para a nuvem da Microsoft em uma conexão privada com a ajuda de um provedor de conectividade. Com o **ExpressRoute**, você pode estabelecer conexões com os serviços em nuvem da Microsoft, como o Microsoft Azure e o Microsoft 365.

78. ***Failover\* é o termo utilizado para indicar a tolerância a falhas**. Na prática, significa que existem recursos tecnológicos em redundância para evitar a indisponibilidade de um determinado componente, que pode ser um hardware, um link de comunicação, a [infraestrutura de rede](https://blog.betrybe.com/tecnologia/topologias-de-rede/), o [banco de dados](https://blog.betrybe.com/tecnologia/dba/) de uma aplicação ou todo o datacenter.

79. ### Gateways com redundância de zona

    Nas regiões que dão suporte a zonas de disponibilidade, os gateways de VPN e os gateways de ExpressRoute podem ser implantados em uma configuração com redundância de zona. Essa configuração oferece resiliência, escalabilidade e maior disponibilidade para os gateways de rede virtual. A implantação de gateways em zonas de disponibilidade do Azure separa de forma física e lógica os gateways em uma região, enquanto protege a conectividade de rede local com o Azure contra falhas no nível da zona. Esses gateways exigem SKUs de gateway diferentes e usam os endereços IP públicos Standard em vez dos Básicos.

80. ## Recursos e benefícios do ExpressRoute

- o expressRoute é um serviço que permite que você estenda sua rede local para a nuvem com a Microsoft com ajuda de um provedor de conexão (VPN), sem cair na internet pública.
- conectar com os recursos Microsoft independente de sua localização(Microsoft Office, Microsoft Dynamics, VM da Azure, Armazenamento Azure...).
- Conectividade global, sem trafegar dados pela internet pública.
- Roteamento dinâmico entre sua rede e a Microsoft(BGP - Border Gateway Protocol)
- redundância interna em cada local de emparelhamento para proporcionar maior confiabilidade.
- O ExpressRoute dá suporte a quatro modelos que podem ser usados para conectar a rede local: Colocação do CloudExchange; Conesão Ethernet ponto a ponto; Conexão qualquer para qualquer; Direto de sites do ExpressRoute;

81. DNS Azure

- Oferece resolução de nomes usando infraestrutura da Microsoft
- Confiabilidade e desempenho
- segurança
- facilidade de uso
- personalizar redes virtuais
- registros de alias

82. Qual recurso da Máquina Virtual do Azure escalona atualizações entre VMs com base no domínio de atualização e no domínio de falha?

- Conjuntos de disponibilidade

- Os conjuntos de disponibilidade escalonam atualizações de VM com base em seus domínios de atualização e falha.

83. Qual serviço do Azure permite que os usuários usem uma versão hospedada na nuvem do Windows de qualquer local e se conectem da maioria dos navegadores modernos?

- Área de Trabalho Virtual do Azure
- A Área de Trabalho Virtual do Azure dá acesso a uma versão hospedada na nuvem do Windows e funciona com a maioria dos navegadores modernos.

84. Descrever as contas de armazenamento do Azure:

- Uma conta de armazenamento fornece um namespace exclusivo para os dados do armazenamento do Azure, que permite acessar de qualquer lugar do mundo. Seguro disponíveis e duráveis e escalonáveis.
- armazenamento com redundância local(LRS)
- Armazenamento com redundância geográfica (GRS)
- armazenamento com redundância geográfica com acesso de leitura(RA-GRS)
- armazenamento com redundância de zona(ZRS)
- Armazenamento com redundância de zona geográfica (GZRS)
- Ao nomear sua conta de armazenamento, lembre-se dessas regras:
  - Os nomes da conta de armazenamento devem ter entre 3 e 24 caracteres e podem conter apenas números e letras minúsculas.
  - O nome da sua conta de armazenamento deve ser exclusivo no Azure. Duas contas de armazenamento não podem ter o mesmo nome. Isso dá suporte à capacidade de ter um namespace exclusivo e acessível no Azure.
- Redundância primária - os dados em uma conta de armazenamento Azure são sempre replicados três vezes na região primária que pode ser LRS ou ZRS
- O LRS é uma opção de redundância de menor custo e oferece menor durabilidade. Mantem os dados redundantes dentro do mesmo Data Center
- Redundância Zero ZRS - replica os dados em três zonas de disponibilidade do Azure na região primária. 
- Redundância em região secundária - armazena os dados em outro Data Center que esta a centenas de quilômetros da região primária. Isso resulta em maior segurança, pois em caso de desastre natural o segundo data center esta localizado mais longe do primeiro.
- Redundância de Geografia - GRS copia os dados de maneira síncrona três vezes em um único local físico na região primária. Em seguia copia 3 vezes na região secundária tbm.

85. IAAS - Infraestrutura como serviço - pode ser uma maquina virtual que vc gerencia quantidade de memória, processador, sistema operacional ...
86. PAAS - plataforma como serviço - podemos citar um banco de dados que pode ser acessado sem se preocupar com o hardware e o sistema operacional
87. SAAS - serviço - uso apenas um serviço sem me preocupar com anda disso, pode ser uma parte de um sistema pronto para uso
88. Serverless - é a criação de funções que serão gerenciados aplicados no Hardware da Azure, mas não preciso me preocupar com hardware e posso escalar o serviço conforme a necessidade
89. Mais de 160 Datacenter fisicamente separados distribuídos em regiões - Geografia/ Regiões e zonas de disponibilidades. Então temos as zonas de distribuições que -> estão dentro das zonas -> que são Geográficas; Geografia = Canadá ; Região é um grupo de zonas de disponibilidade https://azure.microsoft.com/en-us/explore/global-infrastructure/geographies/
90. Formas de pagamento,

- Pay as you go - Pago pelo uso: é a forma de cobrança para os produtos que você não contrata com valor fixo, e sim pagará conforme a sua demanda de uso.
- preço por produto, é o valor que cada produto tem para seu custo.
- Estancia reservada 1 ano(instancia spot), é um tipo de cobrança que oferece o mesmo produto por valor mais acessível(com desconto) já que você tem o compromisso de pagar por 1 ano.







56. https://click.uniacademy.com.br/cloud-hero-az-900-revisao
57. [https://click.uniacademy.com.br/cadastro](https://click.uniacademy.com.br/cadastro)
58. [https://bit.ly/guia--de--estudos](https://bit.ly/guia--de--estudos)

Revisão https://www.youtube.com/watch?v=YjMSGV9YQSA&ab_channel=WellingtonAg%C3%A1pto-CloudHero



