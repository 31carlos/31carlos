package test2.DTO;

public class Vehiculo {
    private String Marca;
    private  String Modelo;
    private  String Patente;
    private int CantidadRuedas;

   
    public Vehiculo(){
        this.Marca = "Chevrolet";
        this.Modelo = "Camaro";
        this.Patente = "Sin Patente";
        this.CantidadRuedas = 4;
       
    }
    public String getMarca(){
        return this.Marca;
        }
    public String getModelo(){
        return this.Modelo;
    }
    public String getPatente(){
        return this.Patente;
    }
    public int getCantidadRuedas(){
        return this.CantidadRuedas;
    }
   
    public void setMarca(String Marca){
        this.Marca = Marca;
       
    }
    public void setModelo(String Modelo){
        this.Modelo = Modelo;
    }
    public void setPatente(String Patente){
        this.Patente = Patente;
     
    }
   public void setCantidadRuedas(int CantidadRuedas){
       this.CantidadRuedas = CantidadRuedas;
   }
   
}

