---
content_type: page
description: This section provides information on lecture topics along with brief
  summaries of the lectures.
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
title: Lecture Summaries
uid: fe1f7256-1984-f912-56a1-5f2ea7828048
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LEC #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
LECTURE SUMMARIES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Maxwell's equations and linear algebra
{{< tdclose >}}
{{< tdopen >}}
Converted Maxwell's equations to Hermitian eigenproblem (for linear, lossless media). Introduced Dirac |H> notation and adjoints. Derived real eigenvalues and orthogonal eigenvectors for Hermitian operators. Showed Maxwell operator to be Hermitian, positive semi-definite, and thus real ω and orthogonal |H>. Compared with quantum mechanics, noted scale invariance.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
Modes of a metal box and mirror symmetry
{{< tdclose >}}
{{< tdopen >}}


Solved toy example of 1d H{{< sub "z" >}}(x) field between 2 metal plates. Discussed symmetry, and showed that a mirror plane σ implies eigenfields that are even or odd under the mirror plane, corresponding to a mirror-reflection operator that commutes with the eigen-operator. Defined how vector fields rotate, and showed that H is not a vector but a pseudo-vector - it picks up an extra factor of -1 under improper rotations (rotations of a mirror image, which have determinant -1). For this reason the H field "looks" odd when the E field is even, and vice versa, but the fields "really" have the same symmetry.

Began a more complicated example of a field in a 2d metal box - here, there are many symmetry operations and to relate them we must use representation theory.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
Symmetry groups, representation theory, and eigenstates
{{< tdclose >}}
{{< tdopen >}}
Representation theory. Proved that eigenstates transform as representations, and showed how this applies to 2d metal box (for which the states fall into three of the five possible representations). Discussed representations, equivalent and irreducible representations, conjugacy classes, and character tables. Showed how to get character table using the orthogonality rules without knowing the representations; found the character table for C{{< sub "4v" >}} (symmetry group of square).
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
Translational symmetry, waves, and conservation laws
{{< tdclose >}}
{{< tdopen >}}


Derived exp(-ikx) representations for translational symmetry group, and used this to find planewave solutions of Maxwell's equations in homogeneous space. Derived conservation laws: showed that the representation of the field is invariant as a function of time.

Using this, derived Snell's law (conservation of interface-parallel k). The result is actually much more general than the usual Snell's law, however, because we can use it in cases where the ray-optics picture is invalid. (It will become even more interesting when we look at discrete periodicity).


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Total internal reflection and the variational theorem
{{< tdclose >}}
{{< tdopen >}}


Considered a two-dimensional dielectric waveguide, and derived the "total-internal-reflected" modes (except this is not ray optics). Introduced the far-reaching concept of the light cone and the fact that higher-dielectric regions introduce discrete guided bands below the light cone that correspond to exponentially localized states.

Derived the variational theorem in Hermitian eigenproblems. Our proof relied on completeness (you'll derive an alternate proof for homework); conversely, we showed how (under certain conditions on the operator), completeness can be derived from the variational theorem. Showed the form(s) taken by the variational theorem for electromagnetism, and (crudely) outlined a simple numerical method based on minimizing the variational Rayleigh quotient.

Proved the existence of guided modes in any 2d waveguide (localization in one direction), under very weak conditions on the dielectric function, using the variational theorem.

Discussed the generalization to 3d waveguides (localization in two directions). Argued that the presence of a substrate on one side of the waveguide creates a low-frequency cutoff for guiding.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}


Discrete translations and Bloch's theorem

MPB demo


{{< tdclose >}}
{{< tdopen >}}


Derived the representations exp(-ika) for discrete translational symmetry with period **a**, and thereby found Bloch's theorem: in a periodic system, the eigensolutions can be chosen of the form exp(ikx) multiplied by a periodic "Bloch envelope" function. Discussed relation to quantum mechanics and the mystery of the "free electron gas" model from the 19th century. Derived that the Bloch wavevector k, in turn, is periodic with periodicity 2π/a and defined the first Brillouin zone (at least in 1d...the more complete definition will wait until we get to 2d-periodic systems).

