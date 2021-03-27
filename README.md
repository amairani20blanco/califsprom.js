# califsprom.js
<script>
let calificaciones = [10,9,8,7,6,8,7,9,10,8];
let suma=0;
  for(let i=0;i<10;i++){
  suma+=calificaciones[i];

}
let promedio=suma/10;
document.write("<br>"+ "El promedio es " + promedio +"<br>");
document.write("Calificaciones mayores al promedio ")
  for(let cal=0;cal<=9;cal++){ 
if(calificaciones[cal]>promedio)
document.write( calificaciones[cal]+" ");}
</script>
