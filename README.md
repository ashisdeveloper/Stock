<!-- #######  YAY, I AM THE SOURCE EDITOR! #########-->
<p>Input And Output:</p>
<p>==================================================================================</p>
<p><strong>Program:</strong></p>
<p><strong>----------</strong></p>
<pre><code class='language-cs'>
namespace MyProject.Examples
{
    class ExampleOne
    {
        static void Main()
        {
            Console.Write("Enter 1st food name: ");
            string name1 = Console.ReadLine();
            int price1 = int.Parse(Console.ReadLine());
            Console.Write("Enter 2nd food name: ");
            string name2 = Console.ReadLine();
            int price2 = int.Parse(Console.ReadLine());
            int total = price1 + price2;
            Console.WriteLine("Total price of {0} and {1} is {2}",name1,name2,total);
            Console.Write("Total price of "+ name1 + " and "+name2+ " is "+total);
            Console.ReadKey();
        }
    }
}
</code></pre>
<p><strong>Output:</strong></p>
<p><strong>----------</strong></p>
<p>Enter 1st food name: Rice</p>
<p>20</p>
<p>Enter 2nd food name: Dal</p>
<p>30</p>
<p>Total price of Rice and Dal is 50</p>
<p>Total price of Rice and Dal is 50</p>
<p>&nbsp;</p>
<p>Data Types:</p>
<p>==================================================================================</p>
<table width="721">
<tbody>
<tr>
<td width="94">
<p><strong>Reserved Word</strong></p>
</td>
<td width="187">
<p><strong>Type</strong></p>
</td>
<td width="55">
<p><strong>Size (bits)</strong></p>
</td>
<td width="325">
<p><strong>Range (values)</strong></p>
</td>
<td width="60">
<p><strong>Default Value</strong></p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>byte</strong></p>
</td>
<td width="187">
<p>Unsigned integer</p>
</td>
<td width="55">
<p>8</p>
</td>
<td width="325">
<p>0 to 255</p>
</td>
<td width="60">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>sbyte</strong></p>
</td>
<td width="187">
<p>Signed integer</p>
</td>
<td width="55">
<p>8</p>
</td>
<td width="325">
<p>-128 to 127</p>
</td>
<td width="60">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>short</strong></p>
</td>
<td width="187">
<p>Signed integer</p>
</td>
<td width="55">
<p>16</p>
</td>
<td width="325">
<p>-32,768 to 32,767</p>
</td>
<td width="60">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>ushort</strong></p>
</td>
<td width="187">
<p>Unsigned integer</p>
</td>
<td width="55">
<p>16</p>
</td>
<td width="325">
<p>0 to 65,535</p>
</td>
<td width="60">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>int</strong></p>
</td>
<td width="187">
<p>Signed integer</p>
</td>
<td width="55">
<p>32</p>
</td>
<td width="325">
<p>-2,147,483,648 to 2,147,483,647</p>
</td>
<td width="60">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>uint</strong></p>
</td>
<td width="187">
<p>Unsigned integer</p>
</td>
<td width="55">
<p>32</p>
</td>
<td width="325">
<p>0 to 4294967295</p>
</td>
<td width="60">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>long</strong></p>
</td>
<td width="187">
<p>Signed integer</p>
</td>
<td width="55">
<p>64</p>
</td>
<td width="325">
<p>-9,223,372,036,854,775,808 to 9,223,372,036,854,775,807</p>
</td>
<td width="60">
<p>0L</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>ulong</strong></p>
</td>
<td width="187">
<p>Unsigned integer</p>
</td>
<td width="55">
<p>64</p>
</td>
<td width="325">
<p>0 to 18,446,744,073,709,551,615</p>
</td>
<td width="60">
<p>0L</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>float</strong></p>
</td>
<td width="187">
<p>Single-precision floating point type</p>
</td>
<td width="55">
<p>32</p>
</td>
<td width="325">
<p>-3.402823e38 to 3.402823e38</p>
</td>
<td width="60">
<p>0.0F</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>double</strong></p>
</td>
<td width="187">
<p>Double-precision floating point type</p>
</td>
<td width="55">
<p>64</p>
</td>
<td width="325">
<p>-1.79769313486232e308 to 1.79769313486232e308</p>
</td>
<td width="60">
<p>0.0D</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>decimal</strong></p>
</td>
<td width="187">
<p>128-bit precise decimal values with 28-29 significant digits</p>
</td>
<td width="55">
<p>128</p>
</td>
<td width="325">
<p>(+ or -)1.0 x 10e-28 to 7.9 x 10e28</p>
</td>
<td width="60">
<p>0.0M</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>char</strong></p>
</td>
<td width="187">
<p>A single Unicode character</p>
</td>
<td width="55">
<p>16</p>
</td>
<td width="325">
<p>Unicode symbols used in text</p>
</td>
<td width="60">
<p>'\0'</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>bool</strong></p>
</td>
<td width="187">
<p>Logical Boolean type</p>
</td>
<td width="55">
<p>8</p>
</td>
<td width="325">
<p>True or False</p>
</td>
<td width="60">
<p>FALSE</p>
</td>
</tr>
<tr>
<td width="94">
<p><strong>object</strong></p>
</td>
<td width="187">
<p>Base type of all other types</p>
</td>
<td width="55">&nbsp;</td>
<td width="325">&nbsp;</td>
<td width="60">&nbsp;</td>
</tr>
<tr>
<td width="94">
<p><strong>string</strong></p>
</td>
<td width="187">
<p>A sequence of characters</p>
</td>
<td width="55">&nbsp;</td>
<td width="325">&nbsp;</td>
<td width="60">&nbsp;</td>
</tr>
<tr>
<td width="94">
<p><strong>DateTime</strong></p>
</td>
<td width="187">
<p>Represents date and time</p>
</td>
<td width="55">&nbsp;</td>
<td width="325">
<p>0:00:00am 1/1/01 to 11:59:59pm 12/31/9999</p>
</td>
<td width="60">&nbsp;</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p><strong>Example:</strong></p>
<p>int num;</p>
<p>Console.Write("Min Range: "+ int.MinValue + "Max Range: " + int.MaxValue);</p>
<p>Output: Min Range: -2147483648Max Range: 2147483647</p>
<p>&nbsp;</p>
<p><strong>INITIALIZING VALUE TYPES</strong></p>
<p>&nbsp;</p>
<p>Local variables in C# must be initialized before they are used.</p>
<p>&nbsp;</p>
<p><strong>int myInt;&nbsp; </strong></p>
<p><span style="text-decoration: line-through;">You cannot use it before you initialize it.</span> You can initialize it using the following statement:</p>
<p>&nbsp;</p>
<p><strong>myInt = new int();</strong>&nbsp; // Invoke default constructor for int type.&nbsp;</p>
<p>&ndash;or&ndash;</p>
<p><strong>myInt = 0;</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // Assign an initial value, 0 in this example.&nbsp;</p>
<p>You can, of course, have the declaration and the initialization in the same statement as in the following examples:</p>
<p>&nbsp;</p>
<p>Using the new operator calls the default constructor of the specific type and assigns the default value to the variable. In the preceding example, the default constructor assigned the value 0 to myInt.</p>
<p>&nbsp;</p>
<p><strong>Character escape sequences:</strong></p>
<p>&nbsp;</p>
<p>\' &ndash; single quote, needed for character literals</p>
<p>\" &ndash; double quote, needed for string literals</p>
<p>\\ &ndash; backslash</p>
<p>\0 &ndash; Unicode character 0</p>
<p>\a &ndash; Alert (character 7)</p>
<p>\b &ndash; Backspace (character 8)</p>
<p>\f &ndash; Form feed (character 12)</p>
<p>\n &ndash; New line (character 10)</p>
<p>\r &ndash; Carriage return (character 13)</p>
<p>\t &ndash; Horizontal tab (character 9)</p>
<p>\v &ndash; Vertical quote (character 11)</p>
<p>&nbsp;</p>
<p><strong>Program:</strong></p>
<p><strong>---------------</strong></p>
<p>string name = "My name: \n \"Ashis \t Kumar\"";</p>
<p>Console.WriteLine(name);</p>
<p>&nbsp;</p>
<p>string path = "C:\\Users\\UX\\Downloads\\Video";</p>
<p>//OR Use Verbatim string literals - string path = @"C:\Users\UX\Downloads\Video";</p>
<p>Console.WriteLine(path);</p>
<p>&nbsp;</p>
<p>string str = @"My name: ""Ashis""";</p>
<p>//OR - string str = @"My name: "Ashis"";</p>
<p>Console.WriteLine(str);</p>
<p>&nbsp;</p>
<p><strong>Output:</strong></p>
<p><strong>---------------</strong></p>
<p>My name:</p>
<p>&nbsp;"Ashis&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Kumar"</p>
<p>C:\Users\UX\Downloads\Video</p>
<p>My name: "Ashis"</p>
<p>&nbsp;</p>
<p>Arithmetic Operators and Simple Calculator:</p>
<p>==================================================================================</p>
<p><strong>Arithmetic Operators:</strong>&nbsp;&nbsp;&nbsp; +&nbsp;&nbsp; -&nbsp;&nbsp; *&nbsp;&nbsp; /&nbsp;&nbsp; %&nbsp;&nbsp; ++&nbsp; --</p>
<p><strong>Relational Operators:</strong>&nbsp;&nbsp;&nbsp; ==&nbsp; !=&nbsp; &gt;&nbsp;&nbsp; &lt;&nbsp;&nbsp; &gt;=&nbsp; &lt;=&nbsp;</p>
<p><strong>Logical Operators:</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &amp;&amp;&nbsp; ||&nbsp; !</p>
<p><strong>Assignment Operators:</strong>&nbsp;&nbsp;&nbsp; =&nbsp;&nbsp; +=&nbsp; -=&nbsp; *=&nbsp; /=&nbsp; %=&nbsp;</p>
<p><strong>Misc Operators:</strong></p>
<table width="699">
<tbody>
<tr>
<td width="62">
<p>sizeof()</p>
</td>
<td width="316">
<p>Returns the size of a data type.</p>
</td>
<td width="321">
<p>sizeof(int), returns 4.</p>
</td>
</tr>
<tr>
<td width="62">
<p>typeof()</p>
</td>
<td width="316">
<p>Returns the type of a class.</p>
</td>
<td width="321">
<p>typeof(StreamReader);</p>
</td>
</tr>
<tr>
<td width="62">
<p>&amp;</p>
</td>
<td width="316">
<p>Returns the address of an variable.</p>
</td>
<td width="321">
<p>&amp;a; returns actual address of the variable.</p>
</td>
</tr>
<tr>
<td width="62">
<p>*</p>
</td>
<td width="316">
<p>Pointer to a variable.</p>
</td>
<td width="321">
<p>*a; creates pointer named 'a' to a variable.</p>
</td>
</tr>
<tr>
<td width="62">
<p>? :</p>
</td>
<td width="316">
<p>Conditional Expression</p>
</td>
<td width="321">
<p>If Condition is true ? Then value X : Otherwise value Y</p>
</td>
</tr>
<tr>
<td width="62">
<p>is</p>
</td>
<td width="316">
<p>Determines whether an object is of a certain type.</p>
</td>
<td width="321">
<p>If( Ford is Car) // checks if Ford is an object of the Car class.</p>
</td>
</tr>
<tr>
<td width="62">
<p>as</p>
</td>
<td width="316">
<p>Cast without raising an exception if the cast fails.</p>
</td>
<td width="321">
<p>Object obj = new StringReader("Hello");</p>
<p>StringReader r = obj as StringReader;</p>
</td>
</tr>
</tbody>
</table>
<p><strong>&nbsp;</strong></p>
<p><strong>Program:</strong></p>
<p>int num1, num2;</p>
<p>int add, sub, mul, rem;</p>
<p>float div;</p>
<p>&nbsp;</p>
<p>Console.Write("Enter 1st Number:\t");</p>
<p>num1 = Convert.ToInt32(Console.ReadLine());</p>
<p>&nbsp;</p>
<p>Console.Write("Enter 2nd Number:\t");</p>
<p>num2 = Convert.ToInt32(Console.ReadLine());</p>
<p>&nbsp;</p>
<p>add = num1 + num2;</p>
<p>sub = num1 - num2;</p>
<p>mul = num1 * num2;</p>
<p>div = (float)num1 / num2;</p>
<p>rem = num1 % num2;</p>
<p>&nbsp;</p>
<p>Console.WriteLine("Addition:\t{0}", add);</p>
<p>Console.WriteLine("Subtraction:\t{0}", sub);</p>
<p>Console.WriteLine("Multiplication:\t{0}", mul);</p>
<p>Console.WriteLine("Division:\t{0}", div);</p>
<p>Console.WriteLine("Remainder:\t{0}", rem);</p>
<p>&nbsp;</p>
<p><strong>Output:</strong></p>
<p>Enter 1st Number:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 13</p>
<p>Enter 2nd Number:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5</p>
<p>Addition:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 18</p>
<p>Subtraction:&nbsp;&nbsp; 8</p>
<p>Multiplication: 65</p>
<p>Division:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.6</p>
<p>Remainder:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3</p>
<p>&nbsp;</p>
<p>Array:</p>
<p>==================================================================================</p>
<p>Program:</p>
<p>int[] myIntArr = new int[2];</p>
<p>myIntArr[0] = 34;</p>
<p>myIntArr[1] = 12;</p>
<p>Console.WriteLine(myIntArr[1]);</p>
<p>&nbsp;</p>
<p>string[] myStrArr = new string[2];</p>
<p>myStrArr[0] = "24";</p>
<p>myStrArr[1] = "Ashis";</p>
<p>Console.WriteLine(myStrArr[1]);</p>
<p>&nbsp;</p>
<p>foreach(string x in myStrArr)</p>
<p>{</p>
<p>Console.WriteLine("Ex: " + x);</p>
<p>}</p>
<p>&nbsp;</p>
<p>Output:</p>
<p>12</p>
<p>Ashis</p>
<p>Ex: 24</p>
<p>Ex: Ashis</p>
<p>&nbsp;</p>
<p>Methods:</p>
<p>==================================================================================</p>
<p><strong>Program:</strong></p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int n1 = 12, n2 = 5;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ExampleOne obj = new ExampleOne();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Sum: " + obj.sum(n1, n2));</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public int sum(int num1, int num2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return num1 + num2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong></p>
<p>Sum: 17</p>
<p>&nbsp;</p>
<p><strong>Program:</strong></p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ExampleOne.sum(20,30);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static void sum(int num1, int num2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Sum: " + (num1 + num2));</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong></p>
<p>Sum: 50</p>
<p>&nbsp;</p>
<p><strong>Program (Static Example):</strong></p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int n1 = 50;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int n2 = 20;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine(ExampleOne.sum(n1, n2));</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static int sum(int num1, int num2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; num1 = 10; num2 = 20;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return num1 + num2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong></p>
<p>Sum: 30</p>
<p>&nbsp;</p>
<table>
<tbody>
<tr>
<td width="349">
<p><strong>Pass By Value</strong></p>
</td>
<td width="349">
<p><strong>Pass By Reference</strong></p>
</td>
</tr>
<tr>
<td width="349">
<p><strong>class</strong> <strong>ExampleOne</strong></p>
<p><strong>{</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp; </strong><strong>public</strong> <strong>static</strong> <strong>void</strong><strong> Main()</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp; {</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>int</strong><strong> n1 = 50;</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; myFunc(n1);</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>Console</strong><strong>.WriteLine(n1);</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>Console</strong><strong>.ReadKey();</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp; }</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp; </strong><strong>public</strong> <strong>static</strong> <strong>void</strong><strong> myFunc(</strong><strong>int</strong><strong> num1)</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp; {</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; num1 = 10;</strong></p>
<p><strong>&nbsp;&nbsp;&nbsp; }</strong></p>
<p><strong>}</strong></p>
</td>
<td width="349">
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int n1 = 50;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; myFunc(ref n1);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine(n1);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static void myFunc(ref int num1)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; num1 = 10;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
</tr>
<tr>
<td width="349">
<p><strong>Output: 50</strong></p>
</td>
<td width="349">
<p>Output: 10</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p><strong>Program: (Use of out for multiple return values)</strong></p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int n1 = 50, n2 = 10, sum = 0, mul = 0;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; myFunc(n1, n2, out sum, out mul);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Sum: {0} and Multiplication: {1}",sum,mul);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static void myFunc(int num1, int num2, out int sum, out int mul)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; sum = num1 + num2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; mul = num1 * num2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong> Sum: 60 and Multiplication: 500</p>
<p>&nbsp;</p>
<p><strong>Program: (Use of params)</strong></p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; string[] nameArr = new string[4];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; nameArr[0] = "Ashis";</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; nameArr[1] = "Kumar";</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; nameArr[2] = "Alok";</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;nameArr[3] = "Ranjan";</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // We can't write myFunc(); without passing the array But using "params" it is possible</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; myFunc(nameArr);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; myFunc("Hi", "Hello");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static void myFunc(params string[] strArr)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; foreach(string str in strArr)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine(str);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Array Length: {0}", strArr.Length);</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong></p>
<p>Ashis</p>
<p>Kumar</p>
<p>Alok</p>
<p>Ranjan</p>
<p>Array Length: 4</p>
<p>Hi</p>
<p>Hello</p>
<p>Array Length: 2</p>
<p>&nbsp;</p>
<p><strong>Conditions and uses of params: </strong></p>
<ol>
<li>Able to pass array elements in the method parameter</li>
<li>In the method we can only use 1 params.</li>
<li>public static void myFunc(int x, params string[] strArr) is possible. Because params can only use at last.</li>
</ol>
<p>&nbsp;</p>
<p>Method Overloading:</p>
<p>==================================================================================</p>
<p><strong>Program:</strong></p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Sum of two int: {0}", sum(20, 30));</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Sum of two double: {0}", sum(20.50, 30));</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Sum of two strings: {0}", sum("Ashis ", "Kumar"));</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static int sum(int n1, int n2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int add = n1 + n2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return add;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static double sum(double n1, double n2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; double add = n1 + n2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return add;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static string sum(string n1, string n2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; string add = n1 + n2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return add;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong></p>
<p>Sum of two int: 50</p>
<p>Sum of two double: 50.5</p>
<p>Sum of two strings: Ashis Kumar</p>
<p>&nbsp;</p>
<p>Classes and Objects:</p>
<p>==================================================================================</p>
<table>
<tbody>
<tr>
<td width="349">
<p>class Box</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public double l, b, h;</p>
<p>&nbsp;&nbsp;&nbsp; public double volume(double l,double b, double h)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return (l * b * h);</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{&nbsp;&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Box box1 = new Box();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box1.l = 20;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box1.b = 10;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box1.h = 5;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Volume of Box1: {0}", box1.volume(box1.l, box1.b, box1.h));</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Box box2 = new Box();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box2.l = 4;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box2.b = 5;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box2.h = 2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Volume of Box2: {0}", box2.volume(box2.l, box2.b, box2.h));</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
<td width="349">
<p>class Box</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public double l, b, h;</p>
<p>&nbsp;&nbsp;&nbsp; public double volume()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return (this.l * this.b * this.h);</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{&nbsp;&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Box box1 = new Box();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box1.l = 20;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box1.b = 10;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box1.h = 5;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Volume of Box1: {0}", box1.volume());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Box box2 = new Box();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box2.l = 4;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box2.b = 5;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; box2.h = 2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Volume of Box2: {0}", box2.volume());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
</tr>
<tr>
<td width="349">
<p><strong>Output:</strong></p>
<p>Volume of Box1: 1000</p>
<p>Volume of Box2: 40</p>
</td>
<td width="349">
<p><strong>Output:</strong></p>
<p>Volume of Box1: 1000</p>
<p>Volume of Box2: 40</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>Constructor and Destructor:</p>
<p>==================================================================================</p>
<ul>
<li>They are called automatically even we don&rsquo;t define them by ourselves</li>
<li>Must have same name as class name</li>
<li>Initialized automatically when an instance or object is created</li>
<li>It doesn&rsquo;t return any values</li>
<li>We can pass parameters</li>
<li>Mostly used to initialize the variables or values</li>
<li>Destructor is called when it reaches at out of scope of instance</li>
</ul>
<table>
<tbody>
<tr>
<td width="349">
<p><strong>Example: 1</strong></p>
</td>
<td width="349">
<p><strong>Example: 2</strong></p>
</td>
</tr>
<tr>
<td width="349">
<p>class Box</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public Box()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Constructor has initialized");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; ~Box(){</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Destructor has called");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{&nbsp;&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Box box1 = new Box();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
</td>
<td width="349">
<p>class Box</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public double l, b, h;</p>
<p>&nbsp;&nbsp;&nbsp; public double volume()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return (this.l * this.b * this.h);</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public Box(double le, double br, double hi)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this.l = le;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this.b = br;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this.h = hi;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{&nbsp;&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Box box1 = new Box(10,20,30);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Volume of Box1: {0}", box1.volume());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
</tr>
<tr>
<td width="349">
<p>Constructor has initialized</p>
<p>Destructor has called</p>
</td>
<td width="349">
<p><strong>Output:</strong></p>
<p><strong>Volume of Box1: 6000 </strong></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>Class Inheritance:</p>
<p>==================================================================================</p>
<p>&nbsp;</p>
<table>
<tbody>
<tr>
<td width="323">&nbsp;</td>
<td width="175">&nbsp;</td>
<td width="30">&nbsp;</td>
<td width="16">&nbsp;</td>
<td width="20">&nbsp;</td>
<td width="187">&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td colspan="4">&nbsp;</td>
<td rowspan="4">&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td colspan="2">&nbsp;</td>
<td rowspan="2">&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td rowspan="3">&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>&nbsp;</p>
<h1 style="color: #5e9ca0;">&nbsp;</h1>
<p>&nbsp;</p>
<p>&nbsp;</p>
<ul>
<li>We can&rsquo;t inherit 2 base classes at the same time (Only one is allowed) but we can indirectly inherit to the base class. Just like</li>
</ul>
<table>
<tbody>
<tr>
<td width="349">
<p>class Polygon{}</p>
<p>class Cls1 : Polygon {}</p>
<p>class Cls2 : Polygon, Cls1 {}</p>
</td>
<td width="349">
<p>class Polygon{}</p>
<p>class Cls1 : Polygon {}</p>
<p>class Cls2 : Cls1 {}</p>
</td>
</tr>
<tr>
<td width="349">
<p>Wrong</p>
</td>
<td width="349">
<p>In this way Cls2 can access the class Polygon</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<ul>
<li>When we create an instance of child class then it automatically creates the instance of the base class.</li>
</ul>
<p><strong>&nbsp;</strong></p>
<p><strong>Program:</strong></p>
<p>class Polygon</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public double height, width;</p>
<p>&nbsp;&nbsp;&nbsp; public void setValues(double h, double w)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this.height = h;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this.width = w;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Rectangle : Polygon</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public double area()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this.height * this.width;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Triangle : Polygon</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public double area()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this.height * this.width /2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Rectangle rect = new Rectangle();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Triangle tri = new Triangle();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rect.setValues(20, 30);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; tri.setValues(20, 30);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Area of Rectangle: {0}", rect.area());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Area of Triangle: {0}", tri.area());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong></p>
<p>Area of Rectangle: 600</p>
<p>Area of Triangle: 300</p>
<p>&nbsp;</p>
<p>Method Hiding:</p>
<p>==================================================================================</p>
<table>
<tbody>
<tr>
<td width="232">
<p><strong>Method: 1</strong></p>
</td>
<td width="232">
<p><strong>Method: 2</strong></p>
</td>
<td width="232">
<p><strong>Method: 3</strong></p>
</td>
</tr>
<tr>
<td width="232">
<p>class Fc</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public void display()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is Fc Class");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Sc : Fc</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public new void display()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is Sc Class");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Sc obj = new Sc();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.display();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
<td width="232">
<p>class Fc</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public void display()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is Fc Class");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Sc : Fc</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public new void display()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is Sc Class");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Sc obj = new Sc();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ((Fc)obj).display();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
<td width="232">
<p>class Fc</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public void display()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is Fc Class");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Sc : Fc</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public new void display()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is Sc Class");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Fc obj = new Sc();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.display();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
</tr>
<tr>
<td width="232">
<p><strong>Note:</strong> Without using &lsquo;new&rsquo; it will show the output but with a warning for method hiding.</p>
</td>
<td width="232">
<p><strong>Note:</strong> Without using &lsquo;new&rsquo; it will show the output but with a warning for method hiding.</p>
</td>
<td width="232">
<p><strong>Note:</strong> Without using &lsquo;new&rsquo; it will show the output but with a warning for method hiding.</p>
</td>
</tr>
<tr>
<td width="232">
<p><strong>Output:</strong> This is Fc Class</p>
</td>
<td width="232">
<p><strong>Output:</strong> This is Fc Class</p>
</td>
<td width="232">
<p><strong>Output:</strong> This is Fc Class</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>Polymorphism:</p>
<p>==================================================================================</p>
<p><strong>Program:</strong></p>
<p>public class Drawing</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public virtual void Draw()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is just a generic drawing object");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Circle : Drawing</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public override void Draw()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is a Circle");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Square : Drawing</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public override void Draw()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is a Square");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Line : Drawing</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public override void Draw()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is a Line");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Drawing[] obj = new Drawing[4];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj[0] = new Circle();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj[1] = new Line();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj[2] = new Square();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj[3] = new Drawing();</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; foreach(Drawing draw in obj)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; draw.Draw();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p><strong>Output:</strong></p>
<p>This is a Circle</p>
<p>This is a Line</p>
<p>This is a Square</p>
<p>This is just a generic drawing object</p>
<p>&nbsp;</p>
<p>Difference between Method Overriding and Method Hiding:</p>
<p>==================================================================================</p>
<table>
<tbody>
<tr>
<td width="349">
<p>Method Overriding</p>
</td>
<td width="349">
<p>Method Hiding</p>
</td>
</tr>
<tr>
<td width="349">
<p>public class Drawing</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public virtual void Draw()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is just a generic drawing object");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Circle : Drawing</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public override void Draw()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is a Circle");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Drawing obj = new Circle();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.Draw();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
<td width="349">
<p>public class Drawing</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public void Draw()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is just a generic drawing object");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class Circle : Drawing</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public new void Draw()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("This is a Circle");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Drawing obj = new Circle();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.Draw();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
</tr>
<tr>
<td width="349">
<p><strong>Output:</strong> This is a Circle</p>
</td>
<td width="349">
<p><strong>Output:</strong> This is just a generic drawing object</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>Getter and Setter:</p>
<p>==================================================================================</p>
<p><strong>Program:</strong></p>
<p>public class Book</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; private int _bookId;</p>
<p>&nbsp;&nbsp;&nbsp; private string _bookName;</p>
<p>&nbsp;&nbsp;&nbsp; private int _noOfPages = 250;</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; public void SetBookId(int id)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if(id &lt; 0)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; //Console.WriteLine("Book ID can't be a negative value");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; throw new Exception("Book ID can't be a negative value");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this._bookId = id;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public int GetBookId()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this._bookId;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public void SetBookName(string bookname)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (string.IsNullOrEmpty(bookname))</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book name can't be empty");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this._bookName = bookname;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public string GetBookName()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this._bookName;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public int GetNoOfPages()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this._noOfPages;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Book obj = new Book();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.SetBookId(10);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.SetBookName("C#");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book ID: {0}", obj.GetBookId());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book Name: {0}", obj.GetBookName());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book Name: {0}", obj.GetNoOfPages());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p><strong>Output:</strong></p>
<p>Book ID: 10</p>
<p>Book Name: C#</p>
<p>Book Name: 250</p>
<p>&nbsp;</p>
<p>Properties in C#:</p>
<p>==================================================================================</p>
<p><strong>Program:</strong></p>
<p>public class Book</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; private int _bookId;</p>
<p>&nbsp;&nbsp;&nbsp; private string _bookName;</p>
<p>&nbsp;&nbsp;&nbsp; private int _noOfPages = 250;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; public int bookid</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; set</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (value &lt; 0)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; //Console.WriteLine("Book ID can't be a negative value");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; throw new Exception("Book ID can't be a negative value");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this._bookId = value;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; get</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return this._bookId;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public string bookname</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; set</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (string.IsNullOrEmpty(value))</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book name can't be empty");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this._bookName = value;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; get</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this._bookName;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public int noofpages</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; get</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this._noOfPages;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Book obj = new Book();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.bookid = 10;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.bookname = "The C# Book";</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book ID: {0}", obj.bookid);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book Name: {0}", obj.bookname);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book Name: {0}", obj.noofpages);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>Output:</p>
<p>Book ID: 10</p>
<p>Book Name: The C# Book</p>
<p>Book Name: 250</p>
<p>&nbsp;</p>
<table>
<tbody>
<tr>
<td width="232">
<p><strong>Program: 1</strong></p>
</td>
<td width="232">
<p><strong>Program: 2</strong></p>
</td>
<td width="232">
<p><strong>Program: 3</strong></p>
</td>
</tr>
<tr>
<td width="232">
<p>public class Book</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; private string _author;</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; public string author</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; set</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this._author = value;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; get</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this._author;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Book obj = new Book();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.author = "Ashis Kumar";</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book Author: {0}", obj.author);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
<td width="232">
<p>public class Book</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; private string _author;</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; public void SetAuthor(string author)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; this._author = author;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public string GetAuthor()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return this._author;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Book obj = new Book();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.SetAuthor("Ashis Kumar");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book Author: {0}", obj.GetAuthor());</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp; &nbsp;}</p>
<p>}</p>
</td>
<td width="232">
<p>public class Book</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public string Author { set; get; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Book obj = new Book();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.Author = "Ashis Kumar";</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Book Author: {0}", obj.Author);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
</td>
</tr>
<tr>
<td width="232">
<p><strong>Output:</strong> Book Author: Ashis Kumar</p>
</td>
<td width="232">
<p><strong>Output:</strong> Book Author: Ashis Kumar</p>
</td>
<td width="232">
<p><strong>Output:</strong> Book Author: Ashis Kumar</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>Interfaces:</p>
<p>==================================================================================</p>
<ul>
<li>An interface is like an abstract base class <strong>with only abstract members</strong>. Any class or struct that implements the interface must <strong>implement all its members</strong>.</li>
<li>An interface <strong>can't be instantiated directly</strong>. Its members are <strong>implemented by any class</strong> or struct that implements the interface.</li>
<li>Interfaces can contain events, indexers, methods, and properties.</li>
<li>Interfaces contain <strong>no implementation of methods</strong>. Means Interfaces can&rsquo;t contain fields. Interface methods can&rsquo;t have a definition.</li>
<li>By default interface members are public. So don&rsquo;t add public in interface methods. But we must add public when we implement the interface within a class.</li>
<li>A <strong>class or struct can implement multiple interfaces</strong>. A <strong>class can inherit a base class</strong> and also <strong>implement one or more interfaces</strong>.</li>
</ul>
<p>&nbsp;</p>
<p><strong>Program:</strong></p>
<p>interface IText1</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; // We can't initialize a member method with access modifiers.</p>
<p>&nbsp;&nbsp;&nbsp; // By default, interface members are public.</p>
<p>&nbsp;&nbsp;&nbsp; // Interface member cannot have definition.</p>
<p>&nbsp;&nbsp;&nbsp; // Interface just contain the prototypes of method.</p>
<p>&nbsp;&nbsp;&nbsp; void print1();</p>
<p>}</p>
<p>interface IText2</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; void print2();</p>
<p>}</p>
<p>// Class can inherit multiple interfaces at a time.</p>
<p>// We can't inherit multiple base classes at a time.</p>
<p>class Text : IText1, IText2</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; // Must add public to access the interface member</p>
<p>&nbsp;&nbsp;&nbsp; public void print1()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Hello World!&nbsp; - 1");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public void print2()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Hello World!&nbsp; - 2");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Text obj = new Text();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.print1();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.print2();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>OR</p>
<p>====</p>
<p>interface IText1</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; void print1();</p>
<p>}</p>
<p>interface IText2</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; void print2();</p>
<p>}</p>
<p>class Text : IText1, IText2</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public void print1()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Hello World!&nbsp; - 1");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public void print2()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Hello World!&nbsp; - 2");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; IText1 obj1 = new Text();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj1.print1();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; IText2 obj2 = new Text();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj2.print2();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p><strong>Output:</strong></p>
<p>Hello World!&nbsp; - 1</p>
<p>Hello World!&nbsp; - 2</p>
<p>&nbsp;</p>
<p>Abstract classes:</p>
<p>==================================================================================</p>
<p>Sometimes we only make classes that represents base classes and we don&rsquo;t want anyone to create objects of these classes. So, we need to make these classes using &ldquo;abstract&rdquo;. Abstract class means no object of this class can be instantiated or created. But they can be used as base classes. So, we can derive from these classes, but they can&rsquo;t use as normal classes.</p>
<p>&nbsp;</p>
<p><strong>Program:</strong></p>
<p>&nbsp;</p>
<p>// abstract class can't be 'sealed' class</p>
<p>// 'sealed' class means the class can't be use as a base class</p>
<p>// 'sealed' class example: public sealed class PrintText{ }</p>
<p>// class can't use 'abstract' and 'sealed' at a time</p>
<p>public abstract class PrintText</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; // We can't provide defination to an abstract method</p>
<p>&nbsp;&nbsp;&nbsp; // It is not neccessary that an abstract class contain an abstract method</p>
<p>&nbsp;&nbsp;&nbsp; // abstract memebrs can't be "private"</p>
<p>&nbsp;&nbsp;&nbsp; // abstract method can't be marked as "virtual / static" keyword</p>
<p>&nbsp;&nbsp;&nbsp; public abstract void print1();</p>
<p>&nbsp;&nbsp;&nbsp; // Abstract class can contain normal methods</p>
<p>&nbsp;&nbsp;&nbsp; public void print2()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Print 2");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>class ExampleOne : PrintText</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public override void print1()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Print 1");</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ExampleOne obj = new ExampleOne();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.print1();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; obj.print2();</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p>Output:</p>
<p>Print 1</p>
<p>Print 2</p>
<p>&nbsp;</p>
<p>Abstract Class versus Interface:</p>
<p>==================================================================================</p>
<p>Delegates:</p>
<p>==================================================================================</p>
<p>Delegate is a type which holds the method(s) reference in an object.</p>
<p>It is also referred to as a type safe function pointer.</p>
<p>Generally delegate is used for multiple use of methods.</p>
<p>&nbsp;</p>
<p><strong>Program 1:</strong></p>
<p>public delegate int addNosDelegate(int num1, int num2);</p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; // Object reference is not required for static methods</p>
<p>&nbsp;&nbsp;&nbsp; public static int addNos(int n1, int n2) {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return n1 + n2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; addNosDelegate obj = new addNosDelegate(addNos);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int result = obj(50, 40);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine(result);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong></p>
<p>90</p>
<p>&nbsp;</p>
<p><strong>Program 2:</strong></p>
<p>class ExampleOne</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; public static int addNos(int n1, int n2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return n1 + n2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static int subNos(int n1, int n2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return n1 - n2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static int multNos(int n1, int n2)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; return n1 * n2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; public static void Main()</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int num1 = 10;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int num2 = 5;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; oprationDelegate obj1 = new oprationDelegate(addNos);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Addition: " + obj1(num1, num2));</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; oprationDelegate obj2 = new oprationDelegate(subNos);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Substraction: " + obj2(num1, num2));</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; oprationDelegate obj3 = new oprationDelegate(multNos);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.WriteLine("Multiplication: " + obj3(num1, num2));</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Console.ReadKey();</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p><strong>Output:</strong></p>
<p>Addition: 15</p>
<p>Substraction: 5</p>
<p>Multiplication: 50</p>
<p>&nbsp;</p>
<p>xyz:</p>
