# Resumo do Lab Microsoft Azure

## Módulo 1: Conceitos Iniciais de Cloud com Azure

### Benefícios da Computação em Nuvem
- **Serviços por Categoria**: Como organizar recursos no portal do Azure, alterando idioma, tema e visualização por categoria.
- **Máquinas Virtuais**: Diferença entre SLAs e como escolher a configuração adequada.

### Tipos de Serviço de Nuvem
- **IaaS**: Maior flexibilidade e mais responsabilidades do usuário.
- **PaaS**: Menos responsabilidades do usuário, focado em apps.
- **SaaS**: Menos flexibilidade, sem responsabilidades operacionais.

### Responsabilidade Compartilhada
- Cada modelo de serviço (IaaS, PaaS, SaaS) tem diferentes responsabilidades entre o Azure e o cliente.

## Módulo 2: Arquitetura e Serviços Azure

### Componentes da Arquitetura
- **Regiões**: Locais geograficamente dispersos para minimizar latência.
- **Zonas de Disponibilidade**: Garantia de redundância dentro da mesma região.
- **Datacenters e Pairs**: Locais físicos conectados para maior segurança e resiliência.

### Gerenciamento de Recursos
- **Assinaturas e Grupos de Recursos**: Organizam e controlam acesso e faturas.
- **Hierarquia de Governança**: Gerenciamento de múltiplos recursos através de Assinaturas e Grupos de Gerenciamento.

### Armazenamento
- **Contas de Armazenamento**: Tipos de redundância (LRS, GRS) e como escolher dependendo da necessidade de durabilidade.
- **Tipos de Armazenamento**: Blobs, filas, arquivos, tabelas.
- **AzCopy e Gerenciador de Armazenamento**: Ferramentas para transferir dados para o Azure.

### Identidade e Acesso
- **Autenticação e RBAC**: Controle de acesso detalhado usando identidades e funções.
- **Acesso Condicional**: Políticas baseadas em local, risco ou dispositivo.

## Módulo 3: Gerenciamento e Governança

### Gerenciamento de Custos
- **Fatores que Afetam Custos**: Tipo de recurso, consumo, localização, e tráfego de rede.
- **Calculadora de Preços**: Ferramenta para estimar custos de serviços.
- **Tags**: Marcação de recursos para facilitar a organização e controle de custos.

### Governança e Conformidade
- **Políticas do Azure**: Impõem restrições para conformidade e segurança.
- **Blueprints**: Padrões de governança para recursos em escala.
