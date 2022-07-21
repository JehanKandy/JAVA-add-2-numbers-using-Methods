# JAVA-add-2-numbers-using-Methods
JAVA use java Methods for add 2 numbers 
<br><br>
<b>Code Explaine</b>

        //import Scanner for get user inputs
        import java.util.Scanner;

        //create class for Cal
        public class Cal{
            //create a method of get messages
            /*
            static void Msg(){
                //create a aboject in Scanner 
                Scanner Msgget = new Scanner(System.in);

                System.out.println("Enter First Number : ");
                int num = Msgget.nextInt();
                System.out.println("First Name is " + fname);              
            }*/

            public void cal_numbers(int num1, int num2){
                //num1 and num2 form user input numbers and the add all 2 numnbers
                System.out.println("Total is : "+ (num1 + num2));
            }



            public static void main(String[] args) {
                //now call the above created method
                //Msg();

                Cal calNum = new Cal();
                Scanner GetNumbers = new Scanner(System.in);

                //get first number and assign to getNum1
                System.out.println("Enter First Number : ");
                int getNum1 = GetNumbers.nextInt();

                //get Second Number and assign to getNum2
                System.out.println("Enter Second Number : ");
                int getNum2 = GetNumbers.nextInt();

                //Pass above got numbers to add each other
                calNum.cal_numbers(getNum1, getNum2);
            }
        }
