# Java-OOP-
OOP Java

package oopjava;
class Main {
    
    public static void main(String[] args) {
        //Hacker: came and changed \/
        //System.out.println("Hello, World!");
        //too, OOP!, with private variables and functions
        hello();
    }
    
    private static void hello() {
        System.out.println(Data.Hacked);
        System.out.print(Data.A);
    }
    
    private static class Data { // globle Main variables
        private static int A = 1; 
        private static String Hacked = "Hello, Earth!";
    }
    
}