Demo'ed the MPB eigensolver software. Computed the band diagram and eigenmodes of the simple 2d waveguide structure we already considered in class. Also showed a more complicated system, a 1d-periodic sequence of 2d dielectric cylinders, and showed that this also has guided modes (quite different from a naive total-internal-reflection picture).


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
Bloch's theorem, time reversal, and diffraction
{{< tdclose >}}
{{< tdopen >}}


Reviewed Bloch's theorem, and stated it in its more-general 3d-periodic form, and showed how e.g. continuous translational symmetry is simply a special case. Described how the other space-group symmetries interact with k (i.e. the translational symmetries), and two effects in particular. First, the **point group** (space group ignoring translations) relates the states at one k to states at other k rotated by the symmetries, so that we only need to compute the eigenstates in a small region of k to get the eigenstates and eigenvalues everywhere. Second, the Bloch-envelope eigenstates at a particular k transform according to the symmetries of Θ{{< sub "k" >}}, which are a **subset** of the space group of the whole system (k breaks some of the symmetry in general).

Also discussed time-reversal symmetry. Reversing time is equivalent to conjugating the eigenproblem, and from this we saw that the k and -k eigenstates have the same eigenvalue. Time-reversal symmetry is broken, however, if Ε is complex - in particular, we still have a Hermitian problem if e is complex-Hermitian, but we don't have time-reversal symmetry. This can happen when you have an external magnetic field, and the resulting magneto-optic effect can be used to make optical isolators.

Considered diffraction from a 1d-periodic surface, and showed that for sufficiently high frequencies one gets additional reflected beams for additional diffracted orders, corresponding to Fourier components of the dielectric function. This comes from the fact that, in a periodic system, k is only conserved up to multiples of 2Π/a.

Introduced (but did not derive) the concept of photonic band gaps in one-dimensional systems, resulting in DBR mirrors (hence iridescent colors in nature), Fabry-Perot cavities, DFB lasers, and so on. Sketched the band structure of an archetypical 1d-periodic system.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
Photonic band gaps in 1d, perturbation theory
{{< tdclose >}}
{{< tdopen >}}


Derived the origin and general characteristics of the photonic band gap and band diagram in one dimension, starting with a uniform system and considering the effect of a small perturbation.

Derived 1st-order perturbation theory for the eigenvalues of a perturbed Hermitian operator, both the non-degenerate and the degenerate case. (See also "time-independent" or "stationary" perturbation theory in any quantum-mechanics text). Applied to Maxwell's equations, and found the first-order correction in the frequency from a small change Δ∈. Used this to compute the size of the first band gap in a weakly periodic system.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
1d band gaps, evanescent modes, and defects
{{< tdclose >}}
{{< tdopen >}}


Began by reviewing 1d gap structures, and how lowest "dielectric band" is concentrated in high-∈ layer while next "air band" is forced out by orthogonality, hence the gap. Discussed numerical results.

Discussed the traditional quarter-wave stack, which leads to maximum field attenuation in the band gap, and gave some useful analytical formulas for the layer thicknesses, mid-gap frequency, and gap size.

By analytic continuation near the band edge, showed that states in the band gap are exponentially decaying, plus a oscillating-sign phase. Furthermore, discussed why larger gaps generally lead to stronger decay. However, gave a couple of counter examples of systems with very large gaps which may have only weak decay: chirped gratings and random gratings (Anderson localization).

Showed how, by introducing a defect in the periodicity, one can trap localized defect modes (with a finite number of discrete frequencies), which are either "pushed up" or "pulled down" from either end of the gap, depending on the type of defect.

Discussed how in actual computation with periodic boundary conditions (ala MPB), defects are computed via supercells, and that this leads to "folded" band structures where many bands must be computed before you get to the localized state.

In the supercell, the defect band is nearly flat, with slope decreasing exponentially with the supercell size. Discuss how this can actually be used in order to form "coupled-cavity waveguides" (Yariv, et al. _Opt Lett_ 24, 711 (1999).) that have low velocity (slope) and a zero-dispersion point. Derived the cosine-like dispersion relation using a tight-binding approximation, based on very general considerations (Hermitian, mirror symmetry, linearity, weak coupling).


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
Waveguides and surface states, omni-directional reflection
{{< tdclose >}}
{{< tdopen >}}


Examined off-axis propagating in 1d-periodic structures: projected band diagrams, Fabry-Perot waveguides, surface states, and omnidirectional mirrors. Much reference were made to the book-figure from lecture 8.

