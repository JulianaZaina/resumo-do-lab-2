# resumo-do-lab-2
Resumo do aprendizado desenvolvido na lab: Benefícios da Nuvem
## Aprendizado
- Bootcamp Azure Essentials: AZ-900 Microsoft Azure Fundamentals
### Benefícios da Nuvem
  - Acordo de Nível de Serviço e como é disponibilizado (SLA Service Level Agreement): tabela % SLA por tempo de inatividade por semana, mês e ano. Quanto maior o tempo disponível, melhor é o nível e mais caro o serviço oferecido. A escolha influencia no custo. Buscar entender o propósito real da empresa para o serviço, pois vai precisar de orçamento pré-definido para desenvolver e usar as melhores estratégias, alinhadas ao propósito e demandas da equipe, em conformidade com o preço. 
  - Portal do Azure - solicitação: criar uma máquina virtual, quais opções de disponibilidade (tempo de inatividade aceitável). Observar que é uma requesição sua, conforme modelo de SLA escolhido por você para criar uma máquina ou mais e definir região, zonas, estruturas. Nesse caso a Microsoft não irá ressarcir pelo tempo que a máquina estiver inativa, uma vez previsto no acordo (SLA escolhido). Quais são os requisitos necessários, produtos, ter atenção pois envolve custos.
  - Ao criar uma MV observar opções de disponibilidade (Zonas) e alternativas de dimensionar. Fazer uso da documentação (explicação). Especificar Zonas, pois o Disco gerenciado e IP públicos são criados na mesma zona de disponibilidade. Há possibilidade de criar um recurso em 3 Zonas (1, 2, 3). Mas nesse caso, pode não ser a melhor estratégia. O Portal oferece sugestões (link) conjunto de dimensionamento (MV), conjunto de disponibilidade, atentar para cada estrutura implica na SLA. Ver documentação.
  - Contas de Armazenamento (estratégia de replicação) - armazenamento com redundância local/ geográfica, de zona, de zona geográfica. Ação replicar dados entre datacenters ou regiões, influencia SLA, alta disponibilidade, no caso de desastre para recuperar, e no custo (preço).
  - Responsabilização pelas escolhas (SLA). 
  - 
