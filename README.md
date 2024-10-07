#include <stdio.h>

int main() {
	// DeclaraC'C#o de variC!veis
	int numero, antecessor, sucessor, contador, resultado, a, b, c;

	// Entrada de dados: o usuC!rio digita um nC:mero
	printf("Digite o numero que deseja saber o sucessor e antecessor: ");
	scanf("%d", &numero);

	// CC!lculo do antecessor e sucessor
	antecessor = numero - 1;
	sucessor = numero + 1;

	// Exibe o nC:mero digitado, seu antecessor e sucessor
	printf("Numero digitado: %d\n", numero);
	printf("Seu antecessor: %d\n", antecessor);
	printf("Seu sucessor: %d\n", sucessor);

	// Exibe a tabuada de multiplicaC'C#o do nC:mero
	printf("Tabuada de Multiplicacao de %d\n", numero);
	contador = 1;
	resultado = numero * contador;

	// Calcula e exibe a tabuada atC) o nC:mero 10
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);
	contador++;
	resultado = numero * contador;
	printf("%d X %d: %d\n", numero, contador, resultado);

	// Calcula e exibe os trC*s prC3ximos nC:meros contados de 2 em 2
	printf("3 proximos numeros contado de 2 em 2\n");
	a = numero + 2;
	b = a + 2;
	c = b + 2;
	printf("%d - %d - %d\n", a, b, c);

	return 0;
}
