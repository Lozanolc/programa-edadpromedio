# Bienvenido a mi primer repositorio

Prueba de repositorio con el curso de Carlos Solis - Programa en Javascript para calcular promedio de edades

   <h1>Calcular la media de edades de una familia</h1>
    <script>

        function imprimir(frase){
            document.write(frase);
            saltoDeLinea();
        }

        var edadPadre = parseInt(prompt("ingrese la edad del Padre"));
        var edadMadre = parseInt(prompt("Ingrese la edad de la madre"));
        var edadHijo = parseInt(prompt("Ingrese edad del Hijo"));
        var edadHija = parseInt(prompt("Ingrese la edad de la hija"));
        var edadPromedio = Math.round((edadPadre + edadMadre + edadHijo + edadHija)/3);

        imprimir("La edad promedio de la familia es: "+edadPromedio);
   </script>

[visita mi canal de youtube](https://www.youtube.com/channel/UCMq7njaMeS5x-ML54KX8n0Q)
