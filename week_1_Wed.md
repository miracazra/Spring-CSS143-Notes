# Writing code 

'''java


public class Main {
    public static void main(String[] args) {
        float initDeposit = 100;
        float interestRate = 10;
        int numberOfYears = 20;
        float monthlyDeposit = 0;

        float total = initDeposit;

        for (int i = 0; i < numberOfYears; i++) {
            total = total + total* interestRate/100 + monthlyDeposit*12;
        }

        System.out.printf("after second year:" + total + "\n");
    }
}

'''
