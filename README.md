# prueba1
esta es una prueba de como usar git

solo dire que mi nombre es camilo zapata



const matriz = [[1,2,3],[4,5,6],[7,8,9]];
let acum=0;

for (var x=0;x<3;x++) {
  let aux=0;
    for (var y=0;y<3;y++) {
             aux+=matriz[x][y];
    }
     if(aux>acum){
     acum=aux;
      }
}



     console.log( acum);





const matriz = [[1,2,3],[4,5,6],[7,8,9]];
let acum=0;

for (var x=0;x<3;x++) {
  var aux=0;
  var row; 
    for (var y=0;y<3;y++) {
             aux+=matriz[x][y];
    }
     if(aux>acum){
     acum=aux;
     row=x;
      }
}



     console.log('la sumatoria de la fila mayor es : '+ acum);
     console.log('La fila mayor es la '+row)
