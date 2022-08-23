---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 403/503 homework

[Submit with gradescope](https://www.gradescope.com/courses/413854)

[Draft Overleaf template](https://www.overleaf.com/read/wqzxckcdzwzr)

## Week 1 (Due Wednesday, August 31)

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
6. TBA


## Week 1 U-Pruv (Due Tuesday, August 30)

1. Let $S$ be the set of sequences of real numbers $(z\_n)$ such that $\lim z\_n=0$. Show that $S$ is a subspace of $R^{\mathbb N}$.
2. TBA


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