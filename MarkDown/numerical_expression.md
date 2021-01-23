# 마크다운에서 수식 표현

__$$를 이용하여 표시할 수 있다.__
$$y=ax + b$$
$$f(x)= if x < x_{min} : (x/x_{min})^a$$  
$$otherwise : 0$$  
$$P(w)=U(x/2)(7/5)/Z$$  
$$p_{\theta}(x) = \int p_{\theta}(2z)p_{\theta}(y\mid k)dz$$  
$$x = argmax_k((x_t-x_u+x_v)^T*x_m)/(||x_b-x_k+x_l||)$$  

__표현이 불가능한 수식은 javascript MathJax를 이용하여서 표현할 수 있다.__
```html
<script type="text/javascript" 
src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML">
</script>
```
표현형식은 [Latex](https://github.com/latex3/latex2e)와 동일하다.