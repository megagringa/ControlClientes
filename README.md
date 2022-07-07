# EjercicioJava

Ejercicios tema 3 armados en java de nievel inicial para un bootcamp.

Primera parte:
```
public class sumaTres{
	public static void suma(int a, int b, int c){
		int resultado = a + b + c;
		System.out.println("La suma de A , B y C es "+ resultado);
	}
	public static void main(String[] args) {
        	suma(20, 30, 40);
	}
}
```
Segunda parte:
```
public class miCoche{
	private int puertas;

	public miCoche(int puertas){
		this.puertas = puertas;
	}

	public void agregarPuertas(int puertas){
		this.puertas +=puertas;
	}

	public void muestra(){
		System.out.println("Puertas: " + puertas);
	}

	public static void main(String[] args){
		miCoche coche = new miCoche(4);
		coche.agregarPuertas(2);
		coche.muestra();
	}
}
```
