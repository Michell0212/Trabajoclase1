package com.mycompany.trabajoclase1;

public class Trabajoclase1 {
    
     public static void main (String [] args) {
      Persona p1= new Persona ("Keila", "Galeano", 27);
        p1.setId(1725415465);
        System.out.println(p1.getId());
        
    }
 }


package com.mycompany.trabajoclase1;
public class Persona {
    
    public String nombre;
    public String apellido;
    public int edad;
    private int id;
    
    
    public Persona (String nombre, String apellido, int edad){
        this.nombre = nombre;
        this.apellido = apellido;
        this.edad = edad;
        
    }
    
    public int getId () {
        return id;
        
        
    }
    
    public void setId (int id) {
        this.id = id;
    }
}