Began with the off-axis band diagram, which causes the TM and TE bands to split - explained why TM bands lie lower than TE bands, due to the discontinuous boundary conditions of ∈|E|{{< sup "2" >}}.

Next considered the projected band diagram in which the ω for all values of k{{< sub "z" >}} (z = periodic direction) are plotted as a function of k{{< sub "y" >}} (y = parallel to layers), resulting in continuum regions. Related asymptotic behavior at large k{{< sub "y" >}} to ray-optics limit, explaining asymptotic slope and narrowing bandwidths.

Next considered a Fabry-Perot waveguide, formed by a defect in the periodic structure, giving rise to a guided band in the gap as a function of k{{< sub "y" >}}. Discussed criteria for whether this guided band intersects the continuum regions. Noted that we can now guide light in a **lower** index region (even air), quite different from index guiding.

Considered the surface states that arise at an interface - they are confined by index-guiding with respect to the homogeneous medium on one side of the interface and by the band gap with respect to the periodic structure on the other side of the interface. Claimed (without proof, yet), that there is always some crystal termination that gives rise to surface state(s).

Considered the criteria for omni-directional reflection from a multilayer film. Showed that for TM polarization, one always has a range of omni-directional reflection, but for TE polarization one may not, depending on the materials. Discussed the importance of Brewster's angle in the TE projected band diagram.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
Group velocity and dispersion
{{< tdclose >}}
{{< tdopen >}}


Discussed group velocity dω/dk and dispersion.

Gave classic derivation of group velocity for a medium uniform in one direction, by considering the propagation of a narrow-bandwidth pulse.

In a general periodic medium (for real, nondispersive ∈ and real wavevector k), showed that dω/dk = flux/energy-density = energy velocity. Did this by first deriving the Hellman-Feynman theorem for the derivative of the eigenvalue of a Hermitian operator, and applied this to compute dω/dk (which was then related to average flux/energy by various vector manipulations).

Then showed that |dω/dk| is at most c, for ∈ at least 1 (for real, nondispersive e and real wavevector k) in a general periodic medium. This was a straightforward application of a few inequalities, including the triangle inequality and the Cauchy-Schwarz inequality for inner products.

Discussed "superluminal" situations with non-Hermitian systems (gain/loss or evanescent fields) and for strongly dispersive ∈. Weakly dispersive∈ will be handled in homework.

Discussed impact of group-velocity ("chromatic") dispersion (frequency-dependent group velocity), and defined the dispersion parameter D. Discussed divergence of D at zero-group-velocity point in Fabry-Perot waveguide, or at any band edge.

Closed by preparing for 2d and 3d periodicity: derived/defined the primitive reciprocal lattice vectors G{{< sub "i" >}}.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
2d periodicity, Brillouin zones, and band diagrams
{{< tdclose >}}
{{< tdopen >}}


Reviewed group velocity, noted that phase velocity is not uniquely defined in a periodic system due to non-uniqueness of k vector.

Considered the 2d-periodic square lattice (in 2d). Defined its lattice vectors and found that the reciprocal lattice is also square lattice.

(Noted relation between reciprocal lattice and Fourier series: the Fourier transform of a 2d periodic function is a series of delta functions at the reciprocal lattice vectors. Periodicity of the Bloch wavevector k arises naturally in this description.)

Defined the first Brillouin zone (B.Z.) (and 2nd, 3rd,...) = pts closer to k=0 than to any other reciprocal lattice vector, and showed that this gives us all the inequivalent points and preserves the full rotational symmetry of the lattice. Showed how to construct it by using perpendicular bisectors between k=0 and other reciprocal lattice points.

Constructed the first Brillouin zone in 1d, and also for the 2d square lattice. In these simple cases, the B.Z. is simply the unit cell of the recip. lattice, centered on k=0, but this is not always the case! Defined irreducible B.Z. (I.B.Z.), and constructed I.B.Z. for square lattice of circular rods (C{{< sub "4v" >}} symmetry).

Defined special points Γ, X, and Μ for sq. lattice, and derived the space group in each of the different k regions. Discussed band diagram in 2d, and explained why we normally plot ω vs. k around the I.B.Z. boundary.

