# assignment2-myana

# Charan Sai Myana

#### Gayathri Temple

This is a temple which is very nearer to my undergrad college.The Lord **Gayathri** is worshipped ovethere.Thebe best thing I liked over there is the quiteness which keep our mind calm. Since it is far from the city there would be no heavy public which made me more **comfortable**.


***

## Route To Troy From Maryville

1. Take a Roadway from maryville to Kansas Airport.
2. Take a flight to Atlanta.
3. Then go with the connecting flight to Albany,since this is the nearest airport to it.
4. And then go in a car on roadways which would hardly take 15 minutes.

## Things to bring

- Camera
- Sport Shoe
- Some Outdoor game equipments
- Swim suits


[About Me](/AboutMe.md)

***

 ## Food and Drinks info :

The following table consists of food and drinks which one should try for sure.It also consists of the location where it is avialble and the price for it.

| Food/Drinks      | Location                      | Price         |
| :---             |    :----:                     |          ---: |
| Chicken Biryani  | Godavari Restaurant,kansas    | $10           |
| Mutton pulao     | Indian Street,Newjersy        | $14           |
| Sambar Rice      | Indhu Hotel,Kansas            | $8            |
| Sweet Lassi      | Lassi spot, St.Louis          | $5            |


***

## Qoutes

> Everyone have two lives, the second starts when you realize that you have only one.

 -*Confucius*


> Get busy Living or Get busy Dying.

 -*Stephen King*

 ***

 >> Calculation of the hash of a string
        The good and widely used way to define the hash of a string s of length n is

hash(s)=s[0]+s[1]⋅p+s[2]⋅p2+...+s[n−1]⋅pn−1modm=∑i=0n−1s[i]⋅pimodm,
where p and m are some chosen, positive numbers. It is called a polynomial rolling hash function.

It is reasonable to make p a prime number roughly equal to the number of characters in the input alphabet. For example, if the input is composed of only lowercase letters of the English alphabet, p=31 is a good choice. If the input may contain both uppercase and lowercase letters, then p=53 is a possible choice. The code in this article will use p=31.

Obviously m should be a large number since the probability of two random strings colliding is about ≈1m. Sometimes m=264 is chosen, since then the integer overflows of 64-bit integers work exactly like the modulo operation. However, there exists a method, which generates colliding strings (which work independently from the choice of p). So in practice, m=264 is not recommended. A good choice for m is some large prime number. The code in this article will just use m=109+9. This is a large number, but still small enough so that we can perform multiplication of two values using 64-bit integers.


[Complete Code](https://cp-algorithms.com/string/string-hashing.html)










