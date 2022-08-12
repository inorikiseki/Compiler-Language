# Compiler-Language

Here are some thoughts about the language's sytax and design.

## every thing is a unit may with a scope.
A unit can take the role of const, var, func, class. 

var func class in this languge nothing differs in nature.

so what var can do, class and func do.
A unit is acutually a scope.
A scope can be given a name.
Every scope scope holds a value units including a nil.return value can more than one unit.
every indent make a scope declaration.
Vice versa.
Bad English.
# decleration : means you are declaring , '=' use for asign value
  the declarations are just a name to mark. everything can be anonymous. name are just mark for using. 
  name do not affect any functionality and the syntax conception.
  ## as var style:
  one:
    1.int
    //int is acctully a functional unit, it receive 1  as arg and has the integer behaviour.
    //also 1 is unit,too. But may be implement by trick.
    //Thus makes this varible has the value 1 as integer
   //varible is just a name.
   //you may not need to declare.
   // the '1' it self is just a unit with less imperative meaning if not work with int,string,bool and so on
   // the '1' itself can ,when work with other unit, be used to get the unit's first sub unit.
   //int's all sub units is all intergers 2^n, n is the bits
   true:
    true.bool
    //this overrides true but has no meaning, cuz it has the same functionality
    //bool's all sub note is two:
    //fisrt:
      'true'
     //second:
     // 'false'
     //actually true is  1,false is 0
     //false:s
        0
     // true:
          1
     
   varible:
  ## as func style:
  function arg1,arg2:return_type:
    scope
  arg1.function arg2:return type:
    scope
  arg1,arg2.function:return type:
    scope
   as said:
   (arg can be any thing
   args can place both front the func name and behind)
# calling
   arg1.func = func arg1.
   
  arg1.func arg2 = func arg1,arg2 =  arg1,arg2.func
  
  (a dot itself is a function.
  void function:
    .  do nothing as placeholder,may follow a space
    syntax assistance,
    end func lists )
  
   fractional:
    arg1.func1 arg2.func2  = arg1.arg2.func2.func1= arg1.func1 func2 arg2= func1 arg1,func2 arg2
    (also write:as said nothing different among var and func,so
      unit1.unit2 unit3.unit4 = unit1.unit2 unit3 unit4=
    for example:
      hello:
        "hello"
      world:
        "world"
       str.uppercase:
          str.1.uppercase //.1 return a values first element
       str1.add_arg str2:
          str1,str2 //multiple return value
       //calling
       hello.add_arg world .uppercase //== "HELLOWORLD"
       //a string in nature like this:
       // "hello"="h","e","l","l","o"
       // var,var,var  is actually a scope, may take the role of an array.
       //that is saying. scope can contain scope.
       //, make two scope be one scope
       //1. 2. 3. unit can be used to access sub scope
       //in other words, no matter how many args there is acutually one arg.but the arg may contain sub unit.
       //to some point, every unit contain sub unit even a void sub unit. so not to be worried about should there be sub units.
       //there always. we should develop a way for not to care about sub unit
       
       
       
