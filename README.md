# UC_Optimizer_algorithm
## Optimizers algorithms  (Hungarian and Vickrey Auction)

## Munkres implementation for Python
Let C be an n by n matrix representing the costs of each of n workers to perform any of n jobs.
The assignment problem is to assign jobs to workers in a way that minimizes the total cost. 
Since each worker can perform only one job and each job can be assigned to only one worker 
the assignments represent an independent set of the matrix C.

One way to generate the optimal set is to create all permutations of the indexes necessary 
to traverse the matrix so that no row and column are used more than once.

http://software.clapper.org/munkres/

#### Non-square Cost Matrices
The Munkres algorithm assumes that the cost matrix is square. However, it’s possible to use
a rectangular matrix if you first pad it with 0 values to make it square. 
This module automatically pads rectangular cost matrices to make them square.

Notes:
The module operates on a copy of the caller’s matrix, so any padding will not be
seen by the caller. The cost matrix must be rectangular or square. 
An irregular matrix will not work.

## Vickrey Auction

Vickrey auctions are a type of sealed-bid auction where all participants bid for the lot 
at the same time without knowing how their competitors are bidding. As a result, 
the winner of the auction is the bidder with the highest bid. 
However, the winner does not pay the highest bid, but the second-highest bid amount. 
This type of auction encourages the participants to bid exactly how much they value 
the good being sold.

https://corporatefinanceinstitute.com/resources/knowledge/other/vickrey-auction/

http://www.masfoundations.org/mas.pdf

MRobalinho : 4-12-2020
