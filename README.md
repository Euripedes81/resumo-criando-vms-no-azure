## Resumo - Criando máquinas Virtuais na Azure

- **SLA – Acordo de nível de serviço:** quanto maior a porcentagem do SLA, menor será a inatividade do serviço e maior será o seu custo. Quanto maior a replicação de um recurso menor será a sua indisponibilidade.
- Ao criar uma VM no Azure com uma conta gratuita você tem 3 tipos de opções de disponibilidade:
  1. **Zonas de disponibilidade:** expandem o nível de controle de que você precisa para manter a disponibilidade dos aplicativos e dos dados em suas VMs. Uma Zona de Disponibilidade é uma zona fisicamente separada em uma região do Azure.
  2. **Conjunto de dimensionamento de máquinas virtuais:** permitem criar e gerenciar um grupo de VMs com balanceamento de carga. O número de instâncias de VM pode aumentar ou diminuir automaticamente em resposta à demanda ou a um agendamento definido.
  3. **Conjunto de disponibilidade:** é um agrupamento lógico de VMs que permite que o Azure entenda como o seu aplicativo foi criado para fornecer redundância e disponibilidade. Recomenda-se que duas ou mais VMs sejam criadas dentro de um conjunto de disponibilidade para fornecer um aplicativo altamente disponível e para atender o SLA de 99,95% do Azure.



