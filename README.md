# Sum-Series-by-Java-

package ict.22.ClassNames;

public class SumClass {
    public static double sumSeries() {
        double sum = 0;
        for (double i = 1.0; i >= 0.1; i -= 0.1) {
            sum += i;
        }
        return sum;
    }
}
