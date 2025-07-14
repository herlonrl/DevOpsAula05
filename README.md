# DevOpsAula05 - Desafio CI/CD 🚀

Vocês Avanters foram contratados pela **Oi, Sumido Soluções Criativas**, que tem em seu carro-chefe uma lucrativa aplicação de venda de saudações aleatórias escrita em **Golang** (`ms-saudacoes-aleatorias`).

O processo de entrega da aplicação em produção é um processo **manual**, cheio de erros. Cada profissional que faz a implantação faz do seu jeito, o que acarreta na perda de receita e usuários para a principal empresa concorrente, a **Odete Roitmann SA**, com sua aplicação de venda de **insultos aleatórios**.

A missão de vocês é **ajudar a empresa no desenvolvimento de uma pipeline automatizada** de entrega da aplicação de saudações aleatórias em produção.

Para essa missão, vocês podem usar o **GitLab** ou o **GitHub Actions**, sendo que devem usar o **template abaixo** para construir a pipeline para cada um deles:

- GitLab: [https://gitlab.com/-/snippets/4868582](https://gitlab.com/-/snippets/4868582)
- GitHub Actions: [https://gitlab.com/-/snippets/4868580](https://gitlab.com/-/snippets/4868580)

Vocês devem criar um repositório na conta de vocês do GitHub ou GitLab, usando este repositório como modelo:

🔗 [https://gitlab.com/avanti-dvp/ms-saudacoes-aleatorias](https://gitlab.com/avanti-dvp/ms-saudacoes-aleatorias)

> Percebam que é um dos repositórios do desafio das Imagens Docker. Então, caso já o tenham, **vocês precisam atualizá-lo.**

Ele recebeu as seguintes alterações:

- `Dockerfile` na raiz do repositório
- Diretório `infra`, com os arquivos do Terraform

**Esses arquivos acima não precisarão e não deverão ser alterados para este desafio.**

---

## Para começar o desenvolvimento da pipeline, vocês precisam:

- Caso esteja usando o **GitLab**, criar o arquivo `.gitlab-ci.yml` na raiz do repositório
- Caso esteja usando o **GitHub Actions**, criar o diretório `.github/workflows` e dentro dele o arquivo `main.yml`

**Se atentem para o correto preenchimento e criação das variáveis `DOCKER_USER`, `DOCKER_PASS`, `KOYEB_TOKEN`**  
(O material complementar contém um tutorial de como criar essas variáveis)

---

## ✅ A pipeline de vocês deve rodar com sucesso as seguintes etapas:

1. **Lint do código** (`build-lint`)
2. **Testes de aplicação** (`test`)
3. **Construir a imagem** (`release`)
4. **Subir a imagem para o Docker Hub** (`release`)
5. **Fazer o deploy da imagem no Koyeb** (`deploy`)
6. **Destruir a infraestrutura criada no Koyeb**, depois de aprovação manual (`cleanup`)

---

## 📎 Evidências necessárias para a conclusão do desafio:

- 📸 Uma **captura de tela da pipeline rodando todas as etapas com sucesso**
- 🔗 O **link do repositório** no GitLab ou GitHub **OU** os arquivos `.gitlab-ci.yml` ou `main.yml` **anexados**
- 📸 Uma **captura de tela do dashboard do Koyeb**, mostrando a aplicação rodando

---

E é isso pessoal, **é hora de botar a mão na massa** 🍝!

---

## 📚 MATERIAL COMPLEMENTAR

### Como criar uma conta no GitHub:
- https://docs.github.com/pt/get-started/start-your-journey/creating-an-account-on-github
- https://www.youtube.com/watch?v=D-qlLy5DNZA

### Como criar uma conta no GitLab:
- https://www.youtube.com/watch?v=WKEEcdIXImY

> **O MATERIAL COMPLEMENTAR ANEXADO ABAIXO SÃO VÍDEOS, VOCÊS VÃO PRECISAR BAIXÁ-LOS**
> 
📁 **O material complementar está na pasta `MaterialComplementar`.**

Boa sorte! 🚀💻