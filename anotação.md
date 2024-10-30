Minha anotação sobre AWS

EC2 é basicamente onde você consegue criar máquinas virtuais, instâncias, é como se fossem servidores mesmo que você pode configurar do seu jeito, escolher sistema operacional, o quanto de memória ou processamento precisa. E legal que dá para aumentar ou diminuir essas instâncias conforme a necessidade, então se eu precisar de mais poder de computação num dia, posso subir uma instância maior, e se estiver mais tranquila, dá para diminuir. Tem várias opções de pagamento também, tipo você pagar só pelo que usar ou escolher instâncias reservadas para economizar.

O RDS é o Relational Database Service e, como o nome indica, ele é um banco de dados relacional que já vem gerenciado. Ele suporta vários bancos de dados que já são conhecidos, como MySQL, PostgreSQL, Oracle, SQL Server, entre outros. A ideia é que você coloque seus dados lá e esqueça manutenção e backups, porque a própria AWS faz isso para você. Além disso, a AWS dá capacidade de replicação desses bancos de dados, o que aumenta a disponibilidade do seu banco.

S3 significa Simple Storage Service. Ou seja, é o serviço de armazenamento de objetos, então, para “colocar arquivos e dados lá”. Os dados são armazenados em “buckets”, que são, na verdade, containers de armazenamento. Outro ponto interessante é que S3 tem uma durabilidade muito alta e várias classes de armazenamento para reduzir custos, por exemplo, como “padrão” para dados utilizados com frequência ou glcier, que é mais barato, usado para arquivos que ficam parados por muito tempo.

Route 53 é um serviço de DNS da AWS e, basicamente, ajuda a adicionar endereços de domínio a recursos como instâncias EC2 ou até a websites fora da AWS. Com isso, pode ser configurado para rotação de tarefa, por isso, a aplicação irá direcionar automaticamente para o servidor mais próximo conforme a geolocalização.

Lâmbda que é um serviço “serverless”, onde você escreve o código e ele é executado automaticamente como resposta dos eventos sem a necessidade de configurar um servidor. Você só precisa pagar pelo tempo de execução, então utilizá-lo sempre que você só precisa de uma função só uma vez ou atualizar algo rapidamente.

Os servisos que eu planejo utilizar são o EC2, RDS e S3 pois Juntos, EC2, RDS e S3 formam uma base eficiente e escalável para o site de catálogo de livros. O EC2 garante o funcionamento do site, oferecendo flexibilidade e poder de processamento. O RDS organiza e gerencia os dados do catálogo de livros, permitindo consultas avançadas e automatizando a manutenção. O S3 armazena as imagens das capas, diminuindo a carga do servidor e garantindo que os arquivos estejam sempre disponíveis de forma prática e econômica.

