package JavaExceptions;

public class ArrayAndMathException {
    public static void main(String[] args) {
        int[] myArr = {1,2,3,4,5,6};
        try{
            myArr[9] = 5/0;
        }
        catch (ArithmeticException e){
            System.out.println("Division by zero");

        }
   catch (ArrayIndexOutOfBoundsException e){
            System.out.println("Array index exceeded");
        }
      System.out.println("SHOW MUST GO ON");
    }
}
