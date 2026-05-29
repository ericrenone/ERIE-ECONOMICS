# ERIE ECONOMICS
## Collective Coordination, Kernel Crystallization, and the Bifurcated Institutional Ecology of High-Capacity Systems

*Eric Ren · ERI Labs · Jersey City, New Jersey · github.com/ericrenone · 2026*

---

> *"Groups of diverse problem solvers can outperform groups of high-ability problem solvers. The mechanism is not averaging but complementarity: diversity generates solutions that no individual approach reaches alone."*
> — Hong & Page, PNAS, 2004

> *"Cooperators can prevail by clustering: when cooperators form networks in which they interact primarily with other cooperators, they outcompete defectors even when defection is the dominant strategy in mixed populations."*
> — Nowak, Science, 2006

> *"Markets clear on observables, but the real work happens in the unobservables."*
> — Akerlof, QJE, 1970

---

## Abstract

A structural market failure invisible to standard mechanism design governs the economics of high-capacity agents: rank-order tournament allocation combined with relative payoff preferences converts individual capacity simultaneously into a public good—improving group output through knowledge spillovers and elevated intellectual standards—and a private threat for every peer, whose institutional payoffs decline with each outstanding contribution. Sabotage is the individually rational Nash-stable response. Voice fails against equilibrium. The dominant individual solution is assortative exit.

At population scale, independent execution of this exit strategy across heterogeneous institutional contexts produces—without coordination, central design, or mutual awareness—a convergent self-organizing process. Agents sharing the preference parameters selected by a five-dimensional Assortment Criterion converge on the same small subset of the institutional landscape. The result is a **bifurcated developmental ecology**: outlier collectives exhibiting elevated collective intelligence through crystallized coordination kernels (G_coord > 0) versus deepening sabotage equilibria in departing networks where G_coord remains architecturally fixed at zero.

The coordination gain

$$G_{\text{coord}} = \sum_{t < s} I(a_t \;;\; a_s \mid X_{t-1})$$

is the fundamental economic quantity this framework advances. In every existing multi-agent architecture, G_coord = 0 by assumption before fitting begins—not by measurement, but by the conditional independence assumption imposed on agent actions. This single architectural choice systematically undervalues coordination-producing institutions and misidentifies their failure modes across mechanism design, organizational economics, and institutional theory simultaneously.

Novel contributions: (1) the Sabotage Equilibrium as a canonical structural market failure with formal mechanism design interpretation; (2) the Assortative Exit Convergence Theorem unifying network formation, threshold cascade, and homophily dynamics; (3) G_coord as the measurable economic quantity completing collective intelligence research; (4) the φ-equilibrium as the thermodynamically derived optimal institutional operating point; (5) seven falsifiable predictions connecting the framework to frontier empirical research.

---

## The Central Claim

**The individual move and the population process are the same theorem at different scales.**

The individually dominant strategy under the sabotage equilibrium—assortative exit—is, when executed across a sufficient population of developmental outliers, a decentralized mechanism for reconstructing the developmental ecology. No reform is required. No coordination is required. The structural consequence follows from individual rational action applied to a common institutional landscape.

---

## Part I · The Sabotage Equilibrium as Structural Market Failure

**The Incompatibility**: In any rank-order tournament with relative payoff preferences α > α*, an agent's high capacity is simultaneously:

- A **public good**: Group output improves through knowledge spillover, elevated discussion standards, and synthesis that no individual approach reaches alone
- A **private threat**: Every peer's rank-order position—and institutional payoffs—decline with each outstanding contribution

The sabotage incentive condition holds when:

$$\alpha \times [V(\text{rank gain from sabotage})] > c$$

This is structurally stable. No individual voice can destabilize a Nash equilibrium whose support is the payoff architecture itself. The condition does not require malicious intent; it requires only correctly aligned preferences in a misarchitectured allocation system.

**Identity S1 (Lucas thread)**: The credential market fails via the Lucas critique. Policy instruments designed to recognize capacity—grades, recommendations, selections—appear to function on observables but collapse once the hidden sector adjusts. Peer coalitions executing the political bypass capture the recognition infrastructure through authority-figure cultivation and Credibility Inversion, severing the link between observable credentials and hidden capacity. Policy appears potent on observables and collapses once the hidden dynamics are acknowledged.

