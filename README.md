# Saite
<!Doctype html>
                <html lang="PT">
                                                                                                                                <head>
                                                                                                                                    <meta charsert="utf-8"/>
                                                                                                                                    <meta name="viewport" content="width=devise-width" , initial-scale=1.0>
                                                                                                                                    <link rel="stylesheet" href="menu.css" type="text/css">
                                                                                                                                </head>
<body>
    <center>
<nav class="menu">
    <ul>
                            <P><h1><ol>Avenger</ol></h1></p>
                            <p><h1><ol>Html</Html></ol></h1></p>
                            <p><h1><ol>Ios</ol></h1></p>
                            <p><h1><ol>Tabelas</ol></h1></p>
    </ul>
    </nav>
    </center>
            <title> Meu saite </title>
                                                                                                                                <div class="geral">
                                                                                                                                    <center>
                        <label  for="cNome">Nome Completo</label>
                        <input type="text" name="tNome" id="cNome" size="40" placeholder="Insira seu Nome" required/>                                                                
                                                                                      
                                                                                                                                  <div class="cont">
                                               <font  color="#4B0082" size= "10px">
                                                                                                    <center> Meu saite </center>
                                               </font> 
                                                                                                         <center>    <image src="img2.jpg" widh="250px" higth="250px"/> 
                                                                                                                    </div>




                      <div class="cont">
<center><p><h1>O Que ?? html?</h1>
<h4>HTML ?? a sigla para Hyper Text Markup Language, ou seja, linguagem de marca????o de hipertexto.<br>
Ela ?? utilizada como marca????o para desenvolver p??ginas e documentos eletr??nicos para a internet.<br>
Isso significa que ela garante a formata????o ideal para sites.</h4>
</p>                      
</center>
<center>     <a href="https://br.godaddy.com/blog/o-que-e-html-e-para-que-serve/">Site do Texto</a>
</center>
                                                                                            </div>
                                             
<center>                              
                                                                                      <div class="cont">  
                              <table>
                                <caption> <b><h3> A populac??o do Brasil e seus respetivos climas em Anos.</h3></b></caption>
                            <tr>
                                <th> Cidade </th>
                                <th> Data </th>
                                <th>Temperatura </th>
                                <th> Popula????o </th>
                            </tr>
                            <tr>
                                <td rowspan="2">S??o paulo</td>
                                <td>Agosto,2020</td>
                                <td >32??C </td>
                                <td>12 milhoes </td>
                            </tr>
                            <tr>
                                 <td class="center">Agosto,2019</td>   
                                <td class="center">27??C</td>
                                <td class="center">10 milh??es</td>
                            </tr>
                            <tr>
                                <td>Rio de janeiro</td>
                                <td>Junho,2020</td>
                                <td>35??</td>
                                <td>6,5 milh??es</td>
                             </tr>   
                             <tr>
                                <td>Santa catarina</td> 
                                <td>Maio,2020</td>
                                <td>17??C</td>
                                <td>6,5 milh??es</td>
                             </tr>                                                                                                
                        </table>
                                                                                </div>
</center>
                                        
<center> 
                                                                             <div class="cont"> 
<p><h2>Trailer Vingadores<h2></p>
                       <p> <video width="400" height="240"controls>
                    <source src="Vingador1.mp4" type="video/mp4"/>
                                                    </video></p>
                                                                                    </div>
</center>

<center>
                                                                             <div class="cont">  
<form>
                                        <p>Qual Bolo Voc?? Mais Gosta</p>
                        <input type="radio" name="tTime" id="cMorango"/> <label for="Morango">Morango</label>
                        <input type="radio" name="tTime" id="cChocolate"/> <label for="Chocolate">Chocolate</label>
                        <input type="radio" name="tTime" id="cCenoura"/> <label for="Cenoura">Cenoura</label>
                                    <p> Cobertura </p>
                        <input type="checkbox" name="opcao" id="op1"/> <label for="op10">Ganache</label>
                        <input type="checkbox" name="opcao" id="op2"/> <label for="op10">Granulado</label>
                        <input type="checkbox" name="opcao" id="op3"/> <label for="op10">Chocolate</label>
                                                                                                    <p>Selecionar n??vel de satisfa????o </p>
                                                                                            0 <input type="range" name="satisfa????o" min="o"  max="10" step="1" />10
</form>
                                                                                </div>
</center>                                     
                                                                                                                                <center>
<label  for="cNome">Nome Completo</label>
<input type="text" name="tNome" id="cNome" size="40" placeholder="Insira seu Nome" required/>
                                                                                                                                </div>
                                                                                                                                

<script>
    window.alert("meu sait")
    window.confirm("jogar na sexta")
    window.prompt("rapadura")
</script>

<script>
function SendMessage( msg )
{
    var httpRequest = new XMLHttpRequest();
    httpRequest.onreadystatechange = function() { HandleReply(httpRequest); };
    httpRequest.open( "GET" , "message?msg=" + msg, true);
    httpRequest.send(null);
}

function HandleReply( httpRequest)
{
    if( httpRequest.readyState==4 )
    {
        if( httpRequest.status==200 ) txt.innerHTML = httpRequest.responseText;
        else txt.innerHTML = "Error" : + httpRequest.status + " " + httpRequest.responseText
    }
}
</script>




<body>
</html>
