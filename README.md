# geoCNPJ

Repositório para GeoCodificação dos endereços do CNPJ para todo o Brasil

## Motivação

O Cadastro Nacional de Pessoa Jurídica (CNPJ) está disponível para download https://dados.gov.br/dados/conjuntos-dados/cadastro-nacional-da-pessoa-jurdica---cnpj contendo os dados cadastrais de todas as empresas do BRasil. Esse dado é muito importante para a pesquisa pois contém entre outras informações o CNAE (CAdastro Nacional de Atividades Economicas), cuja especificação pode ser consultada em https://ibge.gov.br/estatisticas/metodos-e-classificacoes/classificacoes-e-listas-estatisticas/9078-classificacao-nacional-de-atividades-economicas.html . No entanto esses registros não estão espacializados, ou seja, não podem ser mapeados pelos seus locais, algo importante, por exemplo, para estudar acessibildiade a estabelecimentos de Saúde, Alimentação, Educação entre outros.

## Objetivo

Portanto, o objetivo desse repositório é criar um método para espacializar todos os registros da Base de CNPJ, disponibilizando assim tanto o dado processado quanto disseminando o método para ele poder ser replicado, modificado e até melhorado.

## Materiais e Métodos

Localizar um ponto geográfico por um endereço não é algo trivial sobretudo para uma base de dados tão grande quanto o cadastro do CNPJ. Iremos utilizar recursos computacionais e frameworks de código aberto que utilizam dados abertos disponíveis para fazer essa espacialização. Sendo eles: [Pelias](https://pelias.io/) e [Nominatin](https://nominatim.org/)

## Validação

Será necessário uma validação amostral para podermos calcular o grau de confiança no processo de GeoCodificação, para isso será separada uma amostra para que seja feita uma busca manual pelo endereço afim de determinar a acurácia do processamento.

## Resultados

Os resultados assim que estiverem processados serão disponibilizados aqui nesse repositório ou em link indicado.
