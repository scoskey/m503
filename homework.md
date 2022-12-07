---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 403/503 homework

[Submit with gradescope](https://www.gradescope.com/courses/413854)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 15

### Take-home Quiz 2

**Instructions** (a) You may not consult with any other person. Your work must be *completely your own*. (b) You may refer to class notes and materials freely. (c) If you use any outside resources, please provide citations. (d) To receive full credit, use only the methods *we learned in our class*. (e) To receive full credit, please show all work. 

1. Please copy the following paragraph, and sign your name below it: "My solutions are my own original work. I completed the exam without the use of any other person as a resource. I followed Boise State University's policies on academic integrity."
2. Let $V,W$ be finite dimensional inner product spaces, and $T\in L(V,W)$. Assume $(T^\ast T)^{-1}$ exists (this is just so we can write it in the next sentence). Show that for any $v\in V$ and $w\in W$, $Tv$ is orthogonal to $T(T^\ast T)^{-1}T^\ast w-w$.
3. Consider the basis of $R^3$ given by $(1,2,3),(0,2,3),(0,0,3)$. Use Gram-Schmidt to orthonormalize the basis. (You may use software to assist with evaluation, but show the steps.)
4. Consider the matrix $A=\begin{bmatrix}2&3-3i\\\\3+3i&5\end{bmatrix}$. Find an orthonormal basis which diagonalizes $A$, and do so. (Show all the work.)
5. Find an example of a matrix with complex entries which is symmetric but not normal, and show this is the case.
6. Suppose $A$ is a $2\times2$ matrix with trace $3$ and determinant $5$. Show how to use this information to find the eigenvalues of $A$, and do so.
7. Let $A=\begin{bmatrix}a&b\\\\b&d\end{bmatrix}$ be a real-valued symmetric matrix. Show that if $a\geq0$ and $\det(A)\geq0$, then $A$ is positive. [Hint: start with your work from H14#1 and make it general.]

The following problems are to be completed by Math 503 students only.

8. (#8) Consider the basis $1,x,x^2$ of real quadratic polynomials on $[0,1]$. Use Gram-Schmidt to orthonormalize the basis with respect to the inner product $\langle f,g\rangle=\int fg$. Then use the method of projecting to the span of an ONB to find the quadratic polynomial that best fits the function $f(x)=e^{-x}$ on $[0,1]$. (You may use software for evaluation only. You may work with decimals.)
9. (#9) Let $T$ be a finite dimensional inner product space, and $T\in L(V)$. Show that $T^\ast T+I$ is invertible. [Hint: Argue the eigenvalues are real and positive.]

## Week 14

### U14 (Due Tuesday, December 6)

1. For each property of the trace, explain why it is true or provide a counterexample. (a) $\mathrm{trace}(ST)=\mathrm{trace}(S)\mathrm{trace}(T)$; (b) $\mathrm{trace}(\alpha T)=\alpha\mathrm{trace}(T)$; (c) $\mathrm{trace}(RST)=\mathrm{trace}(RTS)$; (d) $\mathrm{trace}(RST)=\mathrm{trace}(TSR)$
2. For each property of the determinant, explain why it is true or provide a counterexample. (a) $\det(ST)=\det(TS)$; (b) $\det(S+T)=\det(S)+\det(T)$; (c) $\det(T^\ast)=\overline{\det(T)}$; (d) $\det(\alpha T)=\alpha\det(T)$

### H14 (Due Wednesday, December 7)

1. Which values of $b$ make the matrix $\begin{bmatrix}1&b\\\\b&9\end{bmatrix}$ positive?
2. Show that if $T$ is any operator then $T^\ast T$ is positive.
3. Suppose $T$ is a positive operator on $C^n$. Show that if $\mathrm{trace}(T)=0$, then $T$ is the zero operator.
4. Let $U$ be a proper subspace of $V$ and $P_U$  the orthogonal projection onto $U$. Show that $\det(P_U)=0$.
5. Let $Q$ be orthonormal ($Q$ has orthonormal columns with respect to some orthonormal basis; better called unitary or isometry). Show that $\|\det(Q)\|=1$.

## Week 13

### U13 (Due Tuesday, November 29)

1. Show that the matrix is normal. Then find its eigenvalues and eigenvectors, and show the eigenvectors are orthogonal. $\begin{bmatrix}0&-1+i\\\\1+i&i\end{bmatrix}$
2. Show that if $P$ is any orthogonal projection matrix, then $P$ is positive, that is, $\langle Pv,v\rangle\geq0$ for all $v$.

### 13 (Due Wednesday, November 30)

1. (Treil 5.3) Show that the null space of $T^\ast T$ is equal to the null space of $T$. [Hint from the book: for one inclusion, use the fact that $\|v\|^2=\langle Tv,Tv\rangle=\langle T^\ast Tv,v\rangle$.]
2. (See Treil 6.1) Observe the matrix is symmetric. Find its eigenvalues and eigenvectors, and show the eigenvectors are orthogonal. $\begin{bmatrix}&2&2\\\\2&&2\\\\2&2\end{bmatrix}$.
3. (Short homework this holiday week)

## Week 12

### U12 (Due Tuesday, November 15)

1. Look at the list of properties of the projection $P_U$ in 6.55. Let $Q=I-P_U$. Show that $Q$ satisfies $Q^2=Q$ (property g). Show that $\mathrm{range}(Q)=U^\perp$ and $\mathrm{null}(Q)=U$ (reverse of properties d,e). Finally show that in fact $Q=P_{U^\perp}$ (which also helps explain the above).
2. - skipped -

### H12 (Due Wednesday, November 16)

1. Recall you used Gram-Schmidt on the basis $(1,1,2),(1,-1,0),(1,0,4)$. Now find the matrix of the projection map $P\_U$ onto the subspace spanned by $(1,1,2),(1,-1,0)$. [Hint: in the ONB you found, $P\_U$ is just $\begin{bmatrix}1\\\\&1\\\\&&0\end{bmatrix}$. Convert this back to the standard basis.]
2. Let $P_U$ be the orthogonal projection onto $U$. Show that $\langle P\_Uv,w\rangle=\langle v,P\_Uw\rangle$ for all vectors $v,w$. [Hint: show that both sides are equal to $\langle P\_Uv,P\_Uw\rangle$.]
3. Complete example 6.58 but without relying on decimal numbers. You may use integration software such as symbolab.
4. Show that the eigenvalues of $T^\ast$ are precisely the conjugates of the eigenvalues of $T$.
5. (Axler, 7A.4) Show that $T$ is injecive if and only if $T^\ast$ is surjective.

## Week 11

### U11 (Due Tuesday, November 8)

1. Prove the following identity, which shows that you can recover the inner product from the norm: $\langle u,v\rangle=\frac14(\|u+v\|^2-\|u-v\|^2+i\|u+iv\|^2-i\|u-iv\|^2)$. 
2. Let $V$ be an inner product space with basis $v\_1,\ldots,v\_n$, and use the Gram-Schmidt process to produce an orthonormal basis $e\_1,\ldots,e\_n$. Let $A$ be the matrix with columns $v\_i$ and let $Q$ be the matrix with columns $e\_i$. Show that $A=QR$ where $R$ is upper triangular.

### H11 (Due Wednesday, November 9)

1. Let $V$ be an inner product space with basis $v_1,\ldots,v_n$. Prove that if $\langle u,v_i\rangle=0$ for all $i$, then $u=0$.
2. (Axler, 6A.8) Suppose that $\|u\|=\|v\|=1$ and $\langle u,v\rangle=1$. Prove that $u=v$.
3. Use the Gram-Schmidt procedure to find an orthonormal list from the list $(1,3,4,5,7),(-6,6,8,0,8)$. Find the vector closest to $u=(1,0,0,0,0)$ which lies in the plane spanned by $(1,3,4,5,7),(-6,6,8,0,8)$.
4. Use the Gram-Schmidt procedure to find an orthonormal basis from the following basis: $(1,1,2),(1,-1,0),(1,0,4)$.
5. Let $V$ be the space of continuous real-valued functions on $[-1,1]$ with inner product $\langle f,g\rangle=\int\_{-1}^1fg$. Show that the union of the two lists is orthonormal: $\sin(n\pi x)$ for $n\geq1$, and $\cos(n\pi x)$ for $n\geq 1$.

## Week 10

### Take-home Quiz 2

**Instructions** (a) You may not consult with any other person. Your work must be *completely your own*. (b) You may refer to class notes and materials freely. (c) If you use any outside resources, please provide citations. (d) To receive full credit, use only the methods *we learned in our class*. (e) To receive full credit, please show all work. 

1. Please copy the following, and sign your name: "My solutions are my own original work. I completed the exam without the use of any other person as a resource. I followed Boise State University's policies on academic integrity."
2. Consider the linear map on the vector space of all polynomials over $F$ defined by $Tp(z)=(3z+5)p^\prime(z)$. Decide whether $T$ is injective, decide whether $T$ is surjective, and prove your answers.
3. For each of the following set of requirements, give an example of a linear map $T\in L(C^4,C^5)$ with the properties or else show it is not possible.  
  * The null space of $T$ is $2$-dimensional, the range of $T$ is $2$-dimensional, the null space of $T'$ is $2$-dimensional, and the range of $T'$ is $2$-dimensional
  * The null space of $T$ is $0$-dimensional, the range of $T$ is $4$-dimensional, the null space of $T'$ is $1$-dimensional, and the range of $T'$ is $4$-dimensional.
4. Suppose that the eigenvalues of $T$ are $\lambda=1,2,3$. What are the eigenvalues of $T+4I$? Prove your answer.
5. Consider the matrix $A$ below. Find a basis in which $A$ is diagonal and use this information to write $A=UDU^{-1}$ where $D$ is diagonal. Then use the fact that $A^n=UD^nU^{-1}$ to calculate $A^{100}$ explicitly.  
  $A=\begin{bmatrix}5&3\\\\-6&-4\end{bmatrix}$.
6. Give an example of an operator $T\in L(C^7,C^7)$ such that $G(3,T)=C^7$, $\mathrm{null}(T-3I)$ is $3$-dimensional, $\mathrm{null}(T-3I)^2$ is $5$-dimensional, and $\mathrm{null}(T-3I)^3$ is $6$-dimensional. Show how you got your example.
7. Consider the matrix $A$ below. The eigenvalues are $\lambda=1,2$. Find a Jordan basis and the Jordan form of $A$.  
  $A=\begin{bmatrix}-1&1&0&0\\\\-4&3&0&0\\\\-5&2&0&1\\\\-6&3&-4&4\end{bmatrix}$.

The following problems are to be completed by Math 503 students only.

8. (#8) Let $V=P^3(F)$ be the space of polynomials of degree at most $3$. Let $V'$ be the dual space of $V$. Consider the basis $\phi\_0,\phi\_1,\phi\_2,\phi\_3$ of $V'$ defined as follows:  
  $\phi\_0(p)=p(0),\quad\phi\_1(p)=p^\prime(0)+p(0),\quad\phi\_2(p)=p^{\prime\prime}(0)+p^{\prime}(0)+p(0),$  
  $\quad\phi\_3(p)=p^{\prime\prime\prime}(0)+p^{\prime\prime}(0)+p^\prime(0)+p(0)$  
  Find a basis $p\_0,p\_1,p\_2,p\_3$ of $V$ such that the dual basis of $p\_0,p\_1,p\_2,p\_3$ is exactly $\phi\_0,\phi\_1,\phi\_2,\phi\_3$.
9. (#9) Suppose that $V$ is $n$-dimensional over $C$, and $T\in L(V,V)$. If $T^3=0$, prove that the rank of $T$ is at most $2n/3$. [Hint: Consider the Jordan form of $T$.]

## Week 9

### U9 (Due Tuesday, October 25)

1. Read the statements and proofs of the results 8.2, 8.3, 8.4, and 8.5 in the text. Show they are true in the case of the matrix below by calculating the null space of $T$, $T^2$, $T^3$, and $T^4$, and the range of $T^4$.  
   $T=\begin{bmatrix}1&2&3&4\\\\0&0&2&4\\\\0&0&0&5\\\\0&0&0&0\end{bmatrix}$
2. Suppose that $T$ is an operator on $V$, suppose $U,W$ are nonzero $T$-invariant subspaces, and finally suppose $V=U\oplus W$. Show that there exists a basis of $V$ such that the matrix of $T$ with respect to the basis has the block form:  
  $A=\begin{bmatrix}A\_1\\\\&A_2\end{bmatrix}$

### H9 (Due Wednesday, October 26)

1. Find all generalized eigenspaces of the matrix below. [Hint: $\lambda=1$]  
  $A=\begin{bmatrix}1&-24&-96\\\\0&21&80\\\\0&-5&-19\end{bmatrix}$ 
2. Find all generalized eigenspaces of the matrix below. [Hint: $\lambda=1,2$]  
  $A=\begin{bmatrix}2&1&0&0\\\\-1&0&0&0\\\\2&2&3&1\\\\-1&-1&-1&1\end{bmatrix}$ 
3. Suppose that $T$ is in $L(C^3,C^3)$ and $T$ has eigenvalues $\lambda=1,2,3$. Prove that there exists $(x,y,z)$ such that $T(x,y,z)=(1+4x,1+4y,1+4z)$.
4. Show that the following matrices are conjugate by finding a change of basis matrix $U$ such that $B=UAU^{-1}$.  
  $A=\begin{bmatrix}2&1\\\\&2&1\\\\&&2\end{bmatrix}$, $B=\begin{bmatrix}2\\\\1&2\\\\&1&2\end{bmatrix}$.
5. This extends the previous problem 5. Give examples of three $3\times3$ matrices $A\_1,A\_2,A\_3$ such that: (1) For each $i$, $A\_i$ has just one eigenvalue and it's $0$, and; (2) If $i\neq j$ then $T\_i$ and $T\_j$ are not conjugate.

## Week 8

### U8 (Due Tuesday, October 18)

1. Let $S(x,y)=(x+2y,3y)$. Find a basis in which $S$ is diagonal and verify this is the case. Let $T(x,y)=(x+2y,y)$. Show that there does not exist a basis in which $T$ is diagonal.
2. Suppose that $T$ is diagonalizable. Prove that $V$ is equal to the direct sum of the null space of $T$ and the range of $T$.

### H8 (Due Wednesday, October 19)

1. Show that if $\lambda$ is an eigenvalue of $T$ then $\lambda^k$ is an eigenvalue of $T^k$. If $T$ is invertible, show this statement applies to negative values of $k$ too.
2. Consider the transformation $T$ with matrix $$\begin{bmatrix}4&3\\\\1&2\end{bmatrix}$$ in the standard basis. Find a basis in which $T$ is upper triangular but not diagonal. Find a basis in which $T$ is diagonal.
3. Give an example of a $2\times2$ matrix $A$ with real entries satisfying each condition, or show it isn't possible:
  * $A$ has no eigenvalues (real or complex)
  * $A$ has one real eigenvalue and no other eigenvalues
  * $A$ has one complex (non-real) eigenvalue and no other eigenvalues
  * $A$ has two real eigenvalues
  * $A$ has two complex (non-real) eigenvalues
  * $A$ has one real eigenvalue and one complex (non-real) eigenvalue
4. Suppose that $S$ and $T$ are operators, and there exists an invertible operator $U$ such that $SU=UT$. Prove that $S$ and $T$ have the same eigenvalues.
5. Give an example of operators $S,T$ such that $S$ and $T$ have the same eigenvalues, and there is no invertible operator $U$ such that $SU=UT$.

## Week 7

### U7 (Due Tuesday, October 11)

1. Define $T\in L(F^2)$ by $T(w,z)=(w-3z,w)$. Find the eigenvalues of $T$, first assuming $F=R$ and then assuming $F=C$.
2. Let $T\in L(V)$, and let $v\_1,\ldots,v\_n$ be a basis of $V$ with the additional property that every $v\_i$ is an eigenvector of $T$. Describe the matrix of $T$ in the basis $v\_1,\ldots,v\_n$.

### H7 (Due Wednesday, October 12)

1. Please read Chapter 4. For each condition, give an example of a cubic polynomial with real coefficients satisfying the condition, or state is impossible. In either case, explain your answer. (a) $p(x)$ has $3$ real roots; (b) $p(x)$ has $2$ real roots and one non-real root; (c) $p(x)$ has $1$ real root and $2$ complex roots; (d) $p(x)$ has $3$ non-real roots.
2. Let $p(x)=3x^3-5x^2+10x-3$ and $s(x)=3x+1$. Perform polynomial long division to express $p=sq+r$ where $\mathrm{deg}(r)<\mathrm{deg}(s)$.
3. For each eigenvalue found in U7#1, find a corresponding eigenvector.
4. Suppose $T^k$ is equal to the zero map for some $k$. Prove that $0$ is an eigenvalue of $T$, and that it is the only eigenvalue of $T$.
5. Let $V$ be a finite dimensional vector space, $V'$ its dual, and $V''$ its second dual. Let $T\colon V\to V''$ be the map defined by $T(v)(\phi)=\phi(v)$. (a) Spend some time understanding this formula and then explain why $T$ is a map from $V$ to $V''$. (b) Prove that $T$ is injective (you may assume $T$ is linear). (c) Conclude $T$ is an isomorphism between $V$ and $V''$.

## Week 6

### U6 (Due Tuesday, October 4)

1. Let $A$ be the $2\times 2$ matrix $\begin{bmatrix}a&b\\\\c&d\end{bmatrix}$, so that $A$ may be identified with an element of $L(F^2,F^2)$ in the standard basis. Show that $A$ is an automorphism of $F^2$ if and only if $ad-bc\neq0$.
2. Let $V$ be a vector space and $v,w\in V$. Show that if $\phi(v)=0$ for all $\phi\in V'$, then $v=0$. Show that if $\phi(v)=\phi(w)$ for all $\phi\in V'$, then $v=w$.

### H6 (Due Wednesday, October 5)

1. Find the inverse of the following linear maps in $L(F^3,F^3)$: $S(x,y,z)=(y,z,x)$, $T(x,y,z)=(x+z,y,z)$.
2. Give an example of bijective (invertible) maps $S,T$ such that $S+T$ is not bijective. Give an example of non-bijective maps $S,T$ such that $S+T$ is bijective. (You may work with $2\times2$ matrices.)
3. Give an example of non-bijective maps $S,T$ such that $ST$ is bijective. (You may work with matrices. By the result of the next exercise, you shouldn't try square matrices.)
4. Assume $V$ is a finite dimensional vector space. Show that if $S,T\in L(V,V)$ and $ST$ is bijective (invertible), then both $S$ and $T$ are bijective (invertible).
5. Let $V$ be a vector space, $v\_1,\ldots,v\_n$ a basis of $V$, and $T\in L(V,V)$. Prove that $T$ is bijective (invertible) if and only if $Tv\_1,\ldots,Tv\_n$ is a basis of $V$.

## Week 5

### Take-home Quiz 1

**Instructions** (a) You may not consult with any other person. Your work must be *completely your own*. (b) You may refer to class notes and materials freely. (c) If you use any outside resources, please provide citations. (d) To receive full credit, use only the methods *we learned in our class*. (e) To receive full credit, please show all work. 

1. Please copy the following, and sign your name: "My solutions are my own original work. I completed the exam without the use of any other person as a resource. I followed Boise State University's policies on academic integrity."
2. Consider the vectors $u=(1+i,-2+i)$ and $v=(5-i,-1+8i)$ in $C^2$. Decide whether $v$ is a scalar multiple of $u$. Explain your answer.
3. Let $V$ be the vector space $F^N$ (aka $F^\infty$, see 1.22) consisting of all sequences $(z_n)$. Let $W$ be the subset of $V$ consisting of all sequences satisfying $z_{n+2}=z_{n+1}+z_n$ for all $n$. Show that $W$ is a subspace of $V$.
4. Let $V=F^5$ and let $U$ be the subspace $U=\set{(x_1,x_2,x_3,x_4,x_5):x_1+x_2+x_4=0,x_2+x_3+x_5=0}$. Find a basis of $U$. Then extend it to a basis of $V$.
5. Let $V=F^3$. Let $v_1=(a,0,0),v_2=(b,c,0),v_3=(d,e,f)$ where $a,b,c,d,e,f$ are unknown constants. For what values of the constants $a,b,c,d,e,f$ is it true that $v_1,v_2,v_3$ is linearly independent? Explain your answer.
6. Let $V=F^2$ and let $T\in L(V,V)$ be a linear map with the special property that the null space of $T$ is exactly equal to the range of $T$. Show that the null space of $T$ is one-dimensional. Show that $T^2=0$ (in other words, $T\circ T$ is the zero map). Give an example of a linear map $T$ with this special property (you may answer with a $2\times2$ matrix).
7. Let $T\in L(V,W)$. Show that there exist bases $v_1,\ldots,v_n$ of $V$ and $w_1,\ldots,w_m$ of $W$ such that the matrix of $T$ with respect to the $v$'s and $w$'s consists entirely of $1$'s and $0$'s.

The following problems are to be completed by Math 503 students only.

8. (#8) Suppose that $V$ is a vector space and $v_1,\ldots,v_n$ is a basis of $V$. Let $u$ be any vector and let $U$ be the span of the vectors $v_1-u,\ldots,v_n-u$. Show that the dimension of $U$ is at least $n-1$.
9. (#9) Suppose that $T\in L(U,V)$ and $S\in L(V,W)$. Show that $\mathrm{rank}(ST)\leq\min\set{\mathrm{rank}(S),\mathrm{rank}(T)}$. Give an example of linear transformations $S,T$ such that $\mathrm{rank}(ST)\lt\min\set{\mathrm{rank}(S),\mathrm{rank}(T)}$.

## Week 4

### U4 (Due Tuesday, September 20)

1. Suppose that $Tv=w$. Show that $T^{-1}(w)=v+\mathrm{null}(T)$. In other words, show that the set of vectors $u$ such that $Tu=w$ is equal to the set of vectors of the form $v+x$ where $x\in\mathrm{null}(T)$.
2. Let $V$ be a vector space and let $v\_1,\ldots,v\_n$ and $w\_1,\ldots,w\_n$ be two bases of $V$. Thus every vector $u$ has a $v$-representation $a\_1v\_1+\cdots+a\_nv\_n$ and a $w$-representation $b\_1w\_1+\cdots+b\_nw\_n$. Show that there exists a matrix $A$ which carries $w$-representations to $v$-representations, that is:  
  $A\begin{bmatrix}b\_1\\\\\vdots\\\\b\_n\end{bmatrix}=\begin{bmatrix}a\_1\\\\\vdots\\\\a\_n\end{bmatrix}$  
  [Hint: Consider the linear transformation $S$ such that $S(v\_i)=w\_i$ for all $i$, and let $A$ be the matrix of $S$ in the basis $v\_1,\ldots,v\_n$.]

### H4 (Due Wednesday, September 21)

1. Find the null space and range of the linear transformation $T(x,y)=(x+iy,ix-y)$.
2. For $T\in L(V,W)$, the symbol $\mathrm{rank}(T)$ denotes the dimension of the range of $T$. Prove that $\mathrm{rank}(T)\leq\min(\mathrm{dim}(V),\mathrm{dim}(W))$.
3. Suppose that $T\in L(F^9,F^9)$ with the property that the range of $T$ is contained in the null space of $T$. Show that the dimension of the range of $T$ is at most $4$. Can the range of $T$ be equal to the null space of $T$?
4. Let $V$ be the vector space of polynomials of degree at most $4$. Use the "standard" basis of $V$. Find a matrix of the derivative map. Find a matrix of the differential operator $Tp(x)=-4p''(x)+3p'(x)+2p(x)$.
5. Suppose that $V$ is a vector space and $T\in L(V,V)$. Let $M$ and $N$ be matrices for $T$ with respect to two different bases. Show that there exists a matrix $A$ such that $MA=AN$. [Hint: Use the same type of matrix described in the U-Pruv.]

## Week 3

### U3 (Due Tuesday, September 13)

1. Suppose that $V=U\_1+U\_2$. Show that $V=U\_1\oplus U\_2$ if and only if $\dim(V)=\dim(U\_1)+\dim(U\_2)$.
2. Show that if $S,T$ are linear transformations then $ST$ is a linear transformation. Show that $S(T\_1+T\_2)=ST\_1+ST\_2$. (Assume all the compositions make sense.)

### H3 (Due Wednesday, Septemmber 14)

1. Suppose that $V=U\_1+U\_2+U\_3$. Show that $V=U\_1\oplus U\_2\oplus U\_3$ if and only if $\dim(V)=\dim(U\_1)+\dim(U\_2)+\dim(U\_3)$.
2. Consider the space $V$ of polynomials of degree at most $4$. Let $v\_0,\ldots,v\_4$ be a list of polynomials with the property that for all $i$, the degree of $v\_i$ is equal to $i$. Show that $v\_0,\ldots,v\_4$ is a basis of $V$.
3. (Similar to 3.A.4) Let $T\in L(V,W)$. Show that if $Tv\_1,\ldots,Tv\_m$ is a linearly independent list in $W$, then $v\_1,\ldots,v\_m$ is a linearly independent list in $V$. Decide whether the converse true or false, and explain why.
4. Let $V$ be a two-dimensional vector space with basis $v\_1,v\_2$. Find the dimension and a basis for $L(V,V)$.

## Week 2

### U2 (Due Tuesday, September 6)

1. For each of the following vector spaces $V$, find a list of vectors that spans $V$. Try to include as few vectors in your list as you can. In each case explain why you are correct.  
  * $V=F^3$
  * $V=$ the plane in $F^3$ with equation $x+y+z=0$.
  * $V=$ the set of polynomials of degree $\leq3$
  * $V=$ the set of polynomials of degree $\leq3$ such that $p'(1)=0$.
2. Suppose that $u\_1,\ldots,u\_m,w\_1,\ldots,w\_n$ is linearly independent, let $U$ be the span of $u\_1,\ldots,u\_m$ and $W$ the span of $w\_1,\ldots,w\_n$. Show that the sum $U+W$ is direct. Show that an analogous statement is true if a linearly independent list is divided into three parts.

### H2 (Due Wednesday, September 7)

1. Linear independence means no redundancy: Let $v\_1,\ldots,v\_m$ be a list of vectors in a vector space $V$. Prove that $v\_1,\ldots,v\_m$ is linearly independent if and only if none of the vectors $v\_j$ can be written as a linear combination of the other vectors in the list.
2. (Treil 2.5) Suppose $v\_1,\ldots,v\_k$ is linearly independent, and let $v\_{k+1}$ be any vector not in the span of $v\_1,\ldots,v\_k$. Show that $v\_1,\ldots,v\_{k+1}$ is linearly independent.
3. (Treil 2.6) Is it possible for vectors $u,v,w$ to be linearly dependent while the vectors $u+v,v+w,w+u$ are linearly independent? Give an example or show none exists.
4. (Similar to 2.B.A) Let $U$ be the subspace of $F^5$ defined by $U=\set{(x\_1,x\_2,x\_3,x\_4,x\_5):x\_1=2x\_2,x\_3=5x\_4}$.  
  (a) Find a basis of $U$.  
  (b) Extend the basis from (a) to a basis of $F^5$.  
  (c) Use (b) to describe a subspace $W$ such that $U\oplus W=F^5$.
5. (Similar to 2.B.6) Suppose $v\_1,v\_2,v\_3,v\_4$ is a basis of $V$. Prove that $v\_1+v\_2+v\_3+v\_4,v\_2+v\_3+v\_4,v\_3+v\_4,v\_4$ is a basis of $V$. [Hint: show that each $v\_i$ can be written as a combination of the new basis vectors.]

## Week 1

### U1 (Due Tuesday, August 30)

1. Let $S$ be the set of sequences of real numbers $(z\_n)$ such that $\lim z\_n=0$. Show that $S$ is a subspace of $R^{\mathbb N}$.
2. Let $U=\set{(x,x,y,y)\mid x,y\in F}$, $V=\set{(x,x,x,y)\mid x,y\in F}$, and $W=\set{(x,x,y,z)\mid x,y,z\in F}$. Show that $W=U+V$. Decide whether $W=U\oplus V$ and demonstrate you are correct.

### H1 (Due Wednesday, August 31)

1. Find a complex number $z$ such that $z^2=-i$ and demonstrate you are correct.
2. In definition 1.23, change the scalar product to $(\lambda f)(x)=f(\lambda x)$. Show that the resulting variant of $F^S$ is not a vector space.
3. Find a subset of $R^2$ which is closed under addition, but not under scalar multiplication. Find a subset of of $R^2$ which is closed under scalar multiplication, but not under addition. In each case demonstrate you are correct.
4. Consider the following subsets of $R^3$. If it is a subspace of $R^3$, show that it is, and otherwise show that it is not.  
  * $\set{(x\_1,x\_2,x\_3)\mid x\_1=x\_2}$
  * $\set{(x\_1,x\_2,x\_3)\mid x\_1=1}$
  * $\set{(x\_1,x\_2,x\_3)\mid x\_1x\_2x\_3=0}$
  * $\set{(x\_1,x\_2,x\_3)\mid x\_1+x\_2+x\_3=0}$
  * $\set{(x\_1,x\_2,x\_3)\mid x\_1\leq x\_2\leq x\_3}$
5. (Similar to 1.C.20) Let $U$ be the following subspace of $R^4$: $U=\set{(x\_1,x\_2,x\_3,x\_4)\mid x\_1=x\_2}$. Find a subspace $V$ of $R^4$ such that $U\oplus V=R^4$.


<script type='text/x-mathjax-config'>
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true
    },
    TeX: {
      Macros: {
        set: ["{\\left\\{ #1 \\right\\}}", 1],
        abs: ["{\\left| #1 \\right|}", 1],
        lt: ["<"]
      }
    }
  });
</script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-AMS_HTML'></script>