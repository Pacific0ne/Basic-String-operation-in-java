# Basic-String-operation-in-java
import java.io.*;
class Rectangle
{
	int length,width,p;
	Rectangle(int l, int b)
	{
		length=l;
		width=b;
		p=2*(l+b);
	}
	void show()
	{
		System.out.print("\n length = " +length+ ", width=" +width);
		System.out.print("\n Area=" + length*width);
		System.out.print("\n Perimeter=" +p);
	}
}
class Geometry
{
	public static void main(String args[])throws IOException
 {
 	InputStreamReader obj= new InputStreamReader(System.in);
 	BufferedReader in= new BufferedReader(obj);
 	System.out.print("\n enter dimension of Rectangle :");
 	int a= Integer.parseInt(in.readLine());
 	int b=Integer.parseInt(in.readLine());
 //	Rectangle obj1=new Rectangle( );
 //	obj1.show();
 	Rectangle obj2=new Rectangle(a,b);
 	obj2.show();
	}
}
