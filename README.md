//# HelloWorld
//just wanna see this work


public class Hello {
	
	public Hello() {
		
	}
	
	public void sayIt() {
		//System.out.println("Hello World!!");
		System.out.println("What up, bitches!");
	}

}

////////////////////////////////////////

public class HelloTester {
	public static void main(String []args)
	{
		Hello hi = new Hello();
		hi.sayIt();
	}
}