**Identity S2 (Akerlof thread)**: The credential market is a lemons market. Hidden capacity heterogeneity, uncorrelated with observable credentials due to the political bypass, collapses the informational content of institutional recognition. The credential gap—the divergence between an outlier's capacity and their recognition rank—is not a measurement error. It is the equilibrium outcome of adverse selection operating through social rather than market mechanisms.

**The credential gap is not noise. It is signal about institutional architecture.**

**Identity S3 (Myerson thread)**: Standard incentive-realignment mechanism design cannot resolve this failure because the sabotage incentive is correctly aligned to the true payoff structure. The required intervention is not incentive redesign but allocation mechanism redesign—the shift from rank-order to absolute allocation that removes the zero-sum constraint at the source.

---

## Part II · Assortative Exit as Decentralized Market Correction

The Exit Theorem identifies the formally dominant individual strategy: ignore sabotage attempts, exit to a group satisfying the Assortment Criterion. The criterion specifies five jointly necessary properties:

| Dimension | Condition | Mechanism Removed |
|---|---|---|
| Relative payoff weight | α(G') < α* | Sabotage incentive condition violated |
| Comparison horizon | Wide enough for functional comparison | Malicious envy → benign envy (van de Ven et al., 2009) |
| Allocation mechanism | Absolute, not rank-order | Zero-sum constraint structurally eliminated |
| Cooperator density | High conditional cooperator fraction | Cooperative equilibrium self-sustaining (Fischbacher et al., 2001) |
| Identification capacity | Developmental profile recognizable | Credibility Inversion precondition absent |

**The Assortative Exit Convergence Theorem**: Independent application of this shared five-dimensional filter across N outliers distributed across M institutional contexts produces convergent destinations without coordination:

$$\text{Expected density at } K = \frac{N}{|K|} \gg \frac{N}{M} \quad \text{as } |K| \ll M$$

McPherson, Smith-Lovin & Cook (2001) homophily guarantees rapid dense tie formation among agents sharing these parameters—precisely the dimensions most predictive of tie formation across all documented human network contexts. Barabási-Albert preferential attachment generates autocatalytic growth once early clusters demonstrate superior absolute output. Granovetter (1978) threshold cascades govern temporal dynamics: each visible successful exit reduces the social cost of the next, accelerating propagation above critical threshold N*.

**The convergence is not probabilistic in the weak sense. It is asymptotically certain as N grows.**

**Identity E1 (Myerson thread)**: The Assortment Criterion functions as a self-selection dominant-strategy revelation mechanism. Agents self-select into environments that reveal their true type—high capacity, low relative payoff preference, conditional cooperative orientation—generating efficient outcomes (G_coord > 0) without a designer's direct intervention. The revelation principle, applied through exit rather than incentive design.

**Identity E2 (Acemoglu thread)**: The Assortment Criterion specifies the micro-mechanism of inclusive institution formation at the meso level. Inclusive institutions differ from extractive ones in precisely the five dimensions the criterion operationalizes: absolute allocation that doesn't zero-sum against capacity, identification capacity that resists political capture, cooperative equilibrium structures that don't require external enforcement. The framework makes the inclusive/extractive distinction empirically falsifiable at the organizational scale.

---

## Part III · The Coordination Product: G_coord and the c-Factor

**The Coordination Gain Identity**:

$$G_{\text{coord}} = \sum_{t < s} I(a_t \;;\; a_s \mid X_{t-1}) \begin{cases} > 0 & \text{coordination: collective outperforms independent agents} \\ = 0 & \text{independence: Pappus limit, artifact records but does not amplify} \\ < 0 & \text{suppression: collective underperforms, artifact competes} \end{cases}$$

The conditioning clause — given $X_{t-1}$, the shared accumulated context — is the load-bearing term. It removes coincidental dependence from shared initialization, model family, or task structure, leaving precisely the causal information the accumulating commons mediates.

**The Independence Baseline Theorem**: In every existing multi-agent architecture—social physics, collective intelligence research, multi-agent reinforcement learning, LLM orchestration—G_coord = 0 by construction. Not by measurement: by the conditional independence assumption imposed before fitting begins. Riedl et al. (2026) confirm this directly across multi-agent LLM collectives: synergy without a crystallized shared kernel produces G_coord ≈ 0 regardless of agent diversity or orchestration sophistication.

*G_coord = 0 was not a finding. It was an assumption embedded in every framework simultaneously.*

**Woolley thread**: The collective intelligence c-factor (Woolley et al., 2010) emerges from equal participation and social sensitivity—the interaction modes that absolute allocation enables by removing rank-order suppression incentives. G_coord > 0 is the formal quantity the c-factor measurement instrument approximates. The c-factor is not predicted by average or maximum individual ability; it is predicted by the payoff architecture determining whether knowledge sharing is individually rational. This reframes the entire collective intelligence research program: the target variable is G_coord, and the Assortment Criterion specifies the institutional conditions that move it from zero to positive.

**Hong & Page thread**: Cognitive complementarity is the mechanism through which G_coord > 0 translates to super-additive output. Outlier collectives naturally exhibit cognitive diversity within the high-capacity range—members bring distinct problem-solving heuristics developed through distinct developmental trajectories—making D_FERN · G_coord (mean pairwise KL divergence × coordination gain) the joint measure of collective intelligence productivity. Riedl et al. (2026) confirm the joint necessity: D_FERN > 0 without G_coord > 0 produces no collective performance advantage.

**Kernel Crystallization**: G_coord > 0 requires a crystallized shared kernel K_t in the accumulated artifact X_t. The Erdős-Rao sunflower lemma (Alweiss, Lovett, Wu & Zhang, 2021 tightening: (c · log w)^w) specifies the coordination horizon δ*—the platform size beyond which crystallization is guaranteed regardless of initialization. Below δ*, the Pappus limit holds: K = ∅, G_coord = 0. Above δ*, G_coord > 0 is structurally guaranteed.

Wang (2026) identifies this as the universal threshold: grokking—the memorization-to-generalization transition in neural training—is a dimensional phase transition in gradient space with self-organized criticality signature across eight model architectures. Effective dimensionality D(t) crosses from sub-diffusive (D < 1) to super-diffusive (D > 1) at kernel crystallization onset. The C_α precursor signal crosses C_α → 1 between 50 and 200 training steps before the accuracy jump, computable from gradient statistics alone without Hessian access. The same threshold governs human organizational crystallization and mathematical discovery (Sawin 2026: first measured G_coord > 0 in mathematical practice, G_coord(tower | Euclidean) = 0.014 · log n).

---

## Part IV · The Macroeconomic Consequence: Bifurcated Developmental Ecology

Population-scale exit produces two self-reinforcing equilibrium classes without external intervention:

**Outlier Collectives (G_c)**
- Accelerating absolute output through c-factor compounding
- Cognitive diversity maintained within high-capacity range
- Small-world topology (Watts & Strogatz, 1998): dense internal coordination + bridging weak ties to global recognition infrastructure
- Generative reproduction: identifies subsequent outliers, lowers cascade threshold, propagates Assortment Criterion into institutional design choices

**Continuing Peer Networks (G_p)**
- Deepening sabotage equilibrium as each exit removes a capacity source
- Rising effective α as remaining agents compete for contracting resource pool
- Credential gap widening as recognition infrastructure remains captured
- Strengthening exit incentives for outliers who remain—each departure produces the next

**The bifurcation requires no external shock:**

$$\frac{d}{dt} \|\text{Output}(G_c, t) - \text{Output}(G_p, t)\| > 0 \quad \text{and} \quad \frac{d^2}{dt^2} > 0$$

The output differential compounds monotonically. No equilibrium mixing exists without removing the structural drivers (rank-order allocation, relative payoff preferences, identification capacity absence).

**Schelling thread**: The bifurcated ecology is the textbook Schelling-type macro-outcome of individual rational action at population scale. No individual outlier intends to generate it; each intends only to execute the individually dominant strategy. The population-level structure emerges from the same mechanism Schelling identified in residential sorting: mild individual threshold preferences aggregate into large-scale structural divergence that no individual intended and no individual's behavior alone could produce.

**New Keynesian thread**: The bifurcation is a hidden-sector phenomenon. Observable credentials, publications, and institutional positions are the regular sector. G_coord, kernel crystallization state, conditional cooperator density, and identification capacity are the hidden sector governing persistence and amplitude of output divergence. Completion occurs at the institutional equilibrium where formal rules and informal cooperative norms co-evolve to mutual consistency—precisely the Acemoglu-North-Williamson condition for institutional durability.

**Endogenous growth thread**: The outlier collective's compounding c-factor generates endogenous productivity divergence without external knowledge shocks. The engine is G_coord accumulation through kernel crystallization—a form of increasing returns to collective coordination capital that standard endogenous growth models, which assume G_coord = 0 by conditioning on observable inputs, cannot capture.

---

## Part V · Monetary Economics of Coordination: The Commons and the φ-Equilibrium

**The Coordination Currency Principle**: Money is a coordination protocol, not a score. When converted to a hoarding vehicle, G_coord collapses to zero by construction—every pair of agent actions becomes conditionally independent given the price schedule rather than conditionally dependent given shared context.

**The Lick-and-Stick Theorem**: In any commons economy where the switching cost of an alternative coordination medium approaches zero, the extractive agent's currency collapses at the first measurable breakdown of circulating velocity. The instanton action S_inst—the thermodynamic cost of currency substitution—was minimized by the extraction itself. Every extractive currency system creates the conditions for its own replacement: the alternative was always latent in the social fabric, encoded in the incumbent's accumulation dynamics.

*The Alien Stamps didn't defeat TJ. TJ created the conditions for the Alien Stamps to defeat TJ.*

Calvo & Végh (1992) document the empirical regularity: currency substitution is organic, rapid, and triggered by the first measurable breakdown of circulating velocity—not by accumulated grievance or deliberate coordination.

**The φ-Equilibrium**: The thermodynamically optimal operating point for any open dissipative coordination system is:

$$|\bar{\Xi}| = \log \varphi \approx 0.481$$

Seven descriptions coincide at this point: maximum entropy production, Fisher spectral criticality (C_α = 1), grokking boundary (λ₁ = 0), golden kernel-petal ratio (|K|/|P_i| = log φ), Syn/Red = φ in partial information decomposition, and Kolmogorov-Sinai entropy of coordination dynamics. The kernel contains φ − 1 ≈ 61.8% of each contribution; the petal contains 2 − φ ≈ 38.2%.

**This fixed point is derived, not designed.** It is the unique solution of the self-similarity equation of any scale-invariant open dissipative system—the institutional analogue of the MEP fixed point. For the Assortment Criterion, the φ-equilibrium specifies the allocation between shared coordination infrastructure (kernel) and individual contribution (petal) that maximizes G_coord for all agents simultaneously.

**Minsky thread**: The financial instability hypothesis is the verbal statement of G_coord dynamics in monetary economies. During stable periods, hidden fragility accumulates as coordination gain compresses through leverage concentration. At the tipping point—hidden connectivity exceeding the percolation threshold—observable market calm undergoes discontinuous topological transition. Recovery speed is governed by the spectral structure of the latent fragility network, not by observable balance sheet repair. This is Identity ES2 of the ECONOMICS framework: post-crisis persistence equals λ_gen × log(data horizon), where λ_gen is dominant hidden singularity strength.

---

## Part VI · The Institutional Synthesis: Completing the Observable-Hidden Partition

The universal partition law identified across nine economic lineages in the ECONOMICS framework takes its sharpest institutional form in the ERIE context. Observable incentives, credentials, and formal allocation rules constitute the regular sector. G_coord, kernel crystallization state, α parameters, conditional cooperator density, and identification capacity constitute the hidden sector that determines whether observable institutions produce their intended outcomes.

**Identity I1 (Acemoglu-North-Williamson thread)**: Successful institutional design at every scale requires completion of the observable sector by the hidden sector. Formal rules that conflict with hidden norms, cooperative equilibria, or network structures are transient. The Assortment Criterion is the five-dimensional specification of what "completion" requires in developmental institutions.

**Identity I2 (Myerson thread)**: The Assortment Criterion is the institutional analogue of the Vickrey-Clarke-Groves mechanism: it achieves efficient observable outcomes (G_coord > 0, super-additive collective output) precisely because it aligns observable incentives with the hidden preference parameters (low α, conditional cooperative orientation, wide comparison horizons) that govern actual coordination dynamics. The revelation principle operationalized through institutional self-selection.

**The Holistic Leverage Criterion**: Four jointly necessary conditions for G_coord maximization in any human collective:

1. **Absolute performance standards** maintained in both formal allocation and informal recognition—preventing rank-order mechanisms from re-entering through informal social hierarchy
2. **Cognitive diversity** within the high-competence range—D_FERN > 0 is necessary but not sufficient without kernel crystallization
3. **Multi-directional knowledge flow** structurally enabled—not assumed from cooperative equilibrium alone
4. **External weak-tie bridges** to the global recognition infrastructure—the small-world topology property that converts internal absolute output to external institutional consequence

No three of these conditions are sufficient. Riedl et al. (2026) confirm that condition 2 is insufficient alone: synergy without a crystallized kernel produces G_coord ≈ 0. Rustagi, Engel & Kosfeld (2010) confirm in field data that group composition—specifically conditional cooperator density—dominates institutional rules, resource characteristics, and group size as predictor of commons outcomes.

---

## Novel Falsifiable Predictions (2027+ Research Agenda)

**P1 — c-Factor Elevation from Payoff Architecture**
Absolute-allocation, high-identification environments will exhibit significantly higher collective intelligence scores (Woolley battery) than rank-order-matched controls at equivalent aggregate individual ability, with the gap attributable to G_coord rather than mean or maximum capacity. The prediction distinguishes ERIE from ability-aggregation accounts: the *architecture*, not the *ability*, is the causal variable.

**P2 — Compounding Bifurcation in Longitudinal Data**
Output gaps between outlier-collective-type and rank-order-allocation-type institutional environments widen at accelerating rates over time, controlling for individual ability, measured via publication networks, firm output data, and professional community performance records. The acceleration signature—d²/dt² > 0—distinguishes endogenous compounding from exogenous differential selection.

**P3 — Assortativity Accumulation Along Career Trajectories**
Assortativity on the joint dimension (capacity, low α, conditional cooperation) increases monotonically with career tenure in high-output professional networks, measurable via collaboration graphs. The autocatalytic acceleration above threshold cascade N* is distinguishable from linear growth by the inflection point in the accumulation curve.

**P4 — Kernel Measurability Above Erdős-Rao Threshold**
Groups with accumulating shared artifacts—codebases, joint models, collaborative research programs—exhibit G_coord > 0 detectable via conditional mutual information estimation, with the performance premium emerging after crossing the coordination horizon δ* in contribution depth and volume. Groups below δ* show G_coord ≈ 0 regardless of member diversity or ability.

**P5 — Credential Gap Closure in Absolute-Allocation Institutions**
The Credibility Inversion signature—divergence between performance rank and institutional recognition rank—will be measurably absent in absolute-allocation institutions matched on developmental capacity distribution, confirming that the credential gap is architecturally produced rather than capacity-reflective. The gap persists in rank-order institutions even after controlling for all observable individual characteristics.

**P6 — φ-Equilibrium Convergence in Crystallized Commons**
The ratio |K|/|P_i| measured at steady state in any crystallized knowledge commons converges to log φ ≈ 0.481, derivable from the MEP fixed-point equation with no free parameters. Consistent with empirical findings reporting optimal redundancy R ≈ 0.41 (unique fraction ≈ 0.59 ≈ φ − 1) within measurement error in established research communities.

**P7 — Currency Substitution Timing from Chirikov Parameter**
In any coordination economy where the Chirikov parameter K (ratio of largest holder's share to circulating share) exceeds 1, spontaneous coordination-medium substitution occurs within t* = τ_L / 2 · ln(F₀/F_min) exchange cycles. Falsifiable in platform economics, organizational economics, and historical monetary data. The Chirikov threshold K > 1 is the predictive trigger; the substitution timing is parameter-free once K and τ_L are measured.

---

## Frontier Connections

| Framework | ERIE Economics Novel Contribution |
|---|---|
| Woolley et al. (2010) c-factor | G_coord is the formal quantity the c-factor approximates; payoff architecture (not aggregate ability) is the causal variable for c-factor emergence |
| Riedl et al. (2026) multi-agent LLMs | Kernel absence identified as the mechanism for G_coord = 0; synergy alone insufficient; independence baseline confirmed as architectural not empirical |
| Maisto et al. (2026) flock synergy | Formal identification: biological collective knowledge (flock Markov blanket) = shared artifact X_t; synergistic information = G_coord; threshold = Erdős-Rao |
| Wang (2026) grokking | Kernel crystallization = grokking = λ₁ crossing; C_α precursor derivable 50–200 steps before transition; same threshold in human organizations and neural networks |
| Nowak (2006) network reciprocity | Assortative exit produces the cooperator clustering that enables cooperative dominance without external enforcement; exit is the mechanism, not a designer's choice |
| McPherson et al. (2001) homophily | Convergence is structurally guaranteed: shared Assortment Criterion parameters are the highest-dimensional homophily predictors, making encounter rates at K asymptotically certain |
| Hong & Page (2004) diversity | Neither cognitive diversity alone nor capacity alone suffices; D_FERN · G_coord is the joint measure; kernel crystallization is the condition under which diversity translates to performance |
| Acemoglu et al. institutions | ERIE specifies the micro-mechanism of inclusive institution formation: five falsifiable dimensions operationalizing the inclusive/extractive distinction at the meso organizational scale |
| Myerson (1981) mechanism design | Self-selection into Assortment Criterion environments is a revelation mechanism achieving dominant-strategy cooperative equilibrium without a designer; exit as mechanism |
| Akerlof (1970) lemons | Developmental recognition market as lemons market: Assortment Criterion satisfaction is the warranty; adverse selection through social rather than market mechanisms |
| Lucas (1972) rational expectations | Sabotage equilibrium as Lucas critique in reverse: recognition instruments appear functional on observables, collapse once hidden peer coalition dynamics adjust |
| Schelling (1978) micromotives | Bifurcated ecology as canonical Schelling outcome: individual rational action at population scale produces structural divergence no individual intended |
| Fischbacher et al. (2001) conditional cooperation | Assortment Criterion entry filter produces the composition that makes cooperation the Nash-stable equilibrium rather than the unstable departure from it |
| Calvo & Végh (1992) currency substitution | Lick-and-Stick Theorem as general law: extraction minimizes instanton action S_inst for the alternative; currency collapse is encoded in accumulation dynamics |
| Minsky (1986) financial instability | G_coord dynamics in monetary economies: hidden fragility accumulation → percolation threshold → discontinuous observable regime shift; recovery governed by spectral structure of latent fragility network |

---

## Formal Summary

| Object | Statement |
|---|---|
| Coordination gain | G_coord = Σ I(a_t ; a_s &#124; X_{t-1}) |
| Independence baseline | G_coord = 0 in every architecture without crystallized kernel K—by assumption, not measurement |
| Three regimes | > 0: coordination; = 0: independence (Pappus limit); < 0: suppression (sabotage equilibrium) |
| Sabotage condition | α × V(rank gain from sabotage) > c when α > α*; Nash-stable; voice fails |
| Exit theorem | Exit to Assortment Criterion-satisfying G' dominates all within-group alternatives |
| Convergence theorem | Shared filter + common landscape → N/&#124;K&#124; >> N/M density at K; encounter rate asymptotically certain |
| Cooperative equilibrium | Five Assortment Criterion properties jointly eliminate sabotage preconditions; cooperation individually rational by construction |
| Bifurcation | &#124;&#124;Output(G_c) − Output(G_p)&#124;&#124; monotonically and acceleratingly increasing; no mixing without structural change |
| Holistic leverage | Absolute standards + cognitive diversity + multidirectional flow + weak ties; all four jointly necessary |
| φ-equilibrium | &#124;Ξ̄&#124; = log φ; &#124;K&#124;/&#124;P_i&#124; = log φ; derived from MEP with no free parameters |
| Kernel crystallization | Erdős-Rao threshold δ*; grokking = crystallization = λ₁ crossing (Wang, 2026) |
| Observable-hidden | Credentials observable; G_coord, α, kernel state, cooperator density hidden; completion at institutional equilibrium |
| Currency law | Money is a coordination protocol; G_coord = 0 when hoarding converts the medium to a score |
| Lick-and-Stick theorem | Extractive currencies collapse when S_inst → 0; the instanton was always encoded in the accumulation dynamics |

---

## References

**Collective Intelligence**
- Woolley, A.W., Chabris, C.F., Pentland, A., Hashmi, N., & Malone, T.W. (2010). Evidence for a collective intelligence factor in the performance of human groups. *Science*, 330(6004), 686–688.
- Riedl, C., Fiore, S.M., Heiss, J., & Toth, P. (2026). Emergent coordination in multi-agent language models. *arXiv:2510.05174*.
- Maisto, D., Nuzzi, D., & Pezzulo, G. (2026). What the flock knows that the birds do not. *arXiv:2511.10835*.
- Barfuss, W., Flack, J.C., Gokhale, C., et al. (2023). Collective cooperative intelligence. *PNAS*, 120(8), e2209561120.

**Network Science, Game Theory, and Sociology**
- Nowak, M.A. (2006). Five rules for the evolution of cooperation. *Science*, 314(5805), 1560–1563.
- McPherson, M., Smith-Lovin, L., & Cook, J.M. (2001). Birds of a feather: Homophily in social networks. *Annual Review of Sociology*, 27, 415–444.
- Hong, L. & Page, S.E. (2004). Groups of diverse problem solvers can outperform groups of high-ability problem solvers. *PNAS*, 101(46), 16385–16389.
- Page, S.E. (2007). *The Difference*. Princeton University Press.
- Barabási, A.-L. & Albert, R. (1999). Emergence of scaling in random networks. *Science*, 286(5439), 509–512.
- Watts, D.J. & Strogatz, S.H. (1998). Collective dynamics of 'small-world' networks. *Nature*, 393, 440–442.
- Fischbacher, U., Gächter, S., & Fehr, E. (2001). Are people conditionally cooperative? *Economics Letters*, 71(3), 397–404.
- Granovetter, M.S. (1978). Threshold models of collective behavior. *American Journal of Sociology*, 83(6), 1420–1443.
- Jackson, M.O. (2008). *Social and Economic Networks: Models and Analysis*. Princeton University Press.
- Schelling, T.C. (1978). *Micromotives and Macrobehavior*. Norton.
- van de Ven, N., Zeelenberg, M., & Pieters, R. (2009). Leveling up and down: The experiences of benign and malicious envy. *Emotion*, 9(3), 419–429.
- Rustagi, D., Engel, S., & Kosfeld, M. (2010). Conditional cooperation and costly monitoring explain success in forest commons management. *Science*, 330(6006), 961–965.
- Wuchty, S., Jones, B.F., & Uzzi, B. (2007). The increasing dominance of teams in production of knowledge. *Science*, 316(5827), 1036–1039.

**Phase Transitions, Learning, and Mathematical Foundations**
- Wang, P. (2026). Grokking as dimensional phase transition in neural networks. *arXiv:2604.04655*.
- Alweiss, R., Lovett, S., Wu, K., & Zhang, J. (2021). Improved bounds for the sunflower lemma. *Annals of Mathematics*, 194(3), 795–815.
- Sawin, W. (2026). A quadratic improvement to the unit distance conjecture. *arXiv:2605.20579*.

**Mechanism Design and Information Economics**
- Myerson, R.B. (1981). Optimal auction design. *Mathematics of Operations Research*.
- Akerlof, G.A. (1970). The market for "lemons." *Quarterly Journal of Economics*.
- Bergemann, D., et al. (2026). Information Design and Mechanism Design: An Integrated Approach.
- Vickrey, W. (1961). Counterspeculation, auctions, and competitive sealed tenders. *Journal of Finance*.

**Institutional and Macroeconomics**
- Acemoglu, D. et al. Network fragility and institutions literature (various, 2020–2026).
- Ménard, C. & Shirley, M. (eds.) (2025). *Handbook of New Institutional Economics*.
- Lucas, R.E. (1972). Expectations and the neutrality of money. *Journal of Economic Theory*.
- Gagliardone, L., Gertler, M., Lenzu, S., & Tielens, J. (2025). Anatomy of the Phillips Curve. *American Economic Review*.
- Irani, R.M., et al. (2021). The rise of shadow banking. *Review of Financial Studies*.
- Calvo, G.A. & Végh, C.A. (1992). Currency substitution in developing countries. International Monetary Fund.
- Minsky, H.P. (1986). *Stabilizing an Unstable Economy*.
- Hogeveen, J., Inzlicht, M., & Obhi, S.S. (2014). Power changes motor resonance. *Journal of Experimental Psychology: General*, 143(2), 755–762.

**Active Inference and Bayesian Mechanics**
- Friston, K., Da Costa, L., et al. (2024). Designing ecosystems of intelligence from first principles. *Collective Intelligence*, 3(1).
- Tschantz, A., Mahajan, G., et al. (2025). As one and many. *Entropy*, 27(2), 143.
- Ramstead, M.J.D., et al. (2023). On Bayesian mechanics. *Interface Focus*, 13(3), 20220029.

---

**Companion Frameworks**: ERIE-SCHOOL lineage · THE-COORDINATION-BIFURCATION · THE-COLLECTIVE-OUTLIER · ECONOMICS · THE-ECONOMICS-OF-RECESS · THE-SINGULAR-COMPLETION

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · 2026*

---
© 2027 ERI Labs. All rights reserved.
