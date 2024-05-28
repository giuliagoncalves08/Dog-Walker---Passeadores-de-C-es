In-Dog
Overview:
In-Dog é uma plataforma desenvolvida em Laravel que visa ajudar donos de cães que vivem uma rotina agitada a garantir que seus 
melhores amigos de quatro patas recebam a atenção e os passeios necessários, mesmo nos dias mais movimentados. Com o In-Dog, os usuários 
podem agendar passeios para seus cães com dog walkers confiáveis e experientes, garantindo assim que seus animais de estimação estejam felizes e saudáveis.

Recursos Principais
Agendamento de Passeios: Os usuários podem agendar passeios para seus cães de acordo com sua disponibilidade e necessidades.

Seleção de Dog Walkers: A plataforma oferece uma lista de dog walkers confiáveis e experientes para os usuários escolherem.

Acompanhamento em Tempo Real: Os usuários podem acompanhar o passeio de seus cães em tempo real por meio de notificações e atualizações no aplicativo.

Perfil de Usuário e Cão: Os usuários podem criar perfis para si mesmos e para seus cães, incluindo informações importantes como raça, 
idade e necessidades especiais.

Instalação
1-Clone o repositório para sua máquina local:
git clone https://github.com/seu-usuario/in-dog.git

2-Instale as dependências do Composer ou user o projeto modelo que iremos disponibilizar:
composer install

3-Copie o arquivo .env.example para .env e configure suas variáveis de ambiente, incluindo as configurações do banco de dados e as chaves de API necessárias.

4-Gere a chave de aplicativo Laravel:
php artisan key:generate

5-Execute as migrações do banco de dados para criar as tabelas necessárias:
php artisan migrate

6-Inicie o servidor de desenvolvimento:
php artisan serve

Contribuição
Contribuições são bem-vindas! Para contribuir com o In-Dog, siga estas etapas:

Faça um fork do repositório e clone-o para sua máquina local.
Crie uma branch para sua feature ou correção: git checkout -b feature/nova-feature.
Desenvolva suas alterações e faça commits explicativos: git commit -m "Adiciona nova feature".
Envie suas alterações para o repositório remoto: git push origin feature/nova-feature.
Abra um pull request descrevendo suas alterações.

Licença

Este projeto está licenciado sob a Licença MIT.


