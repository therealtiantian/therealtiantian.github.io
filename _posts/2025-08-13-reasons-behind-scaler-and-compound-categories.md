---
layout: post
title: Reasons Behind Scaler and Compound Categories
subtitle: 
tags: [CS]
---
In computer science, data can be broken down into atoms. For some atoms, a sequential stacking is still a meaningful piece of data, and for others not. That’s the basis of categorizing data into scaler and compound types. 

The reason behind this difference is whether position/index carries information. Consider a bag of things (or a set) as if you just carried a shopping bag from the grocery store. The sequence of their arrangement is not important. You just need one banana, two apples, and one jar of peanut butter. Whatever stacking strategy will all solve the problem. The sequence carries no information. When you go back home, you do not need to notice who is put onto whom, you just unpack them and only rearrange the grocery outside of the bag (set).

In this scenario, you can say that there are one banana, two apples, and one jar of peanut butter. Or you can say there are two apples, one banana, and one jar of peanut butter. Or one jar, two apples and one banana. This is the archetype of a compound type of data. 

But some compound type also carry positional information, but it is assigned instead of innate. For example, elements in a tuple are indexed, but the indices are artifical and can be changed according to demands. I can label my banana as 0, apples as 1, peanut butter as 2 when I want to arrange them in this fashion, but when I am in the mood of prioritizing peanut butter, I can make peanut butter 0 for the next grocery shopping. 

For scalers, the position carries absolute and intrinsic information. Consider a base-10 number, like 53248, the 5 here means 5*10^4. Whoever is put at the position of this 5 carries the information of “*10^4.” And for boolean values, a stacking of two, such as FalseTrue sabotages the structure of True completely, because True/False only allows the position 0, and any indices other than 0 eradicates the whole value. It turns into nothing with stacking. 

In the real world, you can of course stack integers, but then the action of stacking changes the type of the value, because when position doesn’t meaning anything anymore, the numbers are turned into naive symbols, like phone numbers or passwords. This consequence looks less severe than the stacking of booleans, but it still does something bad. So in the world of computer science, they are treated as non-stackable. It makes things easier.  