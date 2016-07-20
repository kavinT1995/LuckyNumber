# LuckyNumber
import java.util.ArrayList;
import java.util.Scanner;


public class Lucky {

	
	public static void main(String[] args) {
		int a[]=new int[3];
		Scanner sr=new Scanner(System.in);
		for(int i=0;i<a.length;i++){
			int b=sr.nextInt();
			
			a[i]=b;
		}
		int c=0;
			if(a[0]==13){
				 c=a[1]+a[2];
			
		}
			if(a[1]==13){
				c=a[0]+a[2]; 
			}
			if(a[2]==13){
				c=a[0]+a[1];
			}
			System.out.println(c);
	}

}
