# Assignment

Here we have m homeless & n houses and we have to assign them houses according to the capacity of the houses.
There is a weight matrix assigned through which we have to find the minimum sum of weights.

Let H be the set of homeless people, S be the set of houses, C be the set of capacity & W be the weight matrix.
Let H={h1,h2} & S={s1,s2}.
Let us consider the capaticy of the house as C={1,1}.

CASE 1:
The W={[8,4] , [10,3]}
A={a12,a21} (h1->s2,h2->s1)
Minimum sum of weights = 11, But the maximum weight in the set is 10. Means h1 was given a much better housing provider at the expense of h2.

CASE 2:
The W={[7,3] , [11,2]}
A={a12,a21} (h1->s2,h2->s1)
Minimum sum of weights = 9, But the maximum weight in the set is 11. Means h2 was given a much better housing provider at the expense of h1.

CASE 3:
The W={[5,6] , [8,3]}
A={a12,a21} (h1->s2,h2->s1)
Minimum sum of weights = 8, But the maximum weight in the set is 8. Means h1 & h2 both were given equal housing provider at equal expenses.
