# Recursion-
public static void main(String[] args) {

Scanner sc=new Scanner(System.in);

int num;

System.out.println("Enter a number;");

num=sc.nextInt();

long factorial=multiplyNumbers(num);

System.out.println("Factorial of"+num+"="+factorial);

}

public static long multiplyNumbers(int num){

if(num>=1)

{

return num*multiplyNumbers(num-1);

}

else

return 1;

}

}

OUTPUT

Enter a number;

9

Factorial of 9=362880
