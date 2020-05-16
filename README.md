# Java-8-new-features

Java 8 features in simple way

11/05
New features of JAVA 8

1.Lambda expression.
2.Functional Interfaces.
3.Default methods in interfaces.
4.static methods in interfcae.
5.Predicate- predefined functional interface.
6.Function- predifined functional interface.
7.Consumer- predefined functional interface.
8.Method and constructor reference by :: operator.
9.Stream API.
10.Date and Time API-introduced by Joda.org -so joda api
 

Interface- every method is public and abstract, variables are public static final.(till 1.7)

Main objectives of Java 8 - to simplify programming.(version introduction main intention is to simplify or concise the programming).
                          - to utilize functional oriented programming by using Lambda expression.
                          - to enable parallel processing, so that program can run on multi core processor. 


Lambda expessions Intro.

Lambda calculus bought major changes in the mathematics world.

Lambda Expression is used in many programming Languages like LISP, C,Objective C, C#.

Finally Java also started using this Lambda expression.


Benefits of Lambda- To enable Functional programming in JAVA.
                    To write more readable, concise and maintainable code.
                    To use API's very easily and effectively.
                    To enable the parallel processsing.
                    
 
 12/05
 How to write Lambda expressions:

Its an anonymous function-nameless function. It does not have modifiers and return type.

Simple lambda expression

() -> { System.out.println("Hello");} (Arrow symbol to indicate anonymous function).

If you are aware of writing a method in JAVA, anonymous function is very simple to write.

If the body of the lambda expression contains only one statement, then curly braces are optional.

Based on the context if the compiler able to guess/identify the data types automatically then that is called Type Inference


05/16

Properties of lamba expression

1.A lambda expression can take any number of arguments and multiple arguments need to be seperated by comma(,), for single statement in lambda expression flower braces are opetional else it is mandatory.

ex- ()->S.O.P("Hello");
(inta, int b)->S.O.P(a+b);
()->{statement 1;stattement 2; statement 3;}
2.In lambda expression if we have only one parameter then we can remove the braces.

ex-(s)->S.O.P(s.length()); can be written as s->S.O.P(s.length());

3.If the compiler is capable of identifying the date type then we can remove the type declaration as well(known as type inference).

Ex- (int a, int b)->S.O.P(a+b); this can be written as (a,b)->S.O.P(a+b);

4.If lambda expression returns something then we can remove return keyword.

Ex- s-> return s.length(); can be written as s->s.length();

Functional Interface:

Actually a lambda expression is also a method, it should be called somewhere based on our requirement.

To invoke this lambda expression we require Functional Interface.

First what is functional Interface -

If the interface has only one abstract method then it is called as Functional Interface.

Example-Runnable and Callable.









