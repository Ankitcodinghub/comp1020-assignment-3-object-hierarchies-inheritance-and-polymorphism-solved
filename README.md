# comp1020-assignment-3-object-hierarchies-inheritance-and-polymorphism-solved
**TO GET THIS SOLUTION VISIT:** [COMP1020 ASSIGNMENT 3-Object hierarchies, inheritance and polymorphism Solved](https://www.ankitcodinghub.com/product/comp1020-assignment-3-object-hierarchies-inheritance-and-polymorphism-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91856&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP1020 ASSIGNMENT 3-Object hierarchies, inheritance and polymorphism Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Assignment overview

In this assignment, you will implement a simplified Fishing Tracking program.

You will start by building classes to represent a type of fish, an actual fish, and a fishing trip. In phase 2, you will build a hierarchy of Fisher classes (see the representation below).

SportFisher

Testing Your Code

We have provided sample test files for each phase to help you verify that your code is working to the assignment specifications (e.g., correct method headers). These files are only starting points for testing your code. Part of developing your skills as a programmer is to think through additional important test cases and to write your own code to test these cases. The test files should give you a sense what this additional code could consist of.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Phase 1: FishType, Fish, FishingTrips:

First, implement three simple classes: a FishType class, a Fish class. All methods should be public unless otherwise specified.

The FishType class should have:

<ul>
<li> &nbsp;Four instance variables: the name of the fish (a String), the rarity of the fish type (a String), the price per pound (a double) and the minimum age restriction for catching a fish of this type (an int).</li>
<li> &nbsp;A constructor that has four parameters (String, String, double, int), which are used to initialize the four instance variables described above (in the same order).</li>
<li> &nbsp;Three accessor methods: getRarity() which returns the FishType’s rarity, getPrice() which returns the price of the FishType, and getRestriction() which returns the minimum age restriction.</li>
<li> &nbsp;A void method changePrice(double) which sets the FishType’s current price to the value received as a parameter.</li>
<li> &nbsp;A getDescription() method that return a String containing the FishType’s name, and the rarity (in between parentheses).</li>
<li> &nbsp;A standard toString() method, which returns a String containing the FishType’s name, rarity (in between parentheses), price, and minimum age restriction (in between parentheses). Format this string as shown in the output below. Use the String.format method to insert the double values with only 2 digits after the decimal point.</li>
<li> &nbsp;A boolean equals(Object) method that checks if the provided Object is equal to this FishType. Two FishTypes are equal if they have the same name, rarity, restriction, and that their difference in price is less than half a cent (0.005).
The Fish class should have:
</li>
</ul>
<ul>
<li> &nbsp;Three instance variables: the type of the Fish (a FishType), the weight of the fish in pounds (a double), and the age of the fish (an int).</li>
<li> &nbsp;A constructor with three parameters (FishType, double, int), which are used to initialize the three instance variables described above (in the same order).</li>
<li> &nbsp;Three accessor methods getWeight(), getType(), and getAge() that return the values of the corresponding instance variables.</li>
<li> &nbsp;A double getValue() method, which returns the total value of the Fish.</li>
<li> &nbsp;A boolean isValid() method, which will return whether or not this fish matches or is over the minimum age
restriction and can therefore be kept, or must be released.
</li>
<li> &nbsp;A toString() method which returns a String containing the FishType’s name, the FishType’s rarity (given by
FishType.getDescription()), the fish’s weight, and the total value of the fish (given by getValue()) in between

parentheses and whether it is a legal catch. See the example output below for the exact formatting.
</li>
<li> &nbsp;A boolean equals(Object) method that checks if the provided Object is equal to this Fish. Two Fish are equal if they have the same type, their difference in weight is less than 1 hundredth of a pound, and their isValid() result
is identical.

YoucanbegintestingyourclasseswithTestFishTypes.java, and TestFish.java.Youshouldgetthe output shown below.

TestFishTypes.java:

Created four FishType instances, let’s see how they look: FishType1 toString: Ayu, Sweetfish (Common) $5.00 (1) FishType2 toString: Ayu, Sweetfish (Common) $5.01 (1) FishType3 description: Ayu, Sweetfish (Common)

FishType4 description: Bicolor Goatfish, (Uncommon)
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
&nbsp;

<pre>           Let's take the Equals method for a test drive:
           Are FishType1 and FishType2 equal? They should NOT be: false
           Are FishType1 and FishType3 equal? They should be: true
           Are FishType2 and FishType3 equal? They should be: true
           Are FishType1 and FishType4 equal? They should NOT be: false
</pre>
Time for some getters and setters:

How rare is FishType1? Common

How rare is FishType4? Uncommon

What’s the price per pound of FishType1? $5.00 What’s the price per pound of FishType4? $10.00 What’s the new price per pound of FishType3? $5.25 What’s the age restriction of FishType1? 1

<pre>           What's the age restriction of FishType4? 2
</pre>
TestFish.java:

Created five Fish instances, let’s see how they look:

Fish1: Ayu, Sweetfish (Common), 2.10 pounds ($10.50), This is a legal catch

Fish2: Ayu, Sweetfish (Common), 2.11 pounds ($10.55), This is a legal catch

Fish3: Ayu, Sweetfish (Common), 1.10 pounds ($5.50), We should release this fish Fish4: Bicolor Goatfish, (Uncommon), 4.70 pounds ($47.00), This is a legal catch Fish5: Bicolor Goatfish, (Uncommon), 1.51 pounds ($15.10), We should release this fish

Let’s take the Equals method for a test drive:

Are Fish1 and Fish2 equal? They should be: true

Are Fish1 and Fish3 equal? They should NOT be: false Are Fish4 and Fish5 equal? They should NOT be: false

<pre>           Time for some getters and setters:
           Fish1 is 2.10 pounds.
           What type is Fish4? Bicolor Goatfish, (Uncommon) $10.00 (2)
           Fish3 is 0 years old.
           We could sell Fish2 for $10.55.
           With the new price change, we could now sell Fish2 for $11.08.
           Was Fish5 a valid catch? false
</pre>
Phase 2 FishingTrip:

The FishingTrip class represents a fishing trip that has been made. It stores all the information about that fishing

trip (an array of Fish caught). It should have:

<ul>
<li> &nbsp;Three instance variables: a partially-filled array of fish brought back to shore (a Fish[]),the amount of fish being brought back (an int), and finally the total number of fish caught during the trip (an int), which may be greater than the amount of fish actually brought back. We will add an additional instance variable in Phase 3.</li>
<li> &nbsp;A constructor with one parameter FishingTrip(int maxAmount), which is used to instantiate the partially-filled array. The amount and total number of fish caught are always initialized to 0. We will create an additional constructor in Phase 3.</li>
<li> &nbsp;Two accessor methods getTotal() and getAmount() that return the value of the corresponding instance variables.</li>
<li> &nbsp;A double getTotalValue() method, which returns the total value of all of the fish caught.</li>
<li> &nbsp;A double getTotalWeight() method, which returns the total weight of all of the fish brought back.</li>
<li> &nbsp;A boolean catchFish(Fish newFish) method, which adds the Fish object received as a parameter to the array of
Fish to be brought back, if there is room for it. The method will return a boolean indicating if the fish was added to the array. This method should also increment amount if the fish was added to the array. The total instance variable should be incremented regardless of whether or not the fish was added.
</li>
<li> &nbsp;A Fish releaseFish(int index) method which removes the Fish located at the index parameter from the brought back array and returns it to the caller.</li>
</ul>
• This method should check to ensure that the index it is passed is valid, if the index is invalid, the method should return null.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ul>
<li>Once a fish is removed from the array, the elements after it in the array should be arranged to ensure there are no empty/null spots in the array.</li>
<li>This method should decrement amount accordingly if the fish was successfully released.</li>
</ul>
<ul>
<li> &nbsp;A toString() method which returns a String containing the total amount of fish caught, the amount being
brought back out of the maximum possible, and then listing each individual fish being brought back. See the

example output below for the exact formatting.
</li>
<li> &nbsp;A boolean equals(Object) method that checks if the provided Object is equal to this FishingTrip. Two
FishingTrips are considered equal if the difference between their getTotalValue() results is less than ten cents (0.1), the difference between their getTotalWeight() results is less than 1 tenth of a pound (0.1), and that their amount and total number of caught fish match.
</li>
</ul>
You can begin testing your classes with TestFishingTrips.java. You should get the output shown below.

TestFishingTrips.java:

Created three FishingStrip instances, let’s see how they look: Trip1: During this FishingTrip, 0 total Fish were caught. Sadly, the boat is empty.

Trip2: During this FishingTrip, 0 total Fish were caught. Sadly, the boat is empty.

Trip3: During this FishingTrip, 0 total Fish were caught. Sadly, the boat is empty.

Trip1 is trying to catch a fish, can it be brought back? true Trip1 is trying to catch a fish, can it be brought back? true Trip1 is trying to catch a fish, can it be brought back? true Trip1 is trying to catch a fish, can it be brought back? true Trip1 is trying to catch a fish, can it be brought back? true Trip1 is trying to catch a fish, can it be brought back? false

<pre>           Let's check the total value of the FishingTrips:
           Trip1: $2.63.
           Trip2: $63.43.
           Trip3: $2.63.
</pre>
Let’s check the total weight of the FishingTrips: Trip1: 10.50 pounds.

Trip2: 11.52 pounds.

Trip3: 10.51 pounds.

Let’s see how they look now:

Trip1: During this FishingTrip, 6 total Fish were caught, and 5/5 were brought back:

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch &gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch &gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch &gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch &gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

Trip2: During this FishingTrip, 5 total Fish were caught, and 5/99 were brought back: &gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

&gt; Ayu, Sweetfish (Common), 2.11 pounds ($0.53), This is a legal catch

&gt; Ayu, Sweetfish (Common), 1.10 pounds ($0.28), We should release this fish

&gt; Bicolor Goatfish, (Uncommon), 4.70 pounds ($47.00), This is a legal catch

&gt; Bicolor Goatfish, (Uncommon), 1.51 pounds ($15.10), We should release this fish

Trip3: During this FishingTrip, 5 total Fish were caught, and 5/15 were brought back: &gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch &gt; Ayu, Sweetfish (Common), 2.11 pounds ($0.53), This is a legal catch

Time to try out releasing some fish:

Release the fist invalid Fish in Trip2: Ayu, Sweetfish (Common), 1.10 pounds ($0.28), We should release this fish

Release the second invalid Fish in Trip2: Bicolor Goatfish, (Uncommon), 1.51 pounds ($15.10), We should release this fish

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 4 of 8

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 3: Object hierarchies, inheritance and polymorphism COMP 1020 Fall 2021

Try to release an invalid Fish in Trip2: null

Check Trip2:

During this FishingTrip, 5 total Fish were caught, and 3/99 were brought back:

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

&gt; Ayu, Sweetfish (Common), 2.11 pounds ($0.53), This is a legal catch

&gt; Bicolor Goatfish, (Uncommon), 4.70 pounds ($47.00), This is a legal catch

<pre>           Let's release all the Fish in Trip2
</pre>
<pre>           Check Trip2 again:
           During this FishingTrip, 5 total Fish were caught.
           Sadly, the boat is empty.
</pre>
<pre>           Let's take the Equals method for a test drive:
           Are Trip1 and Trip2 equal? They should NOT be: false
           Are Trip1 and Trip3 equal? They should NOT be: false
           Are Trip1 and Trip3 equal? They should be now: true
</pre>
Phase 3 Fisher hierarchy:

Next, implement these classes: Fisher, RecreatonalFisher, SportFisher, and CommercialFisher following the descriptions below. All methods should be public unless otherwise specified.

The Fisher class must be an abstract class. It should have:

<ul>
<li> &nbsp;Three main instance variables: the name of the fisher (a String), and the limit on the amount of fish this
fisher can bring back (an int), and the latest FishingTrip this Fisher has gone on.
</li>
<li> &nbsp;A constructor that accepts the fisher’s name (a String), and the fishing limit (an int), the latest FishingTrip
starts off as null.
</li>
<li> &nbsp;Three accessor methods: getName(), getLimit(), and getTrip() which each return the appropriate instance
variable.
</li>
<li> &nbsp;One mutator method setTrip(FishingTrip) which will set the appropriate instance variable.</li>
<li> &nbsp;A abstract public fishCaught(Fish) method that will update the relevant values in the classes that
implement it, this method will be called in the FishingTrip class’s catchFish() method, detailed further

below.
</li>
<li> &nbsp;A toString() method that returns a String containing the fisher’s name, fishing limit, and latest FishingTrip
(formatted exactly as shown in the sample output below).
</li>
<li> &nbsp;A abstract String describeLatestTrip() method that will return a String describing the latest FishingTrip,
each child of Fisher will implement this method slightly differently.
</li>
<li> &nbsp;A boolean equals(Object) method that checks if the provided Object is equal to this Fisher. Two Fishers
are considered equal if their names and limits are the same.

The RecreationalFisher class should be a subclass of Fisher. It should have:
</li>
<li> &nbsp;One additional instance variable, the grand total of all fish ever caught by this fisher (an int). Note that
this number also includes fish that were caught and released.
</li>
<li> &nbsp;A constructor that receives only the name parameter, in which case the limit will be 0, and the grand
total is initialized to 0. This constructor should call the superclass constructor to initialize the instance

variables.
</li>
<li> &nbsp;The RecreationalFisher class should also have another constructor that accepts both a name and a limit.
This constructor should call the superclass constructor to initialize the instance variables.
</li>
<li> &nbsp;A implementation of fishCaught(Fish) method that will increment the grand total of fish caught.</li>
<li> &nbsp;One accessor methods: getGrandTotal(), which returns the appropriate instance variable.</li>
<li> &nbsp;An overridden toString() method that returns a String containing the result from its parent class’s
toString(), as well as the total number of fish ever caught (formatted exactly as shown in the sample

output below).
</li>
<li> &nbsp;An implementation of describeLatestTrip() which will just return the result of the toString() method of
the FishingTrip (formatted exactly as shown in the sample output below).
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
The SportFisher class should be a subclass of RecreationalFisher. It should have:

<ul>
<li> &nbsp;One additional instance variable, the total weight of all fish ever caught by this fisher (a double). Note
that this number also includes fish that were caught and released.
</li>
<li> &nbsp;A constructor that accepts the fisher’s name (a String), and the fishing limit (an int). The total weight
should be initialized to 0. This constructor should call the superclass constructor to initialize the instance

variables.
</li>
<li> &nbsp;A implementation of fishCaught(Fish) method that will add the weight of the caught fish to the grand
total. The parent class’s fishCaught() method should also be called.
</li>
<li> &nbsp;One accessor methods: getTotalWeight(), which returns the appropriate instance variable.</li>
<li> &nbsp;An overridden toString() method that returns a String containing the result from its parent class’
toString(), as well as the total weight of fish ever caught (formatted exactly as shown in the sample output

below).
</li>
<li> &nbsp;An overridden of describeLatestTrip() which will return the result of the toString() method of the
FishingTrip and add the total weight of fish brought back (formatted exactly as shown in the sample output below).

The CommercialFisher class should be a subclass of Fisher. It should have:
</li>
</ul>
<ul>
<li> &nbsp;One additional instance variable, the grand total value of all fish ever caught by this fisher (a double).
Note that this number also includes fish that were caught and released.
</li>
<li> &nbsp;A constructor that receives the name parameter, and the fishing limit (an int), the grand total is always
initialized to 0. This constructor should call the superclass constructor to initialize the instance variables.
</li>
<li> &nbsp;One accessor methods: getTotalValue (), which returns the appropriate instance variable.</li>
<li> &nbsp;A implementation of fishCaught(Fish) method that will add the value of the caught fish to the grand total.</li>
<li> &nbsp;An overridden toString() method that returns a String containing the result from its parent class’
toString(), as well as the total value of fish ever caught (formatted exactly as shown in the sample output

below).
</li>
<li> &nbsp;An implementation of describeLatestTrip() which (unlike the other Fisher classes) will NOT return the
result of the toString() method of the FishingTrip and rather only return the getTotalValue() for the trip (formatted exactly as shown in the sample output below).

Phase 3 FishingTrip additions

In this phase we will also extend the FishingTrip class as follows:
</li>
<li> &nbsp;We will add an additional instance variable, the fisher who’s fishing trip this is (a Fisher object).</li>
<li> &nbsp;A new constructor with one parameter: FishingTrip(Fisher), which sets the corresponding instance variable and calls the previously defined constructor (FishingTrip(int size)) using the Fisher object’s fish limit value, the
fisher’s latest trip should be set to this one as well.

The catchFish(Fish) method should now call the fishCaught(Fish) method of it’s fisher instance variable, if fisher is

not null.You can begin testing your classes with TestFishers.java. You should get the output shown below.

TestFishers.java:

Created three Fisher instances, let’s see how they look: Fisher1: Gabriel, limited to 0 fish.

Latest Trip: During this FishingTrip, 0 total Fish were caught. Sadly, the boat is empty.

In total, this Fisher has caught: 0 fish.

Fisher2: Jon, limited to 2 fish.

Latest Trip: During this FishingTrip, 0 total Fish were caught. Sadly, the boat is empty.

In total, this Fisher has caught: 0 fish.

In total, this Fisher has caught: 0.00 pounds of fish.

Fisher3: Frédéric, limited to 5 fish.

Latest Trip: During this FishingTrip, 0 total Fish were caught. Sadly, the boat is empty.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
In total, this Fisher has caught: $0.00 worth of fish.

Catch a Fish for trip1, attached to a Recreational Fisher, they should all be false: Trip1 is trying to catch a fish, can it be brought back? false

Trip1 is trying to catch a fish, can it be brought back? false

Fisher1 should now have two fish caught in total:

Gabriel, limited to 0 fish.

Latest Trip: During this FishingTrip, 2 total Fish were caught. Sadly, the boat is empty.

In total, this Fisher has caught: 2 fish.

<pre>           Fisher1 grand total: 2
</pre>
Catch a Fish for trip1, attached to a Recreational Fisher, the first 2 should be true: Trip2 is trying to catch a fish, can it be brought back? true

Trip2 is trying to catch a fish, can it be brought back? true

Trip2 is trying to catch a fish, can it be brought back? false

Fisher2 should now have three fish caught in total, and two brought back:

Jon, limited to 2 fish.

Latest Trip: During this FishingTrip, 3 total Fish were caught, and 2/2 were brought back:

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

<pre>            &gt; Bicolor Goatfish, (Uncommon), 4.70 pounds ($47.00), This is a legal catch
           In total, this Fisher has caught: 3 fish.
           In total, this Fisher has caught: 8.31 pounds of fish.
</pre>
Fisher2 describes their latest trip:

During this FishingTrip, 3 total Fish were caught, and 2/2 were brought back:

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

<pre>            &gt; Bicolor Goatfish, (Uncommon), 4.70 pounds ($47.00), This is a legal catch
           That's 6.80 pounds of fish!
</pre>
Fisher2 grand total: 3

Fisher2 total weight: 8.31 pounds

Catch a Fish for trip1, attached to a Recreational Fisher, the first 5 should be true: Trip3 is trying to catch a fish, can it be brought back? true

Trip3 is trying to catch a fish, can it be brought back? true

Trip3 is trying to catch a fish, can it be brought back? true

Trip3 is trying to catch a fish, can it be brought back? true Trip3 is trying to catch a fish, can it be brought back? true Trip3 is trying to catch a fish, can it be brought back? false

Fisher2 should now have six fish caught in total, and five brought back:

Frédéric, limited to 5 fish.

Latest Trip: During this FishingTrip, 6 total Fish were caught, and 5/5 were brought back:

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

&gt; Ayu, Sweetfish (Common), 2.11 pounds ($0.53), This is a legal catch

&gt; Ayu, Sweetfish (Common), 1.10 pounds ($0.28), We should release this fish

&gt; Bicolor Goatfish, (Uncommon), 4.70 pounds ($47.00), This is a legal catch

&gt; Bicolor Goatfish, (Uncommon), 1.51 pounds ($15.10), We should release this fish

<pre>           In total, this Fisher has caught: $95.93 worth of fish.
           Fisher2 total value: $95.93
</pre>
Fisher1 describes their latest trip:

During this FishingTrip, 2 total Fish were caught. Sadly, the boat is empty.

Fisher2 describes their latest trip:

During this FishingTrip, 3 total Fish were caught, and 2/2 were brought back:

&gt; Ayu, Sweetfish (Common), 2.10 pounds ($0.53), This is a legal catch

<pre>            &gt; Bicolor Goatfish, (Uncommon), 4.70 pounds ($47.00), This is a legal catch
           That's 6.80 pounds of fish!
</pre>
Fisher3 describes their latest trip:

The latest Fishing Expedition resulted in $63.43 in profits.

<pre>           Gave each Fisher a new FishingTrip:</pre>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
<pre>           Trip1 is trying to catch a fish, can it be brought
           Trip2 is trying to catch a fish, can it be brought
           Trip3 is trying to catch a fish, can it be brought
</pre>
Last look at the Fisher instances:

Fisher1: Gabriel, limited to 0 fish.

Latest Trip: During this FishingTrip, 1 total Fish Sadly, the boat is empty.

In total, this Fisher has caught: 3 fish.

</div>
<div class="column">
<pre>back? false
back? true
back? true
</pre>
were caught.

</div>
</div>
<div class="layoutArea">
<div class="column">
Fisher2: Jon, limited to 2 fish.

Latest Trip: During this FishingTrip, 1 total Fish were caught, and 1/2 were brought back:

&gt; Bicolor Goatfish, (Uncommon), 1.51 pounds ($15.10), We should release this fish In total, this Fisher has caught: 4 fish.

In total, this Fisher has caught: 9.82 pounds of fish.

Fisher3: Frédéric, limited to 5 fish.

Latest Trip: During this FishingTrip, 1 total Fish were caught, and 1/5 were brought back:

<pre>            &gt; Bicolor Goatfish, (Uncommon), 4.70 pounds ($47.00), This is a legal catch
           In total, this Fisher has caught: $142.93 worth of fish.
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
