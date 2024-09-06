import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    String s="";
	    String st="0123456789abcde";
	    int f=0,t=1;
	    for(;n>0;)
	    {
	        s=st.charAt((n%16))+s;
	        n/=16;
	    }
		System.out.println(s);
	}
}
