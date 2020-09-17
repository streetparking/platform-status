---
layout: post
title:  "Signup Payment Code Logic"
date:   2020-09-16 14:24:13 -0600
categories: documentation

---
What to expect when user is on payment screen of signup and entering a code.

**Promotions**
1. If there's a current promotion that is within date range and not met max redemptions it will prefill the code box and discount appropriate memberships.
a. appropriate memberships is determined by the required memberships set when the promotion was created.
2. if current promotion in box is deleted the membership dropdown will load for a few seconds then reflect full price amounts


**Gift Card**
1. 

2. 

**Coupon Code**
1. 
2. 

**Default Membership Selected**
1. if staff membership is possible it's auto selected

2. if there's a promotion Default membership will be the lowest of required IE monthly would be selected over 6 month if both qualify. 

3. if there's a promotion and the user is military the lowest of promotion will be selected but they will see military as option in dropdown.

4. if coupon code the applicable membership is selected, if multiple available goes with lowest

5. if gift card the lowest available option will be selected.

6. if no codes not military and not staff monthly will be pre selected