Showed TM band diagram of sq. lattice of dielectric rods in air, and pointed out that non-accidental degeneracies only occur at Γ and Μ points (which have C{{< sub "4v" >}} symmetry and thus have a 2-dimensional irreducible representation).


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
Band diagrams of 2d lattices, symmetries, and gaps
{{< tdclose >}}
{{< tdopen >}}


Continued with TM band diagram of sq. lattice of dielectric rods in air. Explained flatness of band edges at Γ, X, and Μ, and derived sufficient symmetry conditions for zero slope at those points. Discussed exception of non-zero slope at ω=0 Γ point, and relation to effective-medium theory.

Origin of 2d TM gap. Explained why infinitesimal periodicity does **not** give a gap (unlike 1d), and discussed how band diagrams "fold" in 2d. In this case, there is a minimum index contrast of about 1.73:1 to get a TM gap. Explained gap in terms of variation theorem and orthogonality of modes, and compared with computed D field plots. Explained why boundary conditions prevent TE gap in this structure. Showed how TE gap arises in a square lattice of dielectric veins in air (which has no TM gap for these parameters).

Introduced idea that triangular lattice of holes can give simultaneous TE/TM gap. Introduced triangular lattice, gave its lattice vectors, and derived its reciprocal lattice (a triangular lattice rotated 30°).


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
Triangular lattice, complete gaps, and point defects
{{< tdclose >}}
{{< tdopen >}}


Continued studying triangular lattice. Found the B.Z. and I.B.Z. (with corners Γ, Μ, and Κ), and showed that it has C{{< sub "6v" >}} symmetry (which has 2 two-dim. irreduc. representations). Showed that this B.Z. is more circular than B.Z. of sq. lattice, which makes it easier to have a gap (for rods, index contrast must be only 1.3:1 to get a TM gap).

Showed that, in both sq. and tri. lattices, M point is a standing wave pattern along the next-nearest neighbor direction(s). Showed that K point has 2nd-nearest-neighbor periodicity and C{{< sub "3v" >}} symmetry.

Showed TM/TE band diagram for tri. lattice of holes, which has complete TM+TE gap. Explained why first TM bands are doubly degenerate at Κ.

Discussed point defect modes in a square lattice, formed by changing the radius of a single rod. Plotted localized mode frequencies vs. rod radius. Explained why reducing rod radius pushes up monopole mode from lower band at M, and increasing rod radius pulls down doubly-degenerate dipoles modes from upper band at X, and then pulls down more modes. Related the defect modes to the irreducible representations of the C{{< sub "4v" >}} symmetry group.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
  

{{< tdclose >}}
{{< tdopen >}}
  

{{< tdclose >}}
{{< tdopen >}}
Mid-term Exam covering all material up to and including lecture 14 (but no point defects in 2d crystals).
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Line and surface defects in 2d, numerical methods introduction
{{< tdclose >}}
{{< tdopen >}}


Line-defect and surface states in 2d crystals, and projected band diagram. Showed why there is always **some** terminations that give rise to surface states.

Introduced numerical methods for solving continuous eigenproblems. Discussed choice of basis (finite-difference, planewave, finite element) and reduction to finite matrix via Galerkin method. Talked about scaling of dense matrix methods and sparse/iterative methods for N×N matrices. Showed how iterative methods apply to planewave problem via FFTs.

Began discussing preconditioned conjugate-gradient minimization of the Rayleigh quotient to find the lowest eigenvalues and corresponding eigenvectors. Started with steepest descent, then Newton's method, then preconditioned steepest descent. Didn't quite get to conjugate gradients.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
Conjugate-gradient, finite-difference time-domain (FDTD) method
{{< tdclose >}}
{{< tdopen >}}


Finish conjugate-gradient discussion. Also talk about sub-pixel averaging and convergence.

Introduced the finite-difference time-domain (FDTD) method, and demo'ed our "Meep" time-domain code. In particular, we go over concepts that are also described in the introduction and tutorial of the Meep manual: computation of Green's functions, transmission spectra, and resonant modes.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
More FDTD: Yee lattices, accuracy, Von-Neumann stability
{{< tdclose >}}
{{< tdopen >}}
More in-depth discussion of FDTD methods. Introduced the Yee lattice in 1d/2d/3d, analyzed accuracy of center-difference approximations vs. forward/backward differences, and explained how boundary discontinuities degrade the nominal quadratic accuracy. Von-Neumann stability analysis and the Courant factor relating temporal and spatial discretizations. Introduced perfectly-matched layer (PML) absorbing boundaries.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
Perfectly matched layers (PML), filter diagonalization
{{< tdclose >}}
{{< tdopen >}}


