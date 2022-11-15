# Learning R @ Belmont

Hello, I am Edwin Reed-Sanchez and I love to program, hack and tinker with technology. I also enjoy teaching students the basic programming principals that are universal with all programming languages.  

For this class we will be learning R, which is a widely programming language used for statistical and scientific analysis.  

## Information about R
- [R](https://www.r-project.org/)
- [R-studio](https://posit.co/downloads/)

## Software for Class
Sign up for [Replit](https://replit.com/) using your gmail account. 
- Email me  at ereedsanchez@gmail.com with me your username. 
- My replit uysername is: [replit.com/@ereedsanchez](https://replit.com/@ereedsanchez)


## Lesson 1 - The Basics
Today we will learn about basic programs and syntax used in R. 

### Print
`print(“text”)`

### Commenting
`#Comments your code`

### Variables using =
```R
x = 51
print(x)
```
```R
name = “sam”
print(sam)
```


### Variables using <-
### leftward <- operator

```R
X <- 42
print(X);
```
```R
x <- 9
y <- 3 
x <- y 
print(x)
```

### Data Types - Numbers
```R
#numeric
var1 <- 3.14

#integer
var2 <- 88L

print(var1)
print(var2)
```

### Data Types - Strings - Simple Text

```R
#text
var3 <- "hello"
print(var3)
```




### Data Types - Strings - quotations 

```R
message <- "This is called \"escaping\"."
print(message) 
```
will return
```
[1] "This is called \"escaping\"."
```
—
```R
message <- "This is called \"escaping\"."
cat(message)
```
will return
```
[1] "This is called "escaping".
```


## Lesson 2 - Basic Math

##### Arithmetic 
```R
x <- 11
y <- 4

#addition
print(x+y)

#substraction
print(x-y)

#multiplication
print(x*y)

#division
print(x/y)
```

##### Arithmetic Operators
```R
x <- 11
y <- 4

#exponentation
print(x^y) #or x**y

#modulus (remainder from division)
print(x%%y)

#integer division
print(x%/%y)
```


### Resources 
[Producing Simple Graphs with R](https://sites.harding.edu/fmccown/r/)

[Simple Bar Graphs in R](https://medium.com/beginner-at-bi-data-science-and-big-data/importing-data-into-r-from-a-csv-file-and-creating-a-chart-out-of-it-892d5bc81531_)



