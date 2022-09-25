---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 403/503 homework

[Submit with gradescope](https://www.gradescope.com/courses/413854)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 5

### Take-home Quiz

**Instructions** (a) You may not consult with any other person. Your work must be *completely your own*. (b) You may use only methods *we learned in our class*. If you solve a problem using another method that is formally correct but which we have not covered, you may not receive full credit for it. (c) You may refer to your notes and class materials freely. If you use any outside resources, you must provide citations.

- (0) Please copy the following, and sign your name: "My solutions are my own original work. I completed the exam without the use of any other person as a resource. I followed Boise State University's policies on academic integrity."
- (1) Consider the vectors $u=(1+i,-2+i)$ and $v=(5-i,-1+8i)$ in $C^2$. Decide whether $v$ is a scalar multiple of $u$. Explain your answer.
- (2) Let $V$ be the vector space $F^N$ (aka $F^\infty$, see 1.22) consisting of all sequences $(z_n)$. Let $W$ be the subset of $V$ consisting of all sequences satisfying $z_{n+2}=z_{n+1}+z_n$ for all $n$. Show that $W$ is a subspace of $V$.
- (3) Let $V=F^5$ and let $U$ be the subspace $U=\set{(x_1,x_2,x_3,x_4,x_5):x_1+x_2+x_4=0,x_2+x_3+x_5=0}$. Find a basis of $U$. Then extend it to a basis of $V$.
- (4) Let $V=F^3$. Let $v_1=(a,0,0),v_2=(b,c,0),v_3=(d,e,f)$ where $a,b,c,d,e,f$ are unknown constants. For what values of the constants $a,b,c,d,e,f$ is it true that $v_1,v_2,v_3$ is linearly independent? Explain your answer.
- (5) Let $V=F^2$ and let $T\in L(V,V)$ be a linear map with the special property that the null space of $T$ is exactly equal to the range of $T$. Show that the null space of $T$ is one-dimensional. Show that $T^2=0$ (in other words, $T\circ T$ is the zero map). Give an example of a linear map $T$ with this special property (you may answer with a $2\times2$ matrix).
- (6) Let $T\in L(V,W)$. Let $v_1,\ldots,v_n$ be a basis of $V$. Show that there exists a basis $w_1,\ldots,w_m$ of $W$ such that the matrix of $T$ with respect to the $v$'s and $w$'s consists entirely of $1$s and $0$s.

The following problems are to be completed by Math 503 students only.

- (7) Suppose that $V$ is a vector space and $v_1,\ldots,v_n$ is a basis of $V$. Let $u$ be any vector and let $U$ be the span of the vectors $v_1-u,\ldots,v_n-u$. Show that the dimension of $U$ is at least $n-1$.
- (8) Suppose that $T\in L(U,V)$ and $S\in L(V,W)$. Show that $\mathrm{rank}(ST)\leq\min\set{\mathrm{rank}(S),\mathrm{rank}(T)}$. Give an example of linear transformations $S,T$ such that $\mathrm{rank}(ST)\lt\min\set{\mathrm{rank}(S),\mathrm{rank}(T)}$.

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