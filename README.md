# assignment2-pogula
# POGULA SAI PUNEETH
###### Salar Jung museum
The Salar Jung Museum is an art museum located at Dar-ul-Shifa, on the southern bank of the Musi River in the city of **Hyderabad**, **Telangana**, India. It is one of the notable National Museums of India.[1] Originally a private art collection of the Salar Jung family, it was endowed to the nation after the death of Salar Jung III. It was inaugurated on 16 December 1951.

Ordered List
***
# Rajiv Gandhi InternationaL Airport
 Direction from airport to museum
 1. Take a bus from airport to mehidpatanam.
 2. From mehdipatnam take a auto to ameerpet.
 3. From ameerpet bus stand walk 500m straight there goes salar jung museum.

# Unordered List
* Charminar
* Golkonda Fort
* NTR Gardens
* Birla Mandir


[AboutMe](AboutMe.md)

***
# Tables

The tables below tells about the location to visit them when you go to those cities.

|  # Name of a city | # location to visit | # amount of time |
|  ---            | ---               | ---            |
| Hyderabad       | Charminar         | 3 hours        |
| Mumbai          | Lokandwala        | 6 hours        |
| Goa             | Baga Beach        | 2 hours        |
| Vijaywada       | KankaDurga temple | 2 hours        |

***
# BlockQuotes
> Arise!Awake!and do not stop untill the goal is reached -- *swami vivekanada*

> Be the change you wish to see the world -- *swami vivekanada*

***
# code fencing

How to write code get  quick-sort value?

[how to sort in svg](https://stackoverflow.com/questions/17915276/sorting-data-bound-to-svg-elements-using-d3-js)
```
@function quick-sort($list) {
  $less:  ();
  $equal: ();
  $large: ();

  @if length($list) > 1 {
    $seed: nth($list, ceil(length($list) / 2));

    @each $item in $list {
      @if ($item == $seed) {
        $equal: append($equal, $item);
      } @else if ($item < $seed) {
        $less: append($less, $item);
      } @else if ($item > $SEED) {
        $large: append($large, $item);
      }
    }

    @return join(join(quick-sort($less, $order), $equal), quick-sort($large, $order));
  }

  @return $list;
}
```
[sorting function](https://css-tricks.com/snippets/sass/sorting-function/)
