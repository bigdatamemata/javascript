# javascript
como inicializar un objeto:
  var mi objeto ={};
  //también se puede
  var miOtroObjeto = new Objeto();
  var a = new Array();
  var punto = {x:0, y:o};
  var punto2 = {x:point.x,y:point.y+1};
  var book = {
    "Titulo proncipal": "El jinete pálido",
    'Sub Titulo': "Gran película",
    "para": "todo publico",
    author: {
      firstname:"Cleat",
      surname:"Eastwood"
    }
    guardar:function(){
    },
   };
   
   //Añadir propiedad
   miObjeto.nombre = 'SuperObjeto';
   console.log(miObjeto.nombre); //SuperObjeto
   miObjeto["apellido"]="SuperLopez;
   console.log(miObjeto.apellido);//SuperLopez
   
