---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---
Artificial neural networks are nowadays one of the most studied and used algorithms for Artificial Intelligence to solve a huge variety of tasks. However, many deep models share a common drawback: their growing complexity challenges the computational capability of embedded devices and poses questions about the power consumption when deployed on the field. Neural Architecture Search targets automatic research of neural network architectures, optimizing metrics like performance and latency. However, typical NAS approaches do not keep into account the target hardware architecture but they optimize over generic metrics like FLOPs and memory footprint and do not take into account the possible presence of algorithmic biases. Indeed, after the recent AI Act, neural AI will be regulated also against the presence of these biases, which find their best ground to prosper in more compact architectures. 
BANERA proposes to: 

a) study the bias propagation inside neural networks with the employment of tools from information theory, and propose a differentiable term to minimize the bias propagation; 

b) design a penalty term that self-adapts to specific hardware architectures (hence, keeping also into account more metrics like for example caching and memory transfers), in order to obtain a "green" and optimized deep model; 

c) research biasing/debiasing sub-structures in the generated models to drive the fast design of efficient AI models which are also algorithmic bias-free.
