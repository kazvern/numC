### As a user, I want to be able to:

####  Compute derivatives of elementary functions
-  DoD: User/Client calls derivative method on desired function, and gets a matching derivative of the input function.

####  Compute derivatives of elementary functions at specific points
-  DoD: User/Client calls derivative method on desired function and specified coordinate, and it returns a numeric value if the derivative exists, 
-  else throws error if DNE or Undefined

####  Compute limits of elementary functions
-  User/Client calls limit method on desired function (we'll stick with single var functions for now) and approaching constant,
-  and gets evaluated result back, throws error if result DNE or is Undefined

####  Compute the trigonometric functions (sin/cos/tan) of a degree in radians
-  DoD: User/Client calls method on specified degree (program will assume its radians), and return its numeric value, throw error if DNE or Undefined
