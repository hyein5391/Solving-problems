22/10/19
#문제1
Number = 5
1 2 3 4 5
6 7 8 9 10
11 12 13 14 15
16 17 18 19 20
21 22 23 24 25

#풀이 정답
l = int(input('숫자를 입력하세요'))
for i in range(l):
    for j in range(1, l+1):

        print( (5*i) + j , end=" " )

    print("")


#문제2
 number = 5
 21 22 23 24 25
 16 17 18 19 20
 11 12 13 14 15
 6 7 8 9 10
 1 2 3 4 5
 
 #풀이 정답
l = int(input('숫자를 입력하세요'))
for i in range(l):
    for j in range(21, 25+1):
        print( (-5*i) + j , end=" " )
    print("")

#문제3
 number = 5
 1 3 5 7 9
 11 13 15 17 19
 21 23 25 27 29
 31 33 35 37 39
 41 43 45 47 49 

 #풀이 정답
 
