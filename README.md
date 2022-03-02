# google_bigquery_datastudio
Este repositório contém os estudos para o curso: Formação Google Big Query e Data Studio. 

# Google Data Studio: Introdução à ferramenta. 

[Relatório de conclusão de curso.](https://datastudio.google.com/reporting/e5b74b36-82e9-44eb-8742-4480975384ba)

# Google Data Studio: Acessando o MySQL

**- Porta 3306:** Porta de acesso padrão ao MySQL.

**- pla:** planilha.

Para ter o acesso da base de dados local pelo Data Studio que está na web, devemos abrir no Firewall a porta 3306, colocar um IP público para permitir o acesso remoto e ativar o protocolo HTTPS para ser certificado por segurança.

![image](https://user-images.githubusercontent.com/81119854/156402197-417a3bfb-8280-425f-bb69-27c41852fa0d.png)

- Vamos construir a estrutura abaixo: 

![image](https://user-images.githubusercontent.com/81119854/156403437-fb83fac1-e505-419b-bfc9-a5dbe1463272.png)

**Etapas** 

1. Criar uma conta na Google Cloud;
2. Criar um banco de dados MySQL;
3. Instalar o MySQL Workbench;
4. Criar uma conexão entre o MySQL Workbench e o MySQL BD;
5. Criar e popular o nosso banco exemplo;
6. Configurar o Data Studio para acessar o MySQL BD;
7. Construção de relatórios. 

- SQL:

![image](https://user-images.githubusercontent.com/81119854/156418277-b4d20712-1f1d-419c-a0d9-19c395644b3a.png)

- Criar instância:

![image](https://user-images.githubusercontent.com/81119854/156418531-e4060908-00fc-4844-a813-8cb6784e3014.png)

- Escolher MySQL:

![image](https://user-images.githubusercontent.com/81119854/156418678-a2441fc1-ecf2-430b-9a4b-5bd7ee0703fe.png)

- Ativar API:

![image](https://user-images.githubusercontent.com/81119854/156418893-01a6b503-234b-4a64-bc33-796860b6e4ab.png)
