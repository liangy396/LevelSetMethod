# Level set movies for the paper

Liang Yang, David Hyde, Ognjen Grujic, Celine Scheidt, Jef Caers,

Assessing and visualizing uncertainty of 3D geological surfaces using level sets with stochastic motion,

Computers & Geosciences,

Volume 122,

2019,

Pages 54-67,

ISSN 0098-3004,

https://doi.org/10.1016/j.cageo.2018.10.006.

(http://www.sciencedirect.com/science/article/pii/S0098300418302917)

Abstract: 

For many geoscience applications, prediction requires building complex 3D surface models. Because of such complexity, often only a single model is built, possibly with a small set of variants to represent the uncertainty. Recent advancement in implicit modeling has made the construction of 3D geological models simpler; however, automatic assessment and visualization of uncertainty constrained by input geological rules and data constraints is still an active research topic. In this paper, we propose a new method that directly assesses and visualizes the uncertainty of geological surfaces by the means of stochastic motion. We represent the geological surfaces as the addition of stochastic implicit conceptual models and residual functions subject to the constraints of data and geological age relationships. Two sampling approaches to create the stochastic motion are proposed: Monte Carlo and Markov chain Monte Carlo (McMC). The uncertainty is assessed by independent realizations drawn by Monte Carlo sampling. The uncertainty is visualized by a “smooth” movie of gradually evolving geological surfaces that have the same stationary distribution as Monte Carlo, sampled by Markov chain Monte Carlo (McMC). This idea is integrated into the level set equation. Level sets are an ideal way to represent mathematically complex surfaces without explicit grid representations, thereby having the advantage of avoiding tedious topological computations such as defining the connectivity of a surface. We illustrate this new idea with simple synthetic 3D examples, taking the constraints of data and geological age relationships into consideration. Finally, we illustrate the idea using a synthetic data set from a copper deposit, where dense drillholes constrain an ore body with seven different lithologies. Our method provides a direct assessment and visualization of the uncertainty of 3D geological surfaces.

Keywords: 3D geological models; Gradual deformation; Markov chain Monte Carlo; Conditional simulation



# Details

1. "Copper_lithology.mp4" shows how the method works with complex  shapes.You can see significant geometrical and topological changes. Link: https://github.com/liangy396/LevelSetMovies/blob/master/Copper_lithology.mp4

2. "Copper_Section.mp4" shows the section view of the copper data simulation. It shows the geological age relationships. Link: https://github.com/liangy396/LevelSetMovies/blob/master/Copper_Section.mp4

3. "r20s5.mp4" is a illustration example showing conditional simulation with range 20 and sill 5 of 3 surfaces. Link: https://github.com/liangy396/LevelSetMovies/blob/master/r20s5.mp4

4. "r20s10.mp4" is a illustration example showing conditional simulation with range 20 and sill 10 of 3 surfaces. Link: https://github.com/liangy396/LevelSetMovies/blob/master/r20s10.mp4

5. "r60s5.mp4" is a illustration example showing conditional simulation with range 60 and sill 5 of 3 surfaces. Link: https://github.com/liangy396/LevelSetMovies/blob/master/r60s5.mp4

6. "r20s5u.mp4" is a illustration example showing unconditional simulation with range 20 and sill 5 of 3 surfaces. Link: https://github.com/liangy396/LevelSetMovies/blob/master/r20s5u.mp4


