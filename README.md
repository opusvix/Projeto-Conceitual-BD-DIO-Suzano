# Refinando um Projeto Conceitual de Banco de Dados E-COMMERCE:

#### Projeto proposto no Bootcamp [Geração Tech Unimed-BH - Ciência de Dados](https://www.dio.me/bootcamp/geracao-tech-unimed-bh-ciencia-de-dados?ref=CG-bootcamp-unimed-bh-ciencia-de-dados) na plataforma [DIO.](https://www.dio.me/)

### Descrição do Desafio
_"Modelamos juntos um contexto reduzido de e-commerce. Agora é a sua vez, podes escolher a ferramenta de modelagem para realizar o desafio. Contudo, fique atento! Caso opte por uma variação do modelo entidade relacionamento, como nas ferramentas Mysql Workbench ou DBDesigner será preciso especificar as PK e FKs corretamente. Apesar desse conceito não ser utilizado na modelagem conceitual exploramos brevemente suas definições. Sendo assim, seu empregável será o esquema conceitual para o cenário de E-commerce."_ 

Instrutora: *Juliana Mascarenhas*
</b>

### Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;



## Ferramentas utilizadas

- [MySQL Workbench](https://www.mysql.com/products/workbench/)



## Respostas do Desafio



- Para a entidade Cliente foram criadas duas novas entidades  ``PJ_Pessoa Juridica`` e ``PF_Pessoa Fisica`` contendo as informações de CNPJ e CPF.
- No caso de Pagamento a entidade esta atribuída a outras duas entidades afim de detalhar as formas de pagamento : Cartão e Boleto.
- Entrega foi criada para armazenar as informações de envio de cada pedido detalhar como data do pedido, data de envio e data de entrega.



## Certificado



