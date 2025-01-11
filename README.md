public class OddNumberCounter {
    public static void main(String[] args) {
        int count = 0;

        for (int i = 1; i <= 100; i++) {
            if (i % 2 != 0) { // Check if the number is odd
                count++;
            }
        }

        System.out.println("The total number of odd numbers from 1 to 100 is: " + count);
    }
}
output
The total number of odd numbers from 1 to 100 is: 50.
