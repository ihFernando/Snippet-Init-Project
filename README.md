# Snippet-Init-Project

Criação de alguns snippets a mais para o sublime utilizando o **Emmet**
	
## Como adicionar ao Emmet

Com o Emmet instalado, basta abrir o arquivo de *Preferences -> Package Settings -> Emmet -> Settings - User* e adicionar o código abaixo:

		{
			"snippets": {
				"html": {
					"abbreviations": {
						"meta-basico": "meta[name='viewport' content='width=device-width, initial-scale=1, shrink-to-fit=no']+meta[name content]+meta[name='description' content]+meta[name='author' content]+meta[name='reply-to' content]+meta[name='language' content='Portuguese']+meta[name='theme-color' content]",


						"meta-rede-social": "meta[property='og:title' content]+meta[property='og:description' content]+meta[property='og:site_name' content]+meta[property='og:type' content='website']+meta[property='og:locale' content='pt_BR']",


						"bts-cdn": "link[href='https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css' type='text/css' rel='stylesheet']+script[src='https://code.jquery.com/jquery-3.2.1.slim.min.js']+script[src='https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js']+script[src='https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js']"
					}
				}
			},
		}

## Meta Básico
O primeiro é para criação de *metas basicos*

#### Resultado
Para ativar o snippet use *meta-basico+tab*

	<!-- Viewport-->
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

	<!-- Info site -->
	<meta name="description" content="">
	
	<!-- Autor -->
	<meta name="author" content="" />
	<meta name="reply-to" content="" />
	
	<!-- Linguagem-->
	<meta name="language" content="Portuguese" />
	
	<!-- Color Navegador -->
	<meta name="theme-color" content="">


## Meta Redes Sociais
O segundo é para chamada de metas para redes sociais

#### Resultado
Para ativar o snippet use *meta-rede-social+tab*

	<meta property="og:title" content="">
	<meta property="og:description" content="">
	<meta property="og:site_name" content="">
	<meta property="og:type" content="website">
	<meta property="og:locale" content="pt_BR">

## Bootstrap CDN
O terceiro serve para chamar o cdn do Bootstrap 4

#### Resultado
Para ativar o snippet use *bts-cdn*

	<!-- CSS -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" type="text/css">

	<!-- JS -->
	<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js"></script>