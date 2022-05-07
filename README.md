# Ex05-Rec-JaggedArray
## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.
## Algorithm:
### Step 1:
Start the C# program in visual studio 2022.
### Step 2:
Declare a Jagged Array for four element.
### Step 3:
Initialize the elements.

### Step 4:
Accessing the elements.


### Step 5:
Finish the program and Run the prgram
### Step 6:
Take the screenshot of the output of the program. 


## Program:
```
using System;
class CPUactivity
{
    public static void Main(String[] args)
    {
        int[][] array = new int[4][];
        array[0] = new int[3];
        array[1] = new int[5];
        array[2] = new int[6];
        array[3] = new int[4];
        for(int i=0; i<4; i++)
        {
            for(int j=0; j<array[i].Length; j++)
            {
                array[i][j] = i*j+70;
            }
        }
        for(int i=0; i<array.Length; i++)
        {
            for(int j=0;j<array[i].Length; j++)
            {
                Console.WriteLine("CPU usage at node"+ i +" is "+ array[i][j]+"%");
            }
            Console.WriteLine();
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/94164665/167243061-2ba23e79-d9da-4ae0-8135-887cb776cf91.png)

## Result:
Thus, the C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.
