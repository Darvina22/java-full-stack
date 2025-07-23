# java-full-stack
abstract class Animal {
    abstract void varities();
}
class Dogs extends Animal {
    void varities() {
        System.out.println("They are more varities in Dogs");
    }
}
public class Main {
    public static void main(String[] args) {
        Animal a = new Dogs(); 
        a.varities(); 
    }
}
