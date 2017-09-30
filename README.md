# YamabeGraphExp
1-Yamabe equation on a graph experimentation code


Development of tools to analyze 1-Yamabe equation on different
programs and their various program graph representations with varying
measures \mu and \omega on vertex and edge sets, respectively.


Taking (not verbatim) from [1], we are interested in:
```
Let G = (V,E) be a finite graph, where V is the vertex set and
E is the edge set. Let \mu be a measure on vertices, that is
\mu : V -> R_+ = (0, \infty +). Let \omega be a measure on the
edges, that is \omega: E -> R_+, such that for any incident vertices
with edges e = (x, y) and e' = (y, x), \omega(e) = \omega(e'). That
is, \omega is symmetric. 
```


From [2] we have the 1-Laplace operator on graphs as
```
Let x, y \in V

\Delta_1 f(x) =  1/\mu(x) \sum_{e = (x,y)} \omega(e) \sgn(f(y) - f(x))

and

          { {1}    if t > 0
\sgn(t) = { {-1}   if t < 0
          { [-1,1] if t = 0
 
```

## References
1. H. Ge, W. Jiang, "The 1-Yamabe equation on graph", https://arxiv.org/abs/1709.09867
2. K. C. Chang, Spectrum of the 1-Laplacian and Cheeger’s constant on graphs, J. Graph Theory 81 (2016), no. 2, 167-207.
