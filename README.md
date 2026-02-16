# IMDB-Top-Most-Popular-Movies

O código consiste em um scraper desenvolvido em Python para coletar informações da página “Most Popular Movies” do IMDb. Ele utiliza a biblioteca requests para realizar as requisições HTTP e BeautifulSoup para fazer a leitura e extração dos dados presentes no HTML da página. A aplicação acessa a lista dos filmes mais populares, captura os links individuais de cada filme e, em seguida, extrai informações como título, data de lançamento, avaliação e sinopse.

Para tornar o processo mais rápido, o código utiliza programação concorrente com ThreadPoolExecutor, permitindo que múltiplas páginas de filmes sejam acessadas simultaneamente. Após a extração, os dados são organizados e armazenados em um arquivo movies.csv, criando assim um conjunto estruturado de informações sobre os filmes listados no ranking de popularidade do IMDb.

Realizada pequena melhoria adicionando timeout nas requisições HTTP e verificação de status de resposta, tornando a execução mais segura e evitando possíveis travamentos.
