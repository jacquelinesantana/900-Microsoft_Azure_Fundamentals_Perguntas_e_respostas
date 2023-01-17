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

    a) acesse o link: https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/
    
    b) clique no botão Aceitar os termos/condições
    
    c) aguarde a plataforma carregar do lado direito da tela o PowerShell
    
    d) use o comando `get-date` no powerShell, para exibir a data nesse novo CLI(interface de linha de comando). -> retorno esperado é a data do sistema: `Tuesday, January 17, 2023 10:15:41 PM`
    
    e) digite o comando `az version` para verificar a versão do Azure do CLI(interface de linha de comando). -> retorno esperado são as versões da Interface CLI, verão do CORE, versão do TELEMETRY e EXTENSIONS
    
    Exemplo:
    
    ```
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
    
    f) digite o comando bash na CLI -> retorno esperado é seu nome de usuário e alterar para o modo CLI para o bash
    
     `ti_jacque [ ~ ] $`
    
    g) para o modo Bash, deve executar o comando date e não `Get-date` para retornar a data, comando `date` - > retorno esperado: Tue Jan 17 10:28:48 PM UTC 2023
    
    h) execute o comando az upgrade para atualizar e retornar ao modo PowerShell 
    
    

