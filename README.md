# Optimal Transport GAN (OTGAN)

Authors : Maxime Berillon and Rémy Deshayes

Generative modeling is an unsupervised learning task that aims at discovering and learning the underlying
structure of an input data in such a way that the model can be used to generate new examples that plausibly
could have been drawn from the input’s dataset.         
As always with unsupervised learning our main task will amount to learning the probability distribution of
that data at hand.

Section 1 of our [report](https://github.com/remydeshayes/OTGAN/blob/main/ot_final_report_berillon_deshayes.pdf) - please have a look at it - introduces one method to learn a probability distribution and the GANs a very famous generative
method leveraging this technique. Then, section 2 discusses the concept of distance between probability
distributions and presents a very famous distance taken from the optimal transport theory : the Wasserstein
distance. As an alternative to the WGAN, section 2 also compares the primal and dual approach of the
optimal transport problem introduced. Building on those remarks, section 3, introduces the OT-GAN and
its implementation.
