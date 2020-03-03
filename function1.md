# Function Variation

$$
\text{Created by Miłosz Ratajczyk}
$$

## 0. Function

$$
f(x) = 2x^3 - 3x^2 - 2x + 3
$$


## 1. Domain of a function ( $\mathbb{X}$ ) 

$$
x \in \R 
$$


## 2. Zero of a function ( $x_0$ )

$$ 
f(x) = 0 \\
2x^3 - 3x^2 - 2x + 3 = 0 \\
\vdots \\
(2 x - 3) (x - 1) (x + 1) = 0 \\
x_0 = -1 \hspace{2mm}  \lor \hspace{2mm}  x_0 = 1 \hspace{2mm}  \lor \hspace{2mm} x_0 = \frac{3}{2}
$$


## 3. Intersection of OY axis ( $y_0$ )

$$
f(0) = y_0 \\
f(0) = 2(0)^3 - 3(0)^2 - 2(0) + 3 \\
y_0 = 3 
$$


## 4. Even or odd function

### 4.1 Even function
$$
\forall_{ x \in \mathbb{X} } \, f(x) \ne f(-x) \\
\text{Not even}
$$

### 4.2 Odd function
$$
\forall_{ x \in \mathbb{X} } \, -f(x) \ne f(-x) \\
\text{Not odd}
$$


## 5. Limits of a function

### 5.1 Limit in $-\infty$
$$
\lim_{x \to -\infty} f(x) = \lim_{x \to -\infty} x^3 (2 - \frac{3}{x} - \frac{2}{x^2} + \frac{3}{x^3}) = -\infty
$$

### 5.2 Limit in $\infty$
$$
\lim_{x \to \infty} f(x) = \lim_{x \to \infty} x^3 (2 - \frac{3}{x} - \frac{2}{x^2} + \frac{3}{x^3}) = \infty
$$


## 6. Asymptotes of a functions

### 6.1 Vertical asymptote
$$
\text{Does not exist}
$$

### 6.2 Horizontal asymptote
$$
\text{Does not exist}
$$

### 6.3 Oblique asymptote
$$
\text{Does not exist}
$$


## 7. Monotonicity, maxima and minima of a function

### 7.1 Zero of a derivative
$$
f'(x) = 6x^2 - 6x - 2 \\
f'(x) = 0 \\
6x^2 - 6x - 2 = 0 \\
2 (3x^2 - 3x - 1) = 0 \\
x = \frac{1 - \sqrt{\frac{7}{3}}}{2} \approx -0.26
\hspace{2mm} \lor \hspace{2mm} 
x = \frac{1 + \sqrt{\frac{7}{3}}}{2} \approx 1.26
$$

### 7.2 Sign of derivative
$$
f'(x) > 0 \, , \hspace{3mm} 
x \in ( -\infty, \frac{1 - \sqrt{\frac{7}{3}}}{2}  )
\cup ( \frac{1 + \sqrt{\frac{7}{3}}}{2}  , +\infty )
\\ \ \\
f'(x) = 0 \, , \hspace{3mm}
x \in \{ \frac{1 - \sqrt{\frac{7}{3}}}{2} 
, \frac{1 + \sqrt{\frac{7}{3}}}{2}  \}
\\ \ \\
f'(x) < 0 \, , \hspace{3mm} 
x \in (\frac{1 - \sqrt{\frac{7}{3}}}{2} 
, \frac{1 + \sqrt{\frac{7}{3}}}{2} )
\\ \ \\
$$

### 7.3 Monotonicity of a function
$$
f \nearrow \, , \hspace{3mm}
x \in ( -\infty, \frac{1 - \sqrt{\frac{7}{3}}}{2}  \rangle
,\langle  \frac{1 + \sqrt{\frac{7}{3}}}{2}  , +\infty )
\\ \ \\
f \searrow \, , \hspace{3mm}
x \in \langle \frac{1 - \sqrt{\frac{7}{3}}}{2} 
, \frac{1 + \sqrt{\frac{7}{3}}}{2} \rangle
$$

