//Line comparison program
import java.util.Scanner;

public class LineComparison {

	public static void main(String args[]) {
		
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("Enter co-ordinates for a line 1: ");
		System.out.println("Enter the value of x1 and y1:");
		int x1 = scanner.nextInt();
		int y1 = scanner.nextInt();
		
		System.out.println("Enter the value of x2 and y2");
		int x2 = scanner.nextInt();
		int y2 = scanner.nextInt();
		
		double dis1 = Math.sqrt((x2-x1)*(x2-x1) + (y2-y1)*(y2-y1));
		System.out.println("distance between"+"("+x1+","+y1+"),"+"("+x2+","+y2+") is : "+dis1);
		
		System.out.println("Enter co-ordinates for a line 2: ");
                System.out.println("Enter the value of x1 and y1:");
                int x3 = scanner.nextInt();
                int y3 = scanner.nextInt();

                System.out.println("Enter the value of x2 and y2");
                int x4 = scanner.nextInt();
                int y4 = scanner.nextInt();

                double dis2 = Math.sqrt((x4-x3)*(x4-x3) + (y4-y3)*(y4-y3));
                System.out.println("distance between"+"("+x1+","+y1+"),"+"("+x2+","+y2+") is : "+dis2);

		//(dis1.equals(dis2))
		if(length_line1.equals(length_line2)){
			System.out.println("Both line have same length of " + length_line1);
		}
		else{
			System.out.println("Both have different length");

		//(dis1.compare(dis2))
		int res = (int)dis1 - (int)dis2;
		
		//comparing line
		if(res < 0)
			System.out.println("Line 1 is smaller than Line 2.");
		else if(res > 0)
			System.out.println("Line 1 is greater than Line 2.");
		else
			System.out.println("Line 1 is equals to the Line 2.");
	}
}
