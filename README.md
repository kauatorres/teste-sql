# Teste de SQL Intermediário

Este teste é baseado em um banco de dados PostgreSQL com o seguinte esquema:

- EMPRESA (id_empresa, razao_social, inativo)
- PRODUTOS (id_produto, descricao, inativo)
- CONFIG_PRECO_PRODUTO (id_config_preco_produto, id_vendedor, id_empresa, id_produto, preco_minimo, preco_maximo)
- VENDEDORES (id_vendedor, nome, cargo, salario, data_admissao, inativo)
- CLIENTES (id_cliente, razao_social, data_cadastro, id_vendedor, id_empresa, inativo)
- PEDIDO (id_pedido, id_empresa, id_cliente, valor_total, data_emissao, situacao)
- ITENS_PEDIDO (id_item_pedido, id_pedido, id_produto, preco_praticado, quantidade)
