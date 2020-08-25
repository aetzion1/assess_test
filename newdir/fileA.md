#CLASS, OBJECTS, ATTTRIBUTES, & METHODS#

##CLASS##
**CATS**

##ATTRIBUTES##   
  * Is_declawed (boolean)
  * Color (string)
  * Weight_lbs (float)
  * Age_months (integer)
  * Fav_toys (array)
  * Number_toys  (hash)

##Methods##
  * catch_mouse (increases weight_lbs)
  * declaw (changes Is_declawed to true)
  * Dye_fur (changes color)
  * one_month_later (increases Age_months by 1)
  * Buy_fav_ball (adds value to Fav_toys if no ball, increases hash value Number_toys for ball value by 1)

#Adams_Cat#

##Class##
**Cat**

##Attributes##
```
Is_declawed = false
Color = "white"
Weight_lbs = 10.3
Age_months = 11
Fav_toys = ['Mouse','String']
* Number_toys = {"Mouse" => 1, "String" =>3}

##Methods##
catch_mouse: weight_lbs = 10.6
declaw: Is_declawed = true
Dye_fur: Color = "pink"
one_month_later Age_months = 12
Buy_fav_ball:
  Fav_toys = ['Mouse','String', 'Ball']
  Number_toys = {"Mouse" => 1, "String" =>3, "Ball" => 1}
