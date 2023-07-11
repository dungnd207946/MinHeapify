HEAPIFY PSEUDO CODE

MIN_HEAPIFY(A,i)
l = left(i)
r = right(i)
if l<=A.heapSize and A[l] < A[i] 
	min = l
else min = i
if r<=A.heapSize and A[r] < A[min]
	min = r
if min != i
	exchange A[i] with A[min]
	MIN_HEPIFY(A,min)



Time complexity in worst case: O(logn)