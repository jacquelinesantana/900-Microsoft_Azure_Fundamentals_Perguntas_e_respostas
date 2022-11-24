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