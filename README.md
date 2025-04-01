
# 📂 Projeto: Gerenciamento de Usuários e Diretórios no Linux
Este projeto faz parte do Bootcamp da DIO sobre Fundamentos do Linux e tem como objetivo criar diretórios, grupos e usuários no sistema, além de definir permissões de acesso adequadas para cada grupo.

## 🛠️ Funcionalidades
✔️ Criação de diretórios específicos para cada grupo de usuários
✔️ Criação de grupos de usuários
✔️ Criação de usuários e adição aos grupos correspondentes
✔️ Configuração de permissões para garantir acesso adequado

## 📜 Estrutura do Script
O script executa as seguintes ações:

Criação de diretórios:

/publico

/adm

/ven

/sec

Criação de grupos:

GRP_ADM (Administrativo)

GRP_VEN (Vendas)

GRP_SEC (Segurança)

Criação de usuários e associação aos grupos:

GRP_ADM: carlos, maria, joão

GRP_VEN: debora, sebastiana, roberto

GRP_SEC: josefina, amanda, rogerio

Definição de permissões:

Diretórios /adm, /ven e /sec são acessíveis apenas para seus respectivos grupos

Diretório /publico pode ser acessado por todos os usuários

🚀 Como Executar
Clone o repositório ou copie o script para um ambiente Linux

Dê permissão de execução ao script:

bash
Copiar
Editar
chmod +x nome_do_script.sh
Execute o script com privilégios de superusuário:

bash
Copiar
Editar
sudo ./nome_do_script.sh
⚠️ Observações
O script utiliza openssl para gerar senhas criptografadas. Caso necessário, altere as senhas antes de executar.

Certifique-se de rodar o script como root para evitar erros de permissão.

📌 Tecnologias Utilizadas
Shell Script

Comandos básicos do Linux (mkdir, groupadd, useradd, chmod, chown)

📄 Licença
Este projeto foi desenvolvido como parte do Bootcamp da DIO e está disponível para uso e modificação conforme necessário. 🚀

Se precisar de alguma modificação ou quiser personalizar mais, me avise! 🚀
