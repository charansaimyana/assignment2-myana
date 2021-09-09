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

 ## Code Fencing


> Hashing is an important technique which converts any object into an integer of a given range. Hashing is the key idea behind Hash Maps which provides searching in any dataset in O(1) time complexity. Hashing is widely used in a variety of problems as we can map any data to integer upon which we can do arithmetic operations or use it as an index for data structures. We will take a look at the techniques to hash a string that is to convert a string to an integer.
Ideally, an hashing technique has the following properties:
If S is the object and H is the hash function, then hash of S is denoted by H(S).
If there are two distinct objects S1 and S2, ideally, H(S1) should not be equal to H(S2).
In some cases, H(S1) can be equal to H(S2) which we call collision and can be minimized and taken care of as well
If there is a range of hash function H as 0 to M, then H(S) = H(S) mod M.

[Description](https://iq.opengenus.org/string-hashing)


```
long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}

```

[Source Code](https://cp-algorithms.com/string/string-hashing.html)










