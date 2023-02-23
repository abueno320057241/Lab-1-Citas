# Lab-1-Citas
Programa de Citas

#include <stdio.h>

int main(){
    
    int respuesta1, respuesta2, respuesta3, respuesta4, respuesta5, respuesta6, respuesta7, respuesta8, respuesta9, respuesta10, resultado;
    
    printf("Preguntas para conocer mejor a una persona:\n");
    printf("1. ¿Qué le gusta hacer en su tiempo libre?\n");
    printf("a. Jugar videojuegos\tb. Leer libros\tc. Ver películas\td. Escuchar música\n");
    scanf("%d", &respuesta1);
    
    printf("2. ¿Qué es lo que más le gusta comer?\n");
    printf("a. Pizza\tb. Sushi\tc. Hamburguesa\td. Comida mexicana\n");
    scanf("%d", &respuesta2);
    
    printf("3. ¿Cuál es su libro favorito?\n");
    printf("a. El Principito\tb. Harry Potter\tc. El Quijote\td. Cien años de soledad\n");
    scanf("%d", &respuesta3);
    
    printf("4. ¿Cuál es su comida favorita?\n");
    printf("a. Pizza\tb. Sushi\tc. Hamburguesa\td. Comida mexicana\n");
    scanf("%d", &respuesta4);
    
    printf("5. ¿Qué le gusta escuchar?\n");
    printf("a. Música clásica\tb. Rock\tc. Pop\td. Electrónica\n");
    scanf("%d", &respuesta5);
    
    printf("6. ¿Qué deporte le gusta jugar?\n");
    printf("a. Futbol\tb. Baloncesto\tc. Tenis\td. Voleyball\n");
    scanf("%d", &respuesta6);
    
    printf("7. ¿Qué país le gustaría visitar?\n");
    printf("a. España\tb. Estados Unidos\tc. Japón\td. México\n");
    scanf("%d", &respuesta7);
    
    printf("8. ¿Cuál es su color favorito?\n");
    printf("a. Negro\tb. Rojo\tc. Verde\td. Celeste\n");
    scanf("%d", &respuesta8);
    
    printf("9. ¿Qué tipo de música le gusta?\n");
    printf("a. Música clásica\tb. Rock\tc. Pop\td. Electrónica\n");
    scanf("%d", &respuesta9);
    
    printf("10. ¿Qué deporte le gusta ver?\n");
    printf("a. Futbol\tb. Baloncesto\tc. Tenis\td. Voleyball\n");
    scanf("%d", &respuesta10);
    
    resultado = respuesta1 + respuesta2 + respuesta3 + respuesta4 + respuesta5 + respuesta6 + respuesta7 + respuesta8 + respuesta9 + respuesta10;
    
    printf("Su total es: %d/10 puntos\n", resultado);
    
    return 0;
}
