package escola;


public class Aluno {
    String nome;
    int matricula;
    float serie;
    String materia;
    boolean aprovado;
    
    void status (){
        System.out.println("Nome " + this.nome);
        System.out.println("matricula "+this.matricula);
        System.out.println("esta cursando o " + this.serie);
        System.out.println("O aluno foi aprovado? "+this.aprovado);
    }
   
    void aprovado(){
        if(this.aprovado == true){
            System.out.println("O aluno foi aprovado");
        }else{
            System.out.println("O aluno foi reprovado");
        }
    }
    void aprovacao(){
        this.aprovado = true;
    }
    void reprovacao(){
        this.aprovado = false;
    }
    
}
