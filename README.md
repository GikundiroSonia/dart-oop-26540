# Kigali Bus Card OOP Assignment

**Student Name:** Sonia Gikundiro  
**Registration Number:** 26540

## My Personal Numbers

- D = 40
- L = 0
- Starting Balance = 1400 RWF
- Bus Fare = 240 RWF
- Student Discount = 10%

## Part 1: BusCard

The balance has no setter because users should not change it directly. They should use topUp() and pay() to control the balance safely.

## Part 2: StudentCard

The `~/` operator performs integer division. It returns a whole number, while `/` returns a decimal number.

## Part 3: Program Output

Paste the actual output from running:

`dart run main.dart`

## Part 4: Bug Hunt

| Bug | Correction |
|---|---|
| Fields were not initialized | Added initial values |
| Parent constructor was not called | Used `super(brand, battery)` |
| Override method did not exist in parent | Removed invalid `@override` |
| Battery had no setter | Added a setter |
| Getter was called like a method | Used `p.battery` |

**Not a bug:** `p.battery = 100;` is correct because the battery setter accepts values from 0 to 100.

## Part 5: Prediction

Predicted output:

1
5

The first output is 1 because the negative value is rejected. BigBag adds two items each time, so after two calls and one extra item, the result is 5.

## Conclusion

This assignment helped me understand classes, objects, inheritance, encapsulation, getters, setters and method overriding in Dart.
