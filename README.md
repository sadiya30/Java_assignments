# java
public class fibbonacci
{
	public static void main(String[] args) {
	int start=1;
	int previous=0;
	int follow=0;
	System.out.print(previous+"\t");
   while(follow<50)
	{
	   
	 follow=previous+start;
	System.out.print(follow+"\t");
	 start=previous;
	previous=follow;
	}
	}
}
