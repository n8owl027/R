# R
# First R program                   
//use print()                                 
print("R is fun")                         
print("R is easy") 

# Comment
print("Hello, Saturn!")
//it doesn't print Hello Mars

# Variable
x <- 99

x 
// output is 99

name = "Python"

print(name)// Python

# Concatenate 
saturn <-  100

jupiter <- 101

sat <- saturn

jup <- jupiter

paste(sat , "is less than" , jup)

// paste() concatenate sat & jup

# Data Types <- Double

x <- 2.7

x

typeof (x)

# Data Types <- Integer

x <- 27L

x

typeof(x)// integer

y <- 80L

y

typeof(y) // integer

# Data Types <-  Logical

jup < sat

// 101 < 100

// FALSE

jup > sat

// 101 > 100 

// TRUE

# Quote

planet <- "I love \"Saturn\""

planet  // "I love \"Saturn\""


# Cat ( )

planet <- "I love \"Saturn\""

planet  // "I love \"Saturn\""

cat(planet)

// For ignoring “\” 

//I love "Saturn"

# Arithmetic Operator

a <- 80.4

b <- 22.1

c <- 2.5 

// Addition

d <- a + b + c

d

// Subtraction

e <- d - 5

e

// multiplication

f <- e * 2.0

f

// Division

g <- 125.54 / 3

g

// Exponential

h <- 13 ^ 2

h

// Remainder

i <- 125.54 %% 3

i

// Integer Division

j <- 125.54 %/% 3

j


# Max( )                                                                       

a <- 109

b <- 78

c <- 99 

max(a,b,c)

// print the maximum value 109

# Min( )

a <- 109

b <- 78

c <- 99 

min(a,b,c)

// print the minimum value 78

# Relational Operators

a <- 80

b <- 78

c <- 99 

d <- 99.0


a > b // TRUE

a > c // FALSE

b > a // FALSE

b > c // FALSE

c > a // TRUE

c > b // TRUE

c == d // TRUE

c == 99 // TRUE

c =! d // TRUE

c >= d // TRUE

c <= d // TRUE




# If-Else


saturn  <-  30

jupiter  <-  24.6

If (saturn  <  jupiter) {

print ("Sorry! Saturn")

}else {

print ("Sorry! Jupiter")

}

// Sorry! Jupiter

 
# Repeat Elements

cars <- rep( c ( 'audi' , 'bmw' , 'ferrari' ) , each = 2 )

cars

// [1] "audi"    "audi"    "bmw"     "bmw"     "ferrari" "ferrari"

cars <- rep( c ( 'audi' , 'bmw' , 'ferrari' ) ,times = 2 )

cars

// [1] "audi"    "bmw"     "ferrari" "audi"    "bmw"     "ferrari"

cars <- rep( c ( 'audi' , 'bmw' , 'ferrari' ) ,times = c(2, 3, 2 ))

cars

// [1] "audi"    "audi"    "bmw"     "bmw"     "bmw"     "ferrari" "ferrari"


