# Formulario
Formulário com HTML


<!DOCTYPE html>
<html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
      <link rel="stylesheet" type="text/css" href="formulario.css" media="screen"> 
      <title>Cadastro</title>
  </head>

 <body>
   
       <div>
          <h1 id="titulo">Cadastro de DEVs</h1>
          <p id="subtitulo">Complete as sua informações</p>
          <br>
       </div>

      <form>
          <fieldset class="grupo">
              <div>
                  <label for="nome"><strong>Nome</strong</label>
                  <input type="text" nome="nome" id="nome" required>
              </div>

              <div class="campo">
                  <label for="sobrenome"><strong>Sobrenome</strong></label>
                  <input type="text" nome="sobrenome" id="sobrenome" required>
              </div>
          </fieldset>

          <div class="campo">
              <label for="email"><strong>Email</strong></label>
              <input type="email" nome="email" id="email" required>
          </div>

          <div class="campo">
              <label><strong>De qual lado da aplicação você quer desenvolver</strong></label>
              <label>
                 <input type="radio" nome="devweb" value="frontend" checked>front-end
             </label>
             <label>
                  <input type="radio" nome="devweb" value="backend">Back-end
             </label>
             <label>
                 <input type="radio" nome="devweb" value="fullstack">Fullstack
              </label>
          </div>

          <div class="campo">
             <label for="senioridade"><strong>Senioridade</strong></label>
               <select id="senioridade">
                  <option selected disabled value="">Selecione</option>
                  <option>Junior</option>
                  <option>Pleno</option>
                  <option>Senior</option>
               </select>
          </div>

          <fieldset class="grupo">
              <div id="check">
                  <label><strong>Selecione as tecnologias que utiliza</strong></label><br><br>
                  <input type="checkbox" id="tecnologia1" nome="tecnologia1" value="HTML">
                  <label for="tecnologia1">HTML</label> 
                  <input type="checkbox" id="tecnologia2" nome="tecnologia2" value="CSS">
                  <label for="tecnologia2">CSS</label>
                  <input type="checkbox" id="tecnologia3" nome="tecnologia3" value="Javascript">
                  <label for="tecnologia3">Javascript</label>
                  <input type="checkbox" id="tecnologia4" nome="tecnologia4" value="PHP">
                  <label for="tecnologia4">PHP</label>
                  <input type="checkbox" id="tecnologia5" nome="tecnologia5" value="C#">
                  <label for="tecnologia5">C#</label>
                  <input type="checkbox" id="tecnologia6" nome="tecnologia6" value="Python">
                  <label for="tecnologia6">Python</label>
                  <input type="checkbox" id="tecnologia7" nome="tecnologia7" value="Java">
                  <label for="tecnologia7">Java</label>
              </div>
          </fieldset>

          <div class="campo">
              <br>
              <label><strong>Conte um pouco da sua experiência:</strong></label>
              <textarea rows="6" style="width: 26em" id="experiencia" nome="experiencia"></textarea>
          </div>
        
          <button class="botao" type="submit" onsubmit="">Concluído</button>
     </form>
  </body>

</html>
