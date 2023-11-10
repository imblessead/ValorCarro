# ValorCarro
Valor do carro

// seja de 28%e os impostos de 45%  escrever um algoritmo para ler o custo de fabrica de um carro.
//calcular e escrever o custo final ao cosumidor

public class Exercicio10 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Custo do carro em fabricação : ");
		float valorAutomovel = sc.nextFloat();
		
		float distribuidor = valorAutomovel*28/100;
		float imposto = valorAutomovel*45/100;
		float custoFinal = valorAutomovel+distribuidor+imposto;
		
		System.out.println("O valor final do automovel corresponde a  : R$ " + custoFinal);
				
		
		sc.close();
	}

}
