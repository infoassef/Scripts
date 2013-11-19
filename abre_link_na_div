<html>
<head>
<script src="http://code.jquery.com/jquery-1.10.1.min.js"></script>
<script type="text/javascript">
/*--AJAX ABRE LINK EM DIV--*/
function abrirPag(valor){ 
	var url = valor; 
	xmlRequest.open("GET", url, true); 
	xmlRequest.onreadystatechange = mudancaEstado; 
	xmlRequest.send(null); 
	if (xmlRequest.readyState == 1) { 
	document.getElementById("conteudo").innerHTML = "<img src='loader.gif'>"; 
	} 
	return url; 
	} 
	function mudancaEstado(){ 
	if (xmlRequest.readyState == 4){ 
	document.getElementById("conteudo").innerHTML = xmlRequest.responseText; 
	} 
	} 
/*--AJAX ABRE LINK EM DIV--*/

/*--JS ABRE LINK EM DIV--*/
function GetXMLHttp() { 
	    if(navigator.appName == "Microsoft Internet Explorer") { 
	    xmlHttp = new ActiveXObject("Microsoft.XMLHTTP"); 
	    } else { 
	    xmlHttp = new XMLHttpRequest(); 
	    }     
	    return xmlHttp; 
	} 
	var xmlRequest = GetXMLHttp(); 
/*--JS ABRE LINK EM DIV--*/
    </script>
</head>
<body>
<a href="#" onclick="abrirPag('teste.hml');" style="text-decoration: none">Abre site na Div</a> 
<div id="conteudo"></div>
</body>
</html>
