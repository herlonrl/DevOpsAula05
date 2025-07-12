# DevOpsAula05

Desafio CI/CD
Seu feedback:

😡angry
😔sad
😑emotionless
🙂happy
😍love it
Marcar como concluído
Por favor, avalie a sua experiência

😡angry
😔sad
😑emotionless
🙂happy
😍love it
Muito ruim
Muito bom
Anterior
Vocês Avanters foram contratados pela Oi, Sumido Soluções Criativas que tem em seu carro chefe uma lucrativa aplicação de venda de saudações aleatórias escrita em Golang (ms-saudacoes-aleatorias).



O processo de entrega da aplicação em produção, é um processo manual, cheio de erros, cada profissional que faz a implantação faz do seu jeito, o que acarreta na perda de receita e usuários para a principal empresa concorrente, a Odete Roitmann SA com sua aplicação de venda de insultos aleatórios.



A missão de vocês é ajudar a empresa no desenvolvimento de uma pipeline automatizada de entrega da aplicação de saudações aleatórias em produção.



Para essa missão, vocês podem usar o Gitlab ou o Github Actions, sendo que vocês devem usar o template abaixo para construir a pipeline para cada um deles

Gitlab - https://gitlab.com/-/snippets/4868582

Github Actions - https://gitlab.com/-/snippets/4868580



Vocês devem criar um repositório na conta de vocês do Github ou Gitlab, usando este repositório como modelo:

https://gitlab.com/avanti-dvp/ms-saudacoes-aleatorias



Percebam que é um dos repositórios do desafio da Imagens Docker, então caso já o tenham, vocês precisam atualizá-lo.

Porque ele recebeu as seguintes alterações:

- Dockerfile na raiz do repositório

- Diretório de infra, com os arquivos do terraform 



Esses arquivos acima, não precisarão e não deverão ser alterados, para este desafio.



Para começar o desenvolvimento da pipeline, vocês precisam:

- Caso esteja usando o Gitlab, criar o arquivo .gitlab-ci.yml na raiz do repositório

- Caso esteja usando o Github Actions, criar o diretório .github/workflows e criar o arquivo main.yml



Se atentem para o correto preenchimento e criação das variáveis DOCKER_USER, DOCKER_PASS, KOYEB_TOKEN (no material complementar se encontra um tutorial de como criar essas variáveis)



A pipeline de vocês deve rodar com sucesso, as seguintes etapas:

- Lint do código (build-lint)

- Testes de aplicação (test)

- Construir a imagem (release)

- Subir a imagem para o Docker Hub (release)

- Fazer o deploy da imagem no Koyeb (deploy)

- Destruir a infraestrutura criada no Koyeb, depois de aprovação manual (cleanup)



As evidências que vocês precisam enviar para a conclusão do desafio, são:

- Uma captura de tela da pipeline rodando todas as etapas com sucesso

- O link do repositório no Gitlab ou Github ou os arquivos .gitlab-ci.yml ou main.yml anexados

- Uma captura de tela do dashboard do Koyeb, mostrando a aplicação rodando



E é isso pessoal, é hora de botar a mão na massa 🍝!



MATERIAL COMPLEMENTAR

Como criar uma conta no Github

https://docs.github.com/pt/get-started/start-your-journey/creating-an-account-on-github

https://www.youtube.com/watch?v=D-qlLy5DNZA



Como criar uma conta no Gitlab

https://www.youtube.com/watch?v=WKEEcdIXImY


O MATERIAL COMPLEMENTAR ANEXADO ABAIXO SÃO VÍDEOS, VOCÊS VÃO PRECISAR BAIXÁ-LOS
