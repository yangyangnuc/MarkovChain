# MarkovChain
## Markov Property
Markov property refers to a memoryless stochastic process{X(t),t ∈T}, 
that future states only depend on current states, not on the states preceded it. 
It is usually be formualted in conditional probalibity form as 
P{Xn=xn|X<sub>0</sub>=x<sub>0</sub>, X<sub>1</sub>=x<sub>1</sub>, X<sub>2</sub>
=x<sub>2</sub>, ... , X<sub>n-1</sub> = x<sub>n-1</sub>} = P{X<sub>n</sub>=x<sub>n</sub>
|X<sub>n-1</sub> = x<sub>n-1</sub>};

### Conclusion1 
Given process with independent increments {X(t),t≥0}, and X(0) = 0,  
then {X(t),t≥0} is Markov process.
### Conclusion2  
Poisson process is time-continuous and state-discrete markov process;  
Wiener process is time and state continuous markov process;  
Poisson and Wiener is special cases of independent incremental process;

### Definition of Markov chain  
Both time and state discrete process is called Markov chain, which could be marked with  
{X<sub>n</sub> = X(n), n=0,1,2...},  
its time set is  
T<sub>1</sub>={0,1,2...};  
its state set is  
I={a1,a2,...};  
Markov property of Markov chain is usually in conditional probability marked as  
P<sub>ij</sub>(m,m+n) = P{X<sub>m+n</sub>=a<sub>j</sub>|X<sub>m</sub>=a<sub>i</sub>}  
, it shows transition probability from current time m and current state a<sub>i</sub> to a<sub>j</sub> at time (m+n), Where a<sub>i</sub> ∈I;  

