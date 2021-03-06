## Resources
### First week:
##### Competitive Programming:
* Chapter 2 parts 2.1
* Chapter 2 parts 2.2

##### Competitive Programmer's Handbook:
* part 4.1, *Dynamic Arrays* (Including introduction to data structures in page 35)
* part 4.4, *Iterators and ranges* (except *Set iterators*)
* part 4.5, *Other Structures*

### Second week:
##### Competitive Programming:
* Chapter 2 part 2.3

##### Competitive Programmer's Handbook:
* page 40-41 *Set iterators*
* part 4.2, *Set structures*
* part 4.3, *Map structures*

### Third week:
##### Competitive Programming:
* Chapter 2 part 2.4

##### Competitive Programmer's Handbook:
* part 15.2 *Union-find structure*
* part 11 *Basics of graphs*
* part 9 *Range queries*

*optional but suggested:*
* part 28 *Segment trees revisited*

---

## Questions
### First week:
1. [The Festive Evening](https://codeforces.com/problemset/problem/834/B)
2. [Throwing cards away I](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=21&page=show_problem&problem=1876)
3. [Han Solo and Lazer Gun](https://codeforces.com/problemset/problem/514/B)
4. [Raising Bacteria](https://codeforces.com/problemset/problem/579/A)
5. [Number of Ways](https://codeforces.com/problemset/problem/466/C)

### Second week:
1. [Misha and Changing Handles](http://codeforces.com/problemset/problem/501/B)
2. [Set of Strings](http://codeforces.com/problemset/problem/544/A)
3. [Word Index](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=24&page=show_problem&problem=358)
4. [Add All](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=24&page=show_problem&problem=1895)
5. [Hoax or what](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=24&page=show_problem&problem=2077)

### Third week:
1. [Network Connections](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=24&page=show_problem&problem=734)
2. [Frequent values](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=24&page=show_problem&problem=2176)
3. [Resort](https://codeforces.com/problemset/problem/350/B)

*Some trickier and harder(better:)) problems:*
1. [Pashmak and Parmida's problem](https://codeforces.com/contest/459/problem/D)
2. [Enemy is weak](https://codeforces.com/contest/61/problem/E)


##### For more questions in this topic see codeforces questions with [*data structure*](https://codeforces.com/problemset/tags/data%20structures) tag.

---

## Editorial
### First week
1. see part *834B-The Festive Evening* [in this tutorial](https://codeforces.com/blog/entry/53567) and for more explanation with another data structure see [this section](#the-festive-evening-editorial).
2. see part *Throwing cards away I* [in this section](#throwing-cards-away-i-editorial).
3. see part *Han Solo and Lazer Gun* [in this tutorial](https://codeforces.com/blog/entry/16398)
4. see part *Problm 1 : Raising Bacteria* [in this tutorial](https://codeforces.com/blog/entry/20368).
5. see part *466C - Number of Ways* [in this tutorial](https://codeforces.com/blog/entry/13758). also see this [code](https://github.com/mehranagh20/ACM-ICPC/blob/master/IUT-ACM-LOCAL-2016/numberOfWays.cpp) which has explanation.


### Second week:
1. see part *501B - Misha and Changing Handles* [in this tutorial](http://codeforces.com/blog/entry/15743).
2. see part *544A-Set of Strings* [in this tutorial](http://codeforces.com/blog/entry/17773).
3. see the solution of *Word Index* [in this tutorial](http://www.algorithmist.com/index.php/UVa_417).
4. see the solution of *Add All* [in this tutorial](http://www.algorithmist.com/index.php/UVa_10954).
5. see the solution of *Hoax or what* [in this tutorial](http://davidudelson.com/blog/2015/07/23/uva-11136-hoax-or-what/).


### Third week:
1. see solution of *Network Connections* [in this tutorial](http://www.algorithmist.com/index.php/UVa_793), also see [code](http://davidudelson.com/blog/2015/07/25/uva-793-network-connections/).
2. see solution of *Frequent Values* [in this tutorial](http://www.algorithmist.com/index.php/UVa_11235).
3. see part *350B - Resort* [in this tutorial](https://codeforces.com/blog/entry/9042).
4. see part *459D - Pashmak and Parmida's problem* [in this tutorial](https://codeforces.com/blog/entry/13430).
5. see solution of *Enemy is weak* [in this tutorial](https://codeforces.com/blog/entry/1347), also see [code](https://codeforces.com/contest/61/submission/297182).


##### For more questions in this topic see codeforces questions with [*data structure*](https://codeforces.com/problemset/tags/data%20structures) tag.

---

#### Throwing cards away I Editorial
>This question is simple and basic.You can solve this Problem in 2 ways(Using 2 type of DS)   



`1.`Using Vector : just remove first element or __Push_back( )__ to end of vector. do it continuously until size of vector is equal to __1__. see[`code`](https://github.com/mehranagh20/ACM-ICPC/blob/master/uva/throwing-cards-away-i/10935.cpp)    
`2.`Using queue .this is similar to vector.just __pop( )__ or __push( )__ continuously until __q.size( ) == 1__ . then you can print the out put.all of these operations do in a for loop .see [`code`](http://codealltheproblems.blogspot.com/2015/10/uva-10935-throwing-cards-away-i.html)

* the important part of this question is how to output.if you get wrong answer notice how you print your outputs and notice that n can be equal to __1__

---

#### The Festive Evening Editorial
<div dir="rtl">
   به ازای هر رشته ی ورودی یک بار از ابتدا تا انتهای رشته را بررسی می کنیم تا آخرین موقعیت هر کاراکتر مشخص شود. (مثلاً برای رشته‌ی ABA، موقعیت آخرین کاراکتر A، برابر 2 و موقعیت آخرین کاراکتر B برابر 1 هست.) کافی است یک bitset یا حتی bitmask با اندازه 26 بیت داشته‌باشیم (هر بیت روشن یا خاموش به ازای هر حرف از حروف الفبای انگلیسی). یک بار دیگر روی رشته Linear Pass میزنیم. این بار به محض رسیدن به هر کاراکتر، بیت نظیرش را در bitset یا bitmask روشن می‌کنیم، این به این معنی است که درِ مربوط به آن کاراکتر هم‌اکنون در حال استفاده است. در هر نقطه‌ای از linear pass اگر تعداد بیت‌های روشن بیشتر از k بود نتیجه می‌گیریم که تعداد محافظان کافی نیست و حداقل یک در بدون محافظ باقی میماند (پس باید "YES" چاپ کنیم.) ضمنا در هر لحظه از linear pass اگر مکان کاراکتر مورد پردازش برابر با آخرین مکان اون کاراکتر داخل رشته بود، باید بیت نظیرش را خاموش کنیم (به این معنی که آخرین مهمان هم از در مورد نظر رد شده و آن در دیگر مورد استفاده نیست و نیاز به محافظ ندارد.) اگر با موفقیت از pass خارج شدیم، تعداد محافظان در هیچ برهه‌ای از زمان ناکافی نیست ("NO" چاپ می‌کنیم).
</div>
