---README---

<html>
	<head>
		
			<title>My webpage</title>
			<link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet"><!--referência da fonte utilizada-->

	
	</head>

	<style type="text/css"> <!-- cria regras de estilos para as tags-->
			
			#absolut{
				color:#D4BA2AFF;
				width: 80%; 
				position:absolute;
			}
			
			#barra{
				color:white;
                background-color: blue;
                width:100%; <!-- largura da camada-->
                padding: 0; <!-- margem que cola no topo-->
                top: 0;
	            position:fixed;
                font-style: italic;
            }

			#square-green{
                background-color:green;
                border-radius: 50%;
            }
			
			#backtop{
				position: fixed;
				top: 550px; <!-- margem superior-->
				height: 20px;
			 	width: 60px;
				left: 90%;
				z-index: 100; <!-- faz com que a camada fique acima dos objetos do site-->
			}

			#square-blue{
                background-color:blue;
                border-style: ridge solid dotted dashed;
             }

			.red{
					color:red;
			}

			.large{
					font-size:200%;
			}

			#green{
					color:green;
			}

           .square{
                width: 100px;
                height:100;
                margin: 40px;
                float:left;
			}	
			
			.linkund{
				color: blue;
				font-size: 14pt;
			}
			

			a{
				text-decoration: none; <!-- retira o underline do link-->
			}

			a:hover{
				color:#0EF010FF;
				text-decoration: underline; <!-- faz mostrar underline quando o mouse passa sobre o link--> 
			}
			
			a:visited{
				color: blue;

			}

			div {
				width: 300px;
				
			}

			.centered{
				text-align: center;
			}

			body{
                margin:0;
                padding:0;
            }

			
			p {
            
                margin:0;
                padding:0;
                font-weight: bold;      
            }

            ol{
            	margin:10px 20px 30px 50px;
            	padding: 0;
            	font-family: 'Raleway', sans-serif;
            	text-decoration: 1
            }

	</style>
		

	<body>
		
		<p id="absolut">Barra que se mantem</p>
		<p id="barra"> Barra superior fixa</p>


		<h1>Pág 1</h1>
			

			<p id="top">Here is some <strong>bold</strong> text</P> 
			
			<p>Here is some <em>italic</em> more text</P>
			
			<p>Here is some<u>underline</u> text<br>with line break</p>
			
			<hr>
			
			<p>Here is some <sup>superscript</sup> more text</P>
			
			<p>Here is some <sub>subscript</sub> text </p>
			
			<p>Here is some <del>deleted</del> text</p>
			
			<p> Here is some <small>small</small> Formatting</p>
			
			<ol start="10">
			
				<li><strong>Rob</strong></li>
				
				<li><em>Kirten</em></li>
				
				<li><del>Tommy</del></li>
						
			</ol>
			
			<ol type="a"> <!--várias tipos de modelos para listas ordenadas-->
			
				<li><strong>Rob</strong></li>
				
				<li><em>Kirten</em></li>
				
				<li><del>Tommy</del></li>
						
			</ol>
						
			<ul>

				<li><strong>Rob</strong></li>
				
				<li><em>Kirten</em></li>
				
				<li><del>Tommy</del></li>
			
			<hr>
			
			</ul>
				
				<p>Homer Simpson</p>
				<img src="Homer.png" alt="Imagem do Homer" width="300" height="300" align="right"><!--right, middle, top, bottom-->
				<h2>Lute para ter</h2>
				<p><a href="https://goo.gl/RTJNtY"><img src="patinhas.png" alt="Imagem Tio Patinhas" style="widht:260px;height:260px"></a></p>
		
			<hr>
			<!--FORMULÁRIOS-->
			<form> <!--representa uma seção de um documento que contém controles interativos que permitem ao usuário submeter informação a um determinado servidor web-->
				
				<p>Username: <input type="text" placeholder="your username"></p> <!--caixa de preenchimento-->
				<p>Stay logged in:<input type="checkbox"></p> <!-- box de marcação. aceita múltiplas marcações-->
				<p> &nbsp; Wealth <input type="radio" name="age"></p><!-- box para única marcação-->
				<p>&nbsp; &nbsp; &nbsp; or &nbsp;</P> 
				<p>Poverty: <input type="radio" name="age"></p><!-- ''-->
				<!--<input> é usado para criar controles interativos para formulários baseados na
				web para receber dados do usuário-->
			
				<p> Favorite Food: <!--drop box-->
					
					<select>
						
						<option>Pizza</option> 
						<option>Ice Cream</option>
						<option>Sandwiches</option>
						
						
					</select>
				
				</p>
				
				<p><input type="submit" value="Me clica!"</p>
			
			</form>		
			
			<form action="https://www.w3schools.com/html/default.asp">
				
				<p><input type="submit" value="Click Here to w3school!"></p>
			
			</form>
						
			<form>
				<table>
			
					<thead>	<!--cabeçalho-->	
					
						<tr>
						
							<th>Name</th>
							<th>Favorite<br>Color</th>
						
						</tr>
					
					</thead>
				<hr>
					<tbody>
				
						<tr> <!--table row, linha da tabela-->
				
							<!--dados-->
							<td>Rob</td>
							<td>Green</td>		
				
						</tr>
						<tr>	
				
						<td>Kirsten</td>
						<td>Orange</td>
					
						</tr>
					</tbody>
				</table>
			</form>
		
			<hr>
			
			<!--Links-->
			
			<p><a href="http://www.wikipedia.com">Clique para ir p wiki.</a></p>
			<p><a href="http://www.google.com"><img src="google.png" style="widht:160px;height:160px"align="right"></a></p>
			<p><a href="HImlearning.html"><img src="eu.png" alt="Ronaldo Teles"id= width="'100" height="100" align="top"></a></p> <!--link relativo, no pc-->
			<p><small>Eu devorando</small></p>
					
		
			<p style="color:yellow;font-size:50%"> nova página</p> <!--CSS-->		
			<h1 style="color:green;font-size:250%">Css is cool</h1>
		
			<div>
				<p>This is some aligned text</p>
				<p class="centered">THis is somw centered text</p>
				<p class="justified">This is some justified textThis is some justified textThis is some justified textThis is some justified text</p>

			</div>

		<hr>

			<div id="square-blue" class="square"> </div>
        
	   		<p><div id="square-green" class="square"> </div></p>
       		
       		<br>
			<p class="red">Dentro da classe de estilo 'red'</p>
			<p class="large">Dentro da classe de estilo <span class="red">'large' e 'red'</span></p>
			<p id="green">ID, como a classe, <span class="underlined">mas evita-se usar.</span></p>
			<h1 class="red">Css is cool</h1>
			<h2 class="stilos"> <u>Aqui</u> <span class="underlined red">misturam-se </span> <em>estilos</em></h2>
			<div id="backtop"><a href="#top"><img src="arrowup.png" widht="50" height="80" align="right"></a></p></div>
			
	
			<p class="linkund"><a href="http://www.google.com">Este é um link</a></p>
			<p class="linkund"><a href="http://www.google.com" target=_blank>Este é um link</a></p><!--abre o link em nova página-->
		
		
		
	</body>


</html>