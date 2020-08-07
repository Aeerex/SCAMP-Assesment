# SCAMP-Assesment
# SCAMP-Assesment
 public class fibonacciSequence {
     public staatic void main(string[] args){
         int count, num1=0, num2=1;
         System.out.println("How many will be in the sequence:");
         Scanner scanner = new Scanner(System.in);
         count = scanner.nextint();
         scanner.close();
        System.out.print("Fibonacci Series of "+count+" numbers:");

        int i=1;
        while(i<=count)
        {
            System.out.print(num1+" ");
            int sumOfPrevTwo = num1 + num2;
            num1 = num2;
            num2 = sumOfPrevTwo;
            i++;
        }
     }
 }
