# server-tutor
Projeto Tutor: Implantação e Gerenciamento de Servidores de hospedagem e Micro SaaS Linux
O Projeto Tutor é um software de backend escrito em Python 3.9, flask e Gunicorn rodando sob o Apache com Mariadb, projetado para facilitar a implantação, personalização e gerenciamento de servidores Linux. Ele oferece uma solução para hospedar sites, configurar domínios, gerenciar certificados SSL e disponibilizar MicroSaas de forma extremamente rápida e fácil. Vamos explorar as funcionalidades detalhadamente:

Funcionalidades Principais
Esqueleto e Páginas Web Funcionais para o Site Principal:
O projeto fornece um esqueleto básico para o site principal da empresa. Você pode personalizar essas páginas conforme necessário.
Esqueleto Básico para Páginas em Construção de Novos Domínios:
Quando um novo domínio é adicionado, o software cria automaticamente uma página em construção. Isso permite que você configure os novos domínios rapidamente.
Configuração Automática de Novos Domínios no Apache:
A função automatizada escreve os arquivos de configuração do Apache para os novos domínios. Isso simplifica a configuração e garante que os domínios sejam corretamente direcionados.
Configuração Automática de HTTPS (SSL) para os Domínios:
O projeto cuida da configuração HTTPS para os domínios, tornando a segurança uma prioridade.
Função de DNS Interno:
O software age como um servidor DNS interno, indicando o Vhost correto para cada domínio no mesmo servidor.
Recebimento PIX pela EFI com Geração de QR Code:
Os clientes podem fazer pagamentos via PIX, com geração de QR Code para depósito direto em sua conta.
Verificação Instantânea de Pagamentos e Atualização de Saldo:
Um script verifica os pagamentos instantaneamente e atualiza o saldo na conta do cliente.
Cadastro de Clientes com Página Específica para Cada Cliente Logado:
Os clientes têm acesso a uma página específica após o login, onde voce pode disponibilizar informações ou serviços.
Armazenamento Criptografado de Senhas na Base de Dados:
A segurança das senhas é garantida por meio de criptografia.
Integração com Servidor SMTP para E-mails de Conta e Avisos do Sistema:
Recomendo o uso da Brevo (https://www.brevo.com/pt/) para envio de e-mails. Isso será útil para criação de contas, notificações do sistema e recuperação de senhas pelos clientes.
Inegração da API da OpenAI - Para você poder utilizar em MicroSaas e também para funções próprias que serão lançadas no futuro, como geração de conteudo, relatorios, marketing etc.
Próximos Passos
Após implementar essas funcionalidades básicas que já estão concluídas e estão em fase de organização para lançamento, vou trabalhar nas seguintes soluções:

Servidor de E-mail Próprio para os Domínios:
Integração completa com Revendas CPANEL e autocontratação de serviços pelo cliente.(Uma opção a mais de hospedagem, mas o foco principal é a autohospedagem no próprio servidor.)
API para disponibilização de Micro serviços (já em desenvolvimento)
Integração da API da IA Claude da Anthropic https://www.anthropic.com/

O projeto será disponibilizado no dia 30/06/2024 aqui no GitHub.

