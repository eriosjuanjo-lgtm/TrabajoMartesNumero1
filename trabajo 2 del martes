package estudiantes;

public class Estudiantes {

    private String nombre;
    private double nota;

    public Estudiantes(String nombre, double nota) {
        this.nombre = nombre;
        this.nota = nota;
    }

    public void mostrarResultado() {
        if (nota >= 3) {
            System.out.println(nombre + " aprobó con nota " + nota);
        } else {
            System.out.println(nombre + " reprobó con nota " + nota);
        }
    }
}

------------------------------------------------------------------------------------------------------------------------

public class cuentabancaria {

    public class Cuentabancaria {

    private String titular;
    private double saldo;

    public Cuentabancaria(String titular, double saldoInicial) {
        this.titular = titular;
        this.saldo = saldoInicial;
    }

    public void depositar(double cantidad) {
        saldo += cantidad;
    }

    public void retirar(double cantidad) {
        if (cantidad <= saldo) {
            saldo -= cantidad;
        } else {
            System.out.println("Saldo insuficiente");
        }
    }

    public double getSaldo() {
        return saldo;
    }

    public String getTitular() {
        return titular;
    }
}

}

--------------------------------------------------------------------------------------------------------

public class libro {

    private String titulo;
    private String autor;
    private int paginas;

    public libro(String titulo, String autor, int paginas) {
        this.titulo = titulo;
        this.autor = autor;
        this.paginas = paginas;
    }

    public String getTitulo() {
        return titulo;
    }

    public String getAutor() {
        return autor;
    }

    public int getPaginas() {
        return paginas;
    }

    public void mostrarInformacion() {
        System.out.println("Titulo: " + titulo);
        System.out.println("Autor: " + autor);
        System.out.println("Paginas: " + paginas);
    }
}

---------------------------------------------------------------------------------------------------------------------

public class Main {

    public static void main(String[] args) {

        libro libro = new libro("Java Básico", "Carlos López", 250);
        libro.mostrarInformacion();

        Cuentabancaria cuenta = new Cuentabancaria("Ana", 1000);
        cuenta.depositar(500);
        cuenta.retirar(200);

        System.out.println("Saldo actual: " + cuenta.GetSaldo());

        estudiante estudiante = new estudiantes("Pedro", 4.2);
        estudiante.mostrarResultado();

    }
}

