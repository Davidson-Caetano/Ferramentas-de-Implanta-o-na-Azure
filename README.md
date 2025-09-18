Durante a análise das soluções disponíveis, destaquei duas ferramentas bastante interessantes: Azure Arc e Azure Resource Manager (ARM).
🔷 Azure Arc
O Azure Arc é uma solução SaaS voltada para o gerenciamento de ambientes multicloud. De forma resumida, ele permite que empresas que utilizam diferentes provedores de nuvem — como AWS e GCP — centralizem a visualização e o gerenciamento de recursos em uma única plataforma, o portal do Azure.
É importante destacar que algumas funcionalidades específicas continuam restritas aos consoles nativos de cada provedor, o que impõe certas limitações sobre o que pode ser controlado diretamente pelo Arc.
🔷 Azure Resource Manager (ARM)
O ARM funciona como uma camada de abstração que interpreta e organiza as informações recebidas de diferentes fontes — como código, portal do Azure ou solicitações de clientes — e as traduz para execução dentro do ambiente Azure.
Essa ferramenta permite a criação e o gerenciamento de recursos de forma automatizada e padronizada, facilitando a implantação de infraestrutura como código e garantindo maior controle e consistência nos processos.
