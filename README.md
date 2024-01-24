# CRUD1

Este foi meu primeiro projeto CRUD.

#### Linguagem Utilizada: C++

Na elaboração deste projeto, busquei simular o funcionamento de uma loja de veículos. O usuário pode adicionar carros, incluindo informações como preços, modelos, marcas, tipos e observações. Além disso, há a capacidade de adicionar, editar e excluir carros que já fazem parte do banco de dados, o qual utilizei um arquivo de texto simples para armazenar esses dados.

A lógica implementada é a seguinte: ao iniciar o programa, é criado um vetor com um tamanho especificado na primeira linha do arquivo de texto. Cada posição do vetor contém as informações de um carro. Conforme o programa avança, mais posições são adicionadas ao vetor. Ao ser encerrado, o programa salva os dados dos carros em categorias separadas por um ';', no arquivo de texto.

Adicionalmente, implementei um sistema de busca de carros por placas. Isso permite ao usuário escolher entre modificar ou excluir um veículo já salvo no vetor. Se não encontrar a placa, o programa retorna ao menu com uma mensagem informando que a placa não foi encontrada.
