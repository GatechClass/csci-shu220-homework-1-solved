# csci-shu220-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [CSCI-SHU220 Homework 1 Solved](https://mantutor.com/product/csci-shu220-solved-3/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115317&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI-SHU220 Homework 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
This assignment has in total 70 base points and 10 extra points, and the cap is 70. Bonus questions are indicated using the ⋆ mark.

Please specify the following information before submission:

• Your Name: Yufeng Xu

• Your NetID: yx3038

Problem 1: Asymptotic analysis [7+7+7 pts]

(a) Show that n! = ω(n0.99n).

(b) Construct two functions f,g : N → R≥0 such that f(n) = O(g(n)) but neither f(n) = o(g(n)) nor f(n) = Θ(g(n)). Show the correctness of your construction.

(c) Let f(n) = n0.6 and g(n) = 22⌊loglogn⌋. Show that none of the relations Θ, O, Ω, o, ω applies between f(n) and g(n).

Solution. Please write down your solution to Problem 1 here.

(a) want to show n! = ω(n0.99n) ⇐⇒ ∀c &gt; 0,∃n0 &gt; 0 | ∀n &gt; n0,n! &gt; cn0.99n

n

Next, we prove it by showing n! = ω(n 2 ) n! &gt; cnn2 ⇐⇒ log1 + log2 + ··· + logn &gt; logc + n logn where LHS = log1 + log2 +

(b)let ) + 2, take b = 1,n0 = 1,∀n &gt; n0,f(n) ≤ 1 · g(n), sof(n) = O(g(n))

However, f(n) ̸= o(g(n)) and f(n) ̸= Θ(g(n))

(i)If f(n) = o(g(n)), then ∀b &gt; 0,∃n0 &gt; 0 such that ∀n &gt; n0,f(n) &lt; b · g(n)

Take b = 0.1, assume ∃n0 &gt; 0 such that ∀n &gt; n0,f(n) &lt; 0.1 · g(n)

Take ), contradictory to our assumption that f(n) &lt; c · g(n). Therefore, f(n) ̸= o(g(n))

(ii)If f(n) = Θ(g(n)), then ∃a,b &gt; 0 such that ∃n0 &gt; 0,∀n &gt; n0,a · g(n) ≤ f(n) ≤ b · g(n)

Assume such a,b,n0 exist, take 1, therefore f(n) = 0,g(n) = 1 we also know a·g(n) ≤ f(n) ≤ b·g(n), therefore a = 0, contradictory to our essumption that a &gt; 0. Therefore, f(n) ̸= Θ(g(n))

(c)Consider n = 22k,k ∈ N, then

Consider n = 22k−1,k ∈ N, then

(i)Assume f(n) = O(g(n)),∃b,n0 &gt; 0 such that ∀n &gt; n0,f(n) &gt; b · g(n)

However, take k = max{⌈log(logn0 + 1)⌉ + 1,⌈log(10 · logb + 6)⌉ + 1}, take n = 22k−1 &gt; n0, then , which is contradictory to f(n) ≤ b · g(n).

Therefore, f(n) ̸= O(g(n)), hence f(n) ̸= Θ(g(n)),f(n) ̸= o(g(n)).

(ii)Assume f(n) = Ω(g(n)), ∃a,n0 such that ∀n &gt; n0,f(n) ≥ a · g(n).

Take n = 22 &gt; n0, then , which is contradictory to f(n) ≥ a · g(n).

Therefore, f(n) ̸= Ω(g(n)), hence f(n) ̸= ω(g(n)). None of Θ,O,Ω,o,ω apply to f(n) and g(n).

Problem 2: Finding the maximum/minimum [10+10⋆ pts]

For an array A of n different numbers (not necessarily sorted), we want to find the largest number and the smallest number in A simultaneously. However, we have no access to A. Instead, we are given an oracle Compare that can be used to compare the numbers in A. For i ̸= j, Compare(i,j) returns i if A[i] &gt; A[j] and returns j if A[j] &gt; A[i] (recall that the numbers in A are different by assumption, so we cannot have A[i] = A[j] if i ̸= j). For convenience, let us assume n is even.

