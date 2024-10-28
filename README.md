# resumo-do-lab-armazenamento-az
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

# O que eu Aprendi sobre Serviços de Armazenamento do Microsoft Azure (AZ-900)

Ao estudar para a certificação AZ-900, aprofundei-me nos serviços de armazenamento do Microsoft Azure, incluindo opções de gerenciamento e migração de dados. Abaixo, compartilho os pontos principais desse aprendizado:

## Serviços de Armazenamento do Azure

Existem diferentes tipos de armazenamento para atender a várias necessidades de dados:
- **Blob do Azure**: Ideal para armazenar grandes volumes de dados não estruturados, como texto ou dados binários.
- **Disco do Azure**: Fornece armazenamento para máquinas virtuais e outros serviços.
- **Fila do Azure**: Um sistema de armazenamento de mensagens para gerenciar grandes volumes de mensagens, com capacidade de até 64 KB por mensagem.
- **Arquivos do Azure**: Permite configurar um compartilhamento de arquivos de rede usando o protocolo SMB, garantindo alta disponibilidade.
- **Tabelas do Azure**: Um armazenamento de dados não relacionais com um design sem esquema, permitindo chave/atributo para dados estruturados.

## Redundância e Camadas de Armazenamento
- **Opções de Redundância**: O Azure oferece diferentes opções para manter dados seguros e disponíveis, desde replicação local até replicação geográfica para garantir disponibilidade.
- **Camadas de Armazenamento**: Existem camadas de acesso no Azure que permitem otimizar o custo de armazenamento de acordo com a frequência de acesso aos dados.

## Opções de Migração de Dados
Para migrar dados para o Azure, existem diversas ferramentas e serviços:
- **Migrações para o Azure**: Uma plataforma unificada que fornece ferramentas para avaliação e migração de dados.
- **Azure Data Box**: Uma solução física que permite migrar até 80 TB de dados, protegidos em trânsito, para casos de conectividade limitada ou para atender a necessidades de conformidade.

## Opções de Gerenciamento de Arquivos
Para o gerenciamento eficiente de arquivos, o Azure oferece várias ferramentas:
- **AzCopy**: Um utilitário de linha de comando que permite copiar ou sincronizar dados de maneira unidirecional entre a conta de armazenamento e outros locais.
- **Gerenciador de Armazenamento do Azure**: Interface gráfica semelhante ao Windows Explorer, compatível com Windows, macOS e Linux.
- **Sincronização de Arquivos do Azure**: Permite sincronização bidirecional entre arquivos locais e do Azure, mantendo os arquivos acessados frequentemente no local e liberando espaço na nuvem.

---

Esses aprendizados forneceram uma base sólida sobre os serviços de armazenamento do Azure, ajudando a compreender como gerenciar, migrar e otimizar o armazenamento de dados de forma segura e eficiente para a certificação AZ-900.
