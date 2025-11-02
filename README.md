

# 🚀 Infraestrutura AWS com S3, CloudFront e API Gateway

Este projeto foi desenvolvido no **AWS Infrastructure Composer** utilizando o **CloudFormation** para criar e visualizar uma infraestrutura em nuvem moderna e escalável.

---

## 🧱 Estrutura do Projeto

A arquitetura é composta pelos seguintes recursos da AWS:

1. **Amazon S3 Bucket**

   * Armazena arquivos estáticos (HTML, CSS, JS, imagens etc.).
   * Pode ser configurado como **site estático**.

2. **Bucket Policy**

   * Define as permissões de acesso aos arquivos dentro do bucket.
   * Permite leitura pública dos objetos ou controle via CloudFront.

3. **Amazon CloudFront**

   * Rede de distribuição de conteúdo (CDN) para entregar os arquivos com baixa latência e alta performance.
   * Adiciona uma camada extra de segurança ao ocultar o bucket S3.

4. **API Gateway**

   * Gerencia e expõe endpoints REST ou HTTP para comunicação entre front-end e serviços backend.
   * Pode ser integrado a funções Lambda ou a outras APIs.

---

## 🧩 Diagrama da Arquitetura

A infraestrutura criada segue o seguinte fluxo:

```
S3 Bucket → Bucket Policy → CloudFront → API Gateway
```

![Diagrama da Arquitetura](A_2D_digital_diagram_illustrates_a_cloud-based_sta.png)

---

## ⚙️ Implantação

1. Acesse o **AWS CloudFormation**.
2. Importe o modelo gerado pelo **Infrastructure Composer**.
3. Valide e implante a pilha (stack).
4. Após a implantação, acesse o endpoint do CloudFront ou API Gateway conforme a necessidade.

---

## 💡 Possíveis Extensões

* Adicionar **AWS Lambda** para processar dados antes de armazená-los no S3.
* Usar **DynamoDB** como base de dados backend.
* Integrar o **CloudFront** com certificado SSL (ACM) para HTTPS.
* Adicionar logs de acesso e versionamento no bucket S3.

---

## 🧠 Aprendizados

Durante o desenvolvimento deste projeto, foi possível aprender e praticar:

* Criação visual de infraestrutura com o **Infrastructure Composer**.
* Geração automática de templates **CloudFormation**.
* Conexão entre serviços AWS de forma integrada e segura.

---

## 📚 Tecnologias Utilizadas

* **AWS CloudFormation**
* **AWS S3**
* **AWS CloudFront**
* **AWS API Gateway**

---

## ✨ Autora

👩‍💻 **Bruna Stefany**
Projeto desenvolvido como parte dos estudos e práticas do Bootcamp **Code Girls**. 💜

