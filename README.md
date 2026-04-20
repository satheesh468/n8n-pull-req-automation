public class Sample {

    public static String greetUser(String name) {
        return "Hello, " + name + "! Welcome to GitHub Pull Request demo.";
    }

    public static int addNumbers(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        System.out.println(greetUser("Satheesh"));
        int result = addNumbers(10, 20);
        System.out.println("Addition Result: " + result);
    }
}
