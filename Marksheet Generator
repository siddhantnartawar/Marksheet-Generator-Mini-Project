import java.util.Scanner;
class MarksheetGenerator 
{
	public static void main(String[] args) 
	{
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Enter Student's Name : ");
		String name = sc.nextLine();
		
		System.out.println("Enter Roll No : ");
		int rollno =  sc.nextInt();
		
		System.out.println("Enter Marks of 5 Subjects : ");
		System.out.print("English : ");
		float sub1 = sc.nextFloat();
		
		System.out.print("Marathi : ");
		float sub2 = sc.nextFloat();
		
		System.out.print("Hindi : ");
		float sub3 = sc.nextFloat();
		
		System.out.print("Maths : ");
		float sub4 = sc.nextFloat();
		
		System.out.print("Science : ");
		float sub5 = sc.nextInt();
		
		float totalMarks = sub1+sub2+sub3+sub4+sub5;
		
		if (totalMarks > 500)
		{
			System.out.println("Enter Valid Marks, try Again");
		}
		else
		{
				
			float percentage = totalMarks/5;
		
			System.out.println("Total Marks of " + name + " = " + totalMarks);
			System.out.println("Percentage = "+percentage);
		
			if (isPrime(percentage))
			{
				System.out.println("Percentage is prime");
			}
			else
				System.out.println("Percentage is not prime");
		
			if (percentage>80)
			{
				System.out.println("Result = Grade A");
			}
			else if (percentage<=80 && percentage>60)
			{
				System.out.println("Result = Grade B");
			}
			else if (percentage<=60 && percentage>40)
			{
				System.out.println("Result = Grade C");
			}
			else
				System.out.println("Result = Fail");
		}
	}
	
	public static boolean isPrime(float num)
	{
		for (int i=2;i<=num/2 ;i++ )
		{
			if (num%i==0)
			{
				return false;
			}
		}
		return true;
	}
}
