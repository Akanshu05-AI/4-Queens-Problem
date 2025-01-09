# 4-Queens-Problem



Step 1:
1) Put our first Queen (Q1) in the (0,0) cell .
2) 'A' represents the cells which is not safe i.e. they are in the way of the Queen (Q1).
3) After this move to the next row [0 -> 1].


Step 2:
1) Put our next Queen (Q2) in the (1,2) cell .
2) After this move to the next row [1 -> 2].


Step 3:
1) At row 2 there is no cell where we can put the Queen (Q3) .
2) So, backtrack and remove queen Q2 queen from cell ( 1, 2 ) .


Step 4:
1) There is still a safe cell in the row 1 i.e. cell ( 1, 3 ).
2) Put Queen ( Q2 ) at cell ( 1, 3).


Step 5:
1) Put queen ( Q3 ) at cell ( 2, 1 ).


Step 6:
1) There is no any cell to place Queen ( Q4 ) at row 3.
2) Backtrack and remove Queen ( Q3 ) from row 2.
3) Again there is no other safe cell in row 2, So backtrack again and remove queen ( Q2 ) from row 1.
4) Queen ( Q1 ) will be remove from cell (0,0) and move to next safe cell i.e. (0 , 1).


Step 7:
1) Place Queen Q1 at cell (0 , 1), and move to next row.


Step 8:
1) Place Queen Q2 at cell (1 , 3), and move to next row.


Step 9:
1) Place Queen Q3 at cell (2 , 0), and move to next row.


Step 10:
1) Place Queen Q4 at cell (3 , 2), and move to next row.


This is one possible configuration of solution
