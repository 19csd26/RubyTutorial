# Ruby variables
Ruby variables are locations which hold data to be used in the programs. Each variable has a different name. These variable names are based on some naming conventions. Unlike other programming languages, there is no need to declare a variable in Ruby. A prefix is needed to indicate it.

## There are four types of variables in Ruby:

  1.Local variables
  2.Class variables
  3.Instance variables
  4.Global variables

<p align="center">
  <img src="ruby-variables.png" alt="Image" >
</p>

<p align="center">
  <img src="VAR.png" alt="Image" width="70%">
</p>


# 1.Local Variables:

+ Local variables are confined to the scope in which they are defined, such as a method or block.
+ They start with a lowercase letter or an underscore (_) character.<br/>
+ Example : `name = "John"`

# 2.Instance Variables:

+ Instance variables are associated with a particular instance of a class.
+ They start with the @ symbol followed by a name.
+ Instance variables are accessible within the instance's methods.
+ Example : `@age = 30`

# 3.Class Variables:

+ Class variables are shared among all instances of a class.
+ They start with the @@ symbol followed by a name.
+ Class variables are accessible within the class and its subclasses.
+ Example : `@@counter = 0`

# 4.Global Variables:

+ Global variables can be accessed from anywhere within the Ruby program.
+ They start with a dollar sign ($) followed by a name.
+ Use of global variables should be minimized as they can lead to unexpected behavior and make code harder to maintain.
+ Example : `$global_var = "Hello"`
