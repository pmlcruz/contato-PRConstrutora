# contato-PRConstrutora
formulário de contato em html, javascript e css


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato</title>
                            </head>
                            <body>
				<div  class =" form-box ">
						<h2> Peça seu orçamento </h2>
						<br >
						< p > < em > Envie seus dados e em breve entraremos em contato </ em > </ p >
						< br >
				   < ação do formulário  =" # " >
				   				< div  class =" grupo de entrada " >
				   								< label  for =" nome " > Nome completo </ label >
				   								< input  type =" text " id =" nome " placeholder =" Digite seu nome completo " obrigatório >	
				   				</ div >
				   							< div  class =" grupo de entrada " >
				   								< label  for =" email " > E-mail </ label >
				   								< input  type =" text " id =" email " placeholder =" Digite seu e-mail " obrigatório >	
				   				</ div >
				   							< div  class =" grupo de entrada " >
				   								< label  for =" telefone " > Telefone </ label >
				   								< input  type =" text " id =" nome " placeholder =" Digite seu telefone " obrigatório >	
				   				</ div >
				   				< br >
				   				< div  class =" grupo de entrada " >
				   								< botão > Enviar </ botão >
				   				</ div >
				   </ forma >
				</ div >
</body>
</html>


########################################################


CSS




*{
    margin: 0;
    padding: 0;
    box-sizing: 0;
}
body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #ff95be;
}
input[type=text], select, textarea{
width: 100%;
padding: 12px;
border: 1px solid #ccc;
border-radius: 4px;
box-sizing: border-box;
resize: vertical;
}
label {
padding: 12px 12px 12px 0;
display: inline-block;
}
