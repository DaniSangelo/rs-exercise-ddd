### Entidades

#### Produto
* ID
* Nome
* Tamanho
* Cor
* Quantidade em estoque
* Quantidade mínima de estoque

#### Movimentação de Estoque
* ID
* Produto
* Tipo de movimentação (entrada/saída)
* Quantidade
* Data da movimentação

#### Venda
* ID
* Produto
* Quantidade
* Preço unitário
* Data da venda
* Lucro

#### Ordem de Compra
* ID
* Produto
* Quantidade
* Data de criação
* Status (pendente/em processamento/concluída)
* Fornecedor

#### Fornecedor
* ID
* Nome
* Informações de contato
* Prazos de entrega

#### Alerta
* ID
* Produto
* Tipo de alerta (estoque baixo)
* Data de emissão
* Métodos de notificação (e-mail, sistema)

### Casos de Uso

Gerenciar Produtos
Rastreamento de Produtos
Definir Quantidades Mínimas de Estoque
Gerar Alertas
Visualizar Histórico
Gerenciar Ordens de Compra
Integrar com Fornecedores
