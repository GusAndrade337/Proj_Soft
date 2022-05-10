# Proj_Soft]

1)Para começar, o endereçamento é basicamente registros de dados que existem na memória. Ele ocorre principalemten por quastões de proteção. Pois esejamos manter os processos utilizados pelos usuários em um lugar separado na memória se comparado aos processos e kenrel. Portanto usamos endereçamentos para controlar até onde na memória os processos podem ser carergados, com as informalões de registrador base(endereço inferior/mínimo) e registrador limite(endereço superios/máximo)

2)a) O endereço físico são os endereços que existem na mémoria principal (número reduzido)	

b) Endereçamentos Virtuais são endereços que existem na memória secundária para poder agilizar a transferência de dados entre a memória secundária e a memória principal, permitindo o uso de algoritmos como os de paginação, segmentação e Swap

c) Espaço onde é armazenado os endereços fisicos

d) Espaço onde é armazenado os endereços virtuais	


3)O Swap é o mecanismo de transferência de endereçamentos virtuais para endereçamentos físicos. O Swap se assemelha muito com o processo de paginação, no entanto, diferente do segundo, ele carrega o programa/processos por inteiros, ao invés de possuir uma transferência dinâmica. O Swap deve apenas ser usado em ultimo recurso em caso de memória faltando, pois é um processo extremamente lento por transferir grandes uquantidades de dados que não necesseriamente serão utilizados no momento em que são cahamados (chaamado ocioso). Uma operação muito mais aproproriada é a anteriormente citada, paginação e/ou segmentação