(a) Design an algorithm which calls the Compare oracle at most 2 times and returns a pair

(imax,imin) such that A[imax] (resp., A[imin]) is the largest (resp., smallest) number in A. Give the pseudocode and briefly justify its correctness.

(b)⋆ Show that any algorithm has to call the Compare oracle 2 times in worst case in order to find the largest and smallest numbers in A.

Solution. Please write down your solution to Problem 2 here. (a) The pseudocode is shown below:

Algorithm 1 pseudocode for problem 2.1

max idx ← compare(0,1) min idx ← 1− max idx i ← 2

while i &lt; len(A) do tmp max ← compare(i,i + 1) tmp min ← 2 · i + 1−tmp max max idx ← compare(tmp max,max idx) min idx ← tmp min+min idx −compare(tmp min,min idx) i ← i + 2

end while return (max idx, min idx)

This algorithm compares the first two elements for 1 time. For every two elements in the next n − 2 elements of the array, the algorithm compares for 3 times. In total, the algorithm compares 2 times.

Moreover, this algorithm is correct, because if we pick the larger number from every two numbers in the sequence, the global maximal number must be among this set. On the other hand, the global minimal number must be among the set of the smaller numbers from every two numbers.

(b) Let A be the set of numbers that are possibly minimum but not maximum, B be the set of numbers that are possibly maximum but not minimum, C be the set of numbers neither possibly minimum nor maximum, D be the set of numbers both possibly minimum and maximum.

Assume the size of the four sets are (nA,nB,nC,nD).Initially, we have (nA,nB,nC,nD) = (0,0,0,n). The ultimate goal is (1,1,n − 2,0). With direct comparison, there are 3 types of meaningful operations(all other operations contribute to this goal less efficiently):

• (nA,nB,nC,nD) → (nA + 1,nB + 1,nC,nD − 2)

• (nA,nB,nC,nD) → (nA − 1,nB,nC + 1,nD)

• (nA,nB,nC,nD) → (nA,nB − 1,nC + 1,nD)

It is not hard to see the second and the third operations must be done n−2 times in total, whereas the first operation should be done times. Therefore, the total number of comparisons is at least

Problem 3: Solving recurrences [4×5+9 pts]

(a) Find big-Θ bounds for the following recurrences (and show your bounds are correct). For the base case, simply assume T(n) = 1 for all n ≤ 2.

(b) Recall the Fibonacci sequence F0,F1,F2,… defined using the recurrence Fn = Fn−1 + Fn−2 with the base case√ F0 = 0 and F1 = 1. Prove by induction that ϕn−2 ≤ Fn &lt; ϕn for all n ≥ 1,

where ϕ = (1 + 5)/2. Based on this, further show that Fn = Θ(ϕn).

Solution. Please write down your solution to Problem 3 here.

(a)(i) Let ), where a = 8,b = 3,f(n) = Θ(n1.5 log4 n)

Because ∀p,q &gt; 0,np = ω(logq n),log3 8 &gt; 1.5, ∃ϵ &gt; 0 such that f(n) = O(nlog38−ϵ)

According to Master theorem, T(n) = Θ(nlog38)

(ii)Assume

