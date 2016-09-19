# Snippet-Init-Project
Snippet para inicialização de projeto utilizando sublime.

<pre>
	<code>
{
	"snippets": {
		"html": {
			"abbreviations": {
				"meta-basico": "meta[name content]+meta[description content]+meta[viewport content='width=device-width, initial-scale=1 user-scalable=no']+meta[keywords content]",


				"meta-rede-social": "meta[property='og:title' content]+meta[property='og:description' content]+meta[property='og:site_name' content]+meta[property='og:type' content='website']+meta[property='og:locale' content='pt_BR']+link[rel='shortcut icon' href='']",


				"bts-cdn": "link[href='https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css' type='text/css' rel='stylesheet']+script[src='https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js']",


				"material-cdn": "link[href='https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.7/css/materialize.min.css' type='text/css' rel='stylesheet']+script[src='https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.7/js/materialize.min.js']"
			}
		}
	},
}
	<code>
<pre>

------------------------------------------------------------------------------------------------------------------------------

SNIPPET PARA CHAMAR 'METAS BASICOS' 
	<!--Para ativar o snippet use "meta-basico" -->
	meta-basico+tab
	<meta name="" content="">
	<meta description="" content="">
	<meta viewport="" content="width=device-width, initial-scale=1 user-scalable=no">
	<meta keywords="" content="">
	
	===============================================================================
	
SNIPPET PARA CHAMAR 'METAS COMPLEMENTARES' DE REDES SOCIAIS 
	<!--Para ativar o snippet use "meta-rede-social" -->
	meta-rede-social+tab
	<meta property="og:title" content="">
	<meta property="og:description" content="">
	<meta property="og:site_name" content="">
	<meta property="og:type" content="website">
	<meta property="og:locale" content="pt_BR">
	<link rel="shortcut icon" href="">
	
	=================================================================================
	
SNIPPET PARA CHAMAR 'CDN BOOTSTRAP' VERSÃO 3.3.7 (BASTA MUDAR NUMERO DA VERSÃO PARA OBTER A ATUAL) 
	<!-- Para ativar o snippet use "bts-cdn" -->
	bts-cdn+tab
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" type="text/css">
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
	
	==================================================================================
	
SNIPPET PARA CHAMAR 'CDN MATERIAL' VERSÃO 0.97.7 (BASTA MUDAR NUMERO DA VERSÃO PARA OBTER A ATUAL) 
	 <!--Para ativar o snippet use "material-cdn" -->
	 material-cdn+tab
	 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.7/css/materialize.min.css" type="text/css">
	<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.7/js/materialize.min.js"></script> -->
