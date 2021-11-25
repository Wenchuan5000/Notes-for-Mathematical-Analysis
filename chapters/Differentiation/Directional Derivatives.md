# Directional Derivatives

#### Definition: Directional Derivatives

Let $$\mathbb X = (X, \|\cdot\|*\mathbb X)$$ where $$X=\mathbb K^m$$, and let $$\mathbb Y=(Y, \|\cdot\|*\mathbb Y)$$.

Let $$f: \mathbb X \to \mathbb Y$$, and let $$\mathbf u \in \mathbb X \setminus \{\mathbf 0_\mathbb X\}$$.

The **directional derivative** of $$f$$ along $$\mathbf u$$, or **$$\mathbf u$$-directional derivative** of $$f$$ at a point $$\mathbf p \in X$$ is defined as
$$
\nabla_{\mathbf u} f(\mathbf p) := \lim_{t \to 0} \frac{f(\mathbf p + t \mathbf u) - f(\mathbf p)}{t},
$$
if the limit exists in $$\mathbb Y$$.

#### Theorem: Alternative Definition of Differentiable in The Term of Directional Derivatives

$$f$$ is differentiable at a point $$\mathbf p$$ iff for any $$\mathbf u \in \mathbb X$$, we have
$$
f(\mathbf p + t \mathbf u) = f(\mathbf p) + \nabla_{\mathbf u} f(\mathbf p) + o(t \mathbf u),
$$
as $$t \to 0$$, or, equivalently,
$$
\lim_{t \to 0} \frac{f(\mathbf p + t\mathbf u) - f(\mathbf p) - \nabla_{\mathbf u}f(\mathbf p)}{t} = \mathbf 0_{\mathbb Y}.
$$

In particular, let $$\phi: \mathbb X \to \mathbb Y$$ be defined as
$$
\phi(\mathbf x) := \nabla_{\mathbf x}f(\mathbf p),
$$
then $$\phi$$ is linear.