(because(

Therefore LHS &gt; 6logn when c ≥ 12.

√ √ p √ √

On the other hand, T(n) − 6logn − T(n − n) = (c n − 6)log(n) − c n − nlog(n − n). Let

√ p √ √

c = 6, we want to show LHS &lt; 0 ⇐⇒ ( n − 1)log(n) − n − nlog(n − n) &lt; 0 ⇐⇒

0. Let 3. There-

√ p √ √

fore, f( n) − f( n − n) &lt; 0 for n &gt; 16, hence T(n) − T(n − n) &lt; 6logn when n &gt; 16. Thus √

T(n) = Θ( nlogn).

(iii)View T(n) as a recursion tree. Assume the tree has k layers in total, the 0th layer has one node; the 1st layer has 2 nodes plus ; the 2nd layer has 4 nodes plus 2 the kth

layer has 2k nodes with value 1, plus , where k = logn

Therefore, . By integral test, ln( ) + 1. Therefore,

). Therefore, T(n) = Θ(nloglogn).

(iv)View T(n) as a recursion tree. Assume the tree has k layers in total, the 0th layer has one node;

√ √

the 1st layer has 5 nodes plus 2n; the 2nd layer has 25nodes plus 5 n · 2 n = 10n… the kth layer has 5 nodes with value 1, plus 2 · 5k−1n, where k = loglogn.

Therefore, , where 5k = 5loglogn = 2log5·loglogn =

, hence 5 ). Therefore,

(b) (i) Check ϕ−2 ≤ F0 &lt; ϕ0,ϕ−1 ≤ F1 &lt; ϕ1.

(ii) Assume for√ 1,2…k, ϕk−2 ≤ Fk &lt; ϕk. Then Fk+1 = Fk +Fk−1 ≥ ϕk−2 +ϕk−3 = ϕk−3 ·(1+ϕ) =

Hence ϕk−1 ≤ Fk+1 &lt; ϕk+1. By induction, ϕn−2 ≤ Fn &lt; ϕn for all n ≥ 1.

(iii) Now we show that Fn = Θ(ϕn). We know Fn = Fn−1 + Fn−2, assume Fn − A · Fn−1 = (1 − A) · (Fn−1 − A · Fn−2), then 1 = −A · (1 − A), A2 − A − 1 = 0, hence or . Hence . We know that F0 = 0,F1 = 1, hence

, where O(ϕn), hence Fn = Θ(ϕn).

Problem 4: Counting intersection points [10 pts]

Solution. Please write down your solution to Problem 4 here. The pseudocode for this problem is shown in the next page.

Algorithm 2 pseudocode for problem 4.1

procedure CountInt(n,A,B)

A sorted ← sorted(A) ▷ sorted is implemented by merge sort, which is O(nlogn) B sorted ← sorted(B) rank ← zeros(n) ▷ zeros(n) returns an array of zeros of length n for i in range(1,n + 1) do rank[B sorted.rank(B[i])] = A sorted.rank(A[i])

▷ rank applies binary search(O(logn)) and returns the rank of the target in a sequence.

end for procedure DivConq(m,arr)

if m ≤ 1 then

return 0,arr

end if

mid ← m/2 m ← len(arr) inv1,arr1 ← DivConq(mid,arr[: mid]) inv2,arr2 ← DivConq(mid,arr[mid :]) inv ← inv1 + inv2 i,j ← 1 res ← emptylist while i ≤ len(arr1) do if arr1[i] &lt; arr2[j] OR j &gt; len(arr2) then res.append(arr1[i])

i ← i + 1 inv ← inv + j − 1

else res.append(arr2[j])

j ← j + 1

end if

end while return inv,arr

end procedure cnt,arr ← DivConq(n,rank) return cnt

end procedure

This algorithm applies merge sort 2 times and binary search 2n times, which is O(nlogn). In DivConq, the sorting of arr1 and arr2, two sorted arrays, is O(n). In total, the time complexity of DivConq is O(nlogn). Therefore, the time complexity of the whole algorithm is O(nlogn). Next, we will show the correctness of this algorithm.

We know if ai &lt; aj,bi &gt; bj, then there’s an intersection between aibi and ajbj. In other words, the task of counting intersection is equivalent to counting inversed pairs. # inversed pairs in a sequence is equivalent to # inversed pairs within its left part and right part, plus # inversed pairs across the two parts, i.e., for each entry x in the left part, how many entries in the right part are smaller than x. By sorting arr1 and arr2, this algorithm keeps the returned array sorted and counts how many inversed pairs are there across the left and the right part.
