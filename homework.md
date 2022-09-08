---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 403/503 homework

[Submit with gradescope](https://www.gradescope.com/courses/413854)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 3

### U3 (Due Tuesday, September 13)

1. Suppose that $V=U\_1+U\_2$. Show that $V=U\_1\oplus U\_2$ if and only if $\dim(V)=\dim(U\_1)+\dim(U\_2)$.
2. Show that if $S,T$ are linear transformations then $ST$ is a linear transformation. Show that $S(T\_1+T\_2)=ST\_1+ST\_2$. (Assume all the compositions make sense.)

### H3 (Due Wednesday, Septemmber 14)

1. Suppose that $V=U\_1+U\_2+U\_3$. Show that $V=U\_1\oplus U\_2\oplus U\_3$ if and only if $\dim(V)=\dim(U\_1)+\dim(U\_2)+\dim(U\_3)$.
2. Consider the space $V$ of polynomials of degree at most $4$. Let $v\_0,\ldots,v\_4$ be a list of polynomials with the property that for all $i$, the degree of $v\_i$ is equal to $i$. Show that $v\_0,\ldots,v\_4$ is a basis of $V$.
3. TBA

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