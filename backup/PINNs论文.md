# AI4Science

- [ ] Wang H, Fu T, Du Y, Gao W, Huang K, Liu Z, Chandak P, Liu S, Van Katwyk P, Deac A, Anandkumar A, Bergen K, Gomes CP, Ho S, Kohli P, Lasenby J, Leskovec J, Liu TY, Manrai A, Marks D, Ramsundar B, Song L, Sun J, Tang J, Velickovic P, Welling M, Zhang L, Coley CW, Bengio Y, Zitnik M. **Scientific discovery in the age of artificial intelligence**. Nature 2023, 620(7972): 47-60. 🔍【AI4Science】科学发现综述
- [ ] Karniadakis GE, Kevrekidis IG, Lu L, Perdikaris P, Wang S, Yang L. **Physics-informed machine learning**. Nature Reviews Physics 2021.

### PINNs

- [ ] Wang S, Sankaran S, Perdikaris P. **Respecting causality is all you need for training physics-informed neural networks**. arXiv preprint arXiv:220307404 2022. 🔍时序因果结构引入了数值方法的分步思想

- [ ] Wang S, Yu X, Perdikaris P. **When and why PINNs fail to train: A neural tangent kernel perspective**. Journal of Computational Physics 2022, 449: 110768. 🔍神经正切核，PINNs失效

### 神经算子结构网络

- [ ] Lu L, Jin P, Pang G, Zhang Z, Karniadakis GE. **Learning nonlinear operators via DeepONet based on the universal approximation theorem of operators**. Nature Machine Intelligence 2021, 3(3): 218-229. 🔍【DeepONet】结构
- [ ] Li Z, Kovachki N, Azizzadenesheli K, Liu B, Bhattacharya K, Stuart A, Anandkumar A. **Fourier neural operator for parametric partial differential equations**. arXiv preprint arXiv:201008895 2020. 🔍傅里叶神经算子【FNO】结构

# 本科毕设论文阅读

这部分论文主要是在完成本科毕设的过程中阅读的。

- [x] **Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations**, *M. Raissi, P. Perdikaris, G. E. Karniadakis*, Journal of Computational Physics, 2019. [[paper](https://www.sciencedirect.com/science/article/pii/S0021999118307125)] 🔍PINNs初始文章
- [x] **NSFnets (Navier-Stokes flow nets): Physics-informed neural networks for the incompressible Navier-Stokes equations**, 2021. [[paper](https://www.sciencedirect.com/science/article/pii/S0021999120307257)] 🔍本科毕设复现文章，专门求解NS方程的NSFnet
- [x] **Physics-Driven Learning of the Steady Navier-Stokes Equations Using Deep Convolutional Neural Networks**, 17 Jun 2021. [[paper](https://arxiv.org/abs/2106.09301)] 🔍参考Unet的设计思路，使用CNN求解steady NS方程（并未复现此篇，无源代码）
- [x] **A practical approach to flow field reconstruction with sparse or incom plete data through physics informed neural network**, 14 November 2022. [[paper](https://link.springer.com/article/10.1007/s10409-022-22302-x)] 🔍毕设的主要工作量来源，采用稀疏或不完整的数据集对NS方程进行求解