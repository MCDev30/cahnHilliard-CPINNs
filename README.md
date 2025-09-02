# Constrained Neural Networks Approach of the Cahn-Hilliard Equation with u-dependent Mobility

### Abstract
The paper relative to this repository, presents a comparative study of numerical methods for the Cahn-Hilliard equation with concentration dependent mobility, contrasting a classical finite element approach with a modern deep learning framework. We introduce a constrained Physics-Informed Neural Network, or c-PINNs, which directly incorporates the physical bounds of the concentration field into the learning process. Our results demonstrate that this approach not only captures the complex dynamics of phase separation with high visual fidelity but also achieves strong quantitative agreement with a high fidelity finite element reference solution. The c-PINNs method adeptly handles the high order spatial derivatives inherent to the problem via automatic differentiation, bypassing the complexities of traditional discretization. While the initial training phase is computationally intensive, the resulting model acts as a fast and accurate surrogate, capable of instantaneous predictions. This work highlights the potential of constrained neural networks as a robust and flexible alternative for simulating complex physical phenomena, paving the way for more efficient exploration of phase separation dynamics in materials science and beyond.


#### Keywords: Cahn-Hilliard, Phase separation, concentration-dependent mobility, c-PINNs, Finite Element Method, Neural networks, Physical constraints 

## Authors
Abdou W. BELLO, Jamal ADETOLA, Said A. ABDILLAH and Charbel Z. J. MAMLANKOU
