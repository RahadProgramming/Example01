# Example01
package JavaArray;

public class Example01 
{
	public static void main(String[] args)
	{
		int i,j;
		
		for(i = 0;i < 10;i++)
		{
			for(j = 0;j < 10;j++)
			{
				if(i == 0 || i == 9)
				{
					System.out.print("* ");
				}
				else
				{
					if(j == 2 || j == 7)
					{
						System.out.print("  ");
					}
					else
					{
						if(i == 8 && (j == 3 || j == 4 || j == 5 || j == 6))
						{
							System.out.print("  ");
						}
						else
						{
							System.out.print("* ");
						}
					}
				}
			}
			System.out.println();
		}
	}
}