Continued discussion of PML: talked about numerical reflections and implementation of frequency-dependent ∈ and µ via introduction of auxiliary fields.

Discussed filter-diagonalization methods (FDM) in a Fourier basis, for computing resonant frequencies and loss rates from time-domain simulation.

Began discussion of three-dimensional photonic crystals. Introduced cubic/fcc/diamond lattices and reciprocal lattice/Brillouin zone. Contrasted fcc and diamond lattices of spheres.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
3d photonic crystals and lattices
{{< tdclose >}}
{{< tdopen >}}


Continued discussion of 3d crystals. Introduced "Yablonovite" and analyzed its symmetry and irreducible Brillouin zone. Also discussed Woodpile, natural opal, and inverse-opal crystals.

In MIT structure (which is simpler to visualize since layers resemble 2d crystals), discussed line and point defects and surface states.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
Haus coupled-mode theory, resonance, and Q
{{< tdclose >}}
{{< tdopen >}}


Concluded 3d-crystal discussion with description of multi-photon lithography and interference-lithography schemes.

Began introduction of Haus coupled-mode theory (see also Haus, H. _Waves and Fields in Optoelectronics._ Chapter 7.), to analyze devices combining waveguides and resonant cavities.

Started with simple system of waveguide coupled to cavity, and showed that while the reflection is always 100%, there is a time delay proportional to the cavity lifetime for frequencies near resonance. Then analyzed waveguide-cavity-waveguide system, and showed 100% Lorentzian transmission peak at resonance. Defined quality factor, Q, and gave various interpretations.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
Coupled-mode theory with losses, splitter / bend / crossing / filter devices
{{< tdclose >}}
{{< tdopen >}}
Continued coupled-mode theory discussion. Considered imperfect waveguide-cavity-waveguide filter systems, with asymmetry and/or losses. Analyzed splitter, bend, and crossing. Analyzed resonant-absorption system where one wants to absorb 100% of incident light. Analyzed channel-drop filter.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
Bistability in a nonlinear filter, periodic waveguides
{{< tdclose >}}
{{< tdopen >}}


Analyzed optical bistability in nonlinear filter/cavity.

Introduced hybrid systems combining band gaps and index guiding. 1d-periodic waveguides in 2d and 3d, projected band diagrams, guided modes, and "gaps".


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}
Photonic-crystal slabs: gaps, guided modes, waveguides
{{< tdclose >}}
{{< tdopen >}}


Localized defect modes (resonant modes) in 1d-periodic waveguides. Quality factor (Q) and losses, relation to Fourier decomposition, effect of substrates.

2d-periodic photonic-crystal slabs with vertical index guiding: gaps, symmetries, effects of slab thickness. Line-defect waveguides in rod and hole slabs. Losses from asymmetry, disorder.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
24
{{< tdclose >}}
{{< tdopen >}}


Cavities in photonic-crystal slabs

Photonic-crystal fibers


{{< tdclose >}}
{{< tdopen >}}


Localized point-defect modes in photonic-crystal slabs. Mechanisms for increasing Q: delocalization and cancellation.

Photonic-crystal fibers. Introduce conventional silica fiber and its limitations. Introduce hollow-core fibers: 2d-periodic (gaps, guided mdoes, surface states, effect of termination); 1d-periodic "Bragg fibers" (gaps, conservation of angular momentum, comparison with metal waveguides, TE/TM/hybrid modes, suppression of cladding absorption and perturbation theory, fabrication by Fink et al.)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
25
{{< tdclose >}}
{{< tdopen >}}
Hollow-core and solid-core photonic-bandgap fibers
{{< tdclose >}}
{{< tdopen >}}


Continue discussion of hollow-core fibers.

Solid-core fibers: band diagrams and modes, endlessly single-mode, enhanced nonlinearities. Effective area (with vectorial corrections) to determine strength of nonlinearities. The scalar limit and LP modes (asymptotic field patterns, symmetry and degeneracies, finite vs. infinite # modes, and origin of band gaps).


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}