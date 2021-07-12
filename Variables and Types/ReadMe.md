## Variables and Types

- python variable should begin with a uppercase or lowercase letter or with an underscore (\_)
- Cannot begin with a number
- python variables are case sensitive go `greeting` and `Greeting` will be considered as two different variables
- Variables in python `:p` strongly typed and dynamically types
  - <pre>
        <code> 
                age = 24
                print(age) # prints number 24
                age = "Twenty four"
                print(age) # prints string value "Twenty four"
        </code>
    </pre>
  - <pre>
        <code> 
                age = 24
                print("age is: "+ age) # Throws error `cannot concatenate string and a int value`
        </code>
    </pre>
- Numeric Types

  - int
  - float
  - decimal
  - complex
  - <pre>
        <code> 
            a = 12
            b = 3
    
            print(a + b)    # 15 
            print(a - b)    # 9
            print(a * b)    # 36
            print(a / b)    # 4.0
            print(a // b)   # 4 :integer division rounded towards the minus infinity
            print(a % b)    # 0 :modulo division reminder after integer division
        </code>
    </pre>

  -
