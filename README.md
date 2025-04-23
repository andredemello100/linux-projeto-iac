🛠️ Gerenciamento de Usuários e Permissões no Linux — Script de Infraestrutura como Código (IaC)
Este script automatiza a criação de estrutura de diretórios, grupos de usuários, contas de usuários e configurações de permissões em um servidor Linux. Ele segue o conceito de Infraestrutura como Código (IaC), facilitando a padronização e a repetibilidade do ambiente de trabalho.

📄 O que o script faz:
Cria os diretórios: /publico, /adm, /ven, /sec.

Cria grupos de usuários: GRP_ADM, GRP_VEN, GRP_SEC.

Cria usuários e os associa aos respectivos grupos.

Define shells padrão e senhas criptografadas para os usuários.

Aplica permissões apropriadas aos diretórios com base nos grupos.

Garante que cada grupo tenha acesso apenas ao seu diretório e que o diretório /publico seja acessível a todos.

💡 Objetivo:
Automatizar tarefas administrativas comuns em ambientes corporativos, como o provisionamento de usuários e a aplicação de políticas de acesso baseadas em grupos.

🧪 Requisitos:
Execução como superusuário (root)

Pacote openssl instalado no sistema
