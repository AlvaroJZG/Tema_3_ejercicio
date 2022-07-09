# Tema_3_ejercicio
Ejercicio del tema 3 de el curso de introducción a la programación de Open Boodcamp

public class tematres {
    public static void main(String [] arg) {
        int resultado_s;
        resultado_s = suma(10, 20, 30);
        System.out.println(resultado_s);
        //Objeto
        coche micoche = new coche();
        micoche.incremento();
        System.out.println("Mi coche tiene " + micoche.puertas + " puerta(s)");
    }
    //suma
    public static int suma(int a, int b , int c) { return a + b + c; }
}
//class
class coche {
    //propiedades
    int puertas = 0;
    //metodo
    public void incremento(){ this.puertas++; }
}