### 7.4 Maxima and minima of a function
$$
f''(x) = 12x - 6
\\ \ \\
f''(\frac{1 - \sqrt{\frac{7}{3}}}{2}) \approx -9.12 < 0 \Rightarrow \text{Maxima}
\\ \ \\
f''(\frac{1 + \sqrt{\frac{7}{3}}}{2}) \approx 9.12 > 0 \Rightarrow \text{Minima}
$$


## 8. Concave or convex of a function

### 8.1 Zero of a second derivative
$$
f''(x) = 12x - 6 \\
f''(x) = 0 \\
12x - 6 = 0 \\
x = \frac{1}{2}
$$

### 8.2 Sign of a second derivative
$$
f''(x) < 0 \, , \hspace{3mm} x \in ( -\infty, \frac{1}{2} ) \\
f''(x) = 0 \, , \hspace{3mm} x = \frac{1}{2} \\
f''(x) > 0 \, , \hspace{3mm} x \in ( \frac{1}{2}, -\infty )
$$

### 8.3 Concave or convex of a function
$$
x \in (-\infty , \frac{1}{2}) \Rightarrow \text{Concave function} \\
x \in (\frac{1}{2}, \infty  ) \Rightarrow \text{Convex function} 
$$

### 8.4 Inflection point
$$
f''(\frac{1}{2}) = 0 \Rightarrow \text{Inflection point in } \frac{1}{2}
$$ 


## 9. Table
|      $x$ | $-\infty$ |   $(-\infty, -1 )$    | $-1$  | $(-1,\frac{1 - \sqrt{\frac{7}{3}}}{2} )$ | $\frac{1 - \sqrt{\frac{7}{3}}}{2}$ | $(\frac{1 - \sqrt{\frac{7}{3}}}{2}, 1 )$ |  $1$  |   $(1,  \frac{1}{2})$   |
| -------: | :-------: | :-------------------: | :---: | :--------------------------------------: | :--------------------------------: | :--------------------------------------: | :---: | :---------------------: |
|   $f(x)$ | $-\infty$ | $\uparrow\rightarrow$ |  $0$  |          $\uparrow\rightarrow$           |          $\text{maxima}$           |         $\rightarrow\downarrow$          |  $0$  | $\rightarrow\downarrow$ |
|  $f'(x)$ |           |          $+$          |  $+$  |                   $+$                    |                $0$                 |                   $-$                    |  $-$  |           $-$           |
| $f''(x)$ |           |          $-$          |  $-$  |                   $-$                    |                $-$                 |                   $-$                    |  $-$  |           $-$           |

 |      $x$ |       $\frac{1}{2}$       | $(\frac{1}{2} , \frac{1 + \sqrt{\frac{7}{3}}}{2} )$ | $\frac{1 + \sqrt{\frac{7}{3}}}{2}$ | $(\frac{1 + \sqrt{\frac{7}{3}}}{2}, \frac{3}{2} )$ | $\frac{3}{2}$ | $(\frac{3}{2}, +\infty )$ | $+\infty$ |
 | -------: | :-----------------------: | :-------------------------------------------------: | :--------------------------------: | :------------------------------------------------: | :-----------: | :-----------------------: | :-------: |
 |   $f(x)$ | $\text{inflection point}$ |               $\downarrow\rightarrow$               |          $\text{minima}$           |               $\rightarrow\uparrow$                |      $0$      |   $\rightarrow\uparrow$   | $\infty$  |
 |  $f'(x)$ |            $-$            |                         $-$                         |                $0$                 |                        $+$                         |      $+$      |            $+$            |           |
 | $f''(x)$ |            $0$            |                         $+$                         |                $+$                 |                        $+$                         |      $+$      |            $+$            |           |

## 10. Plot 

![plot](https://github.com/miloszratajczyk/function-variation/blob/master/function1.png?raw=true)