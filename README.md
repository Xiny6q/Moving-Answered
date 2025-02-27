Download link :https://programming.engineering/product/moving-answered/

# Moving-Answered
Moving Answered
Congratulations! You just landed a job for the summer! Now you have to gure out how to move all your stu out there. You’ve now packed up all your belongings into cardboard boxes, and need to move them to your new home. We’ll assume, for the sake of argument, that all the boxes are the same weight and dimensions { you’re that good of a packer. You can bring a certain number of things with you in your car (or on the plane), but the rest must be shipped to your destination. In particular, you must

take exactly a given number of items with you, for reasons we won’t get into here.

There are various companies that will help you move your items. Each one o ers the same two services:

For a given cost, x, you can have one item shipped to your nal location.

For a given (but probably di erent) cost, y, you can have half of your items shipped to your location. The company will always round favor of shipping more boxes (i.e., if you have 7 items, this will ship 4 of them for you).

Not surprisingly, you cannot have less than 0 items to ship. The goal is to gure out how much each agency will cost to ship all your items, and list them in sorted order.

Input

The rst line of the input will contain a single number which is the number of test cases in the input. The test cases follow immediately.

The rst line in each test case will contain three numbers: the number of boxes you have to move, how many you must take with you (and thus do not need to ship), and the number of available shipping companies, in that order. We will designate these numbers as b, m, and c. You can assume that m b.

Each of the following c lines will contain the information for one of the moving companies. Each line will contain, space separated, the following values: the company name, their charge x for the rst service (moving one box), and their charge y for the second service (moving half of the boxes). The names will be strings that contain only capital letters { no spaces, numbers, or punctuation { and are at most 16 characters in length.

All numeric values will be non-negative integers, and all will be less than 216.

Output

For each test case, your output should start with the line \Case #”, where ’#’ is the case number, starting from 1.

Each case will contain c additional output lines, one for each agency. Each line should list the agency name, a single space, and the minimum cost of using that company. The list should be sorted by cost (increasing); ties are resolved by the normal alphabetical sorting of the company names.

All numeric output values will be less than 231.

Sample Input

Sample Output

2

Case 1

75 10

6

UHAUL 12

DHL53

USPS 28

UPS99

COURIER 30

USPS 3 2

FEDEX 34

FEDEX 3

5

DHL 46

COURIER

2

7

UPS 90

UHAUL 1

2

Case 2

2246 2245

5

UNITED 0

AMERICAN 100 600

DELTA 2

USAIR 2

2000

USAIR 2

SOUTHWEST 20 20

SOUTHWEST 20

DELTA 2

100

AMERICAN 100

UNITED 0 0

