# Response to Referee Comments

**Manuscript:** Model MEML 75: Phenomenological Model of the 
Fermion Sector of the Standard Model from T²/ℤ₃ Geometry

**Author:** D. V. Yurov

**Date:** 2026

---

## Общее вступление

We thank the Referee for the careful reading of the manuscript and 
for the constructive comments. Below we address each point in detail. 
All changes to the manuscript are marked in the revised version.

We emphasize that the paper presents an **honest** phenomenological 
model with explicit separation between what is derived from first 
principles and what is phenomenological. We have strengthened this 
separation in the revised version.

---

## Referee Comment 1: "The model is not predictive in the quark sector"

**Comment:** With 11 parameters for 9 observables (2 extra DOF), the 
quark sector cannot be considered predictive.

**Response:** We agree completely. This limitation is explicitly 
stated in the Abstract, Section 6.4 (LOO analysis), and Section 9.1 
(open problems). We have added:

1. **Explicit LOO table** (Table 4) showing errors up to 796% for |V_ub| 
   and 372% for |J|.
2. **Clear statement** in the Abstract: "The model reproduces CKM but 
   does not predict it."
3. **Comparison with other modular models** (Feruglio 2017, 
   Kobayashi 2019) that have similar structure.

We do not claim predictivity in the quark sector. The main strict 
result of the paper is the derivation of **α_G = 2/(3π)**.

**Changes in manuscript:** §6.4, §8.1, Abstract.

---

## Referee Comment 2: "Fine-tuning of coefficients is not addressed"

**Comment:** The hierarchy of Yukawa coefficients ~10⁹ suggests 
significant fine-tuning.

**Response:** This concern was valid for the original version. We have 
addressed it in two ways:

1. **Reduced fine-tuning to Δ ~ 10⁵·¹³** by using modular forms of 
   different weights (Y^(2), Y^(4), Y^(6)) for different matrix 
   elements. See Section 6.3 and Eq. (14).

2. **Comparison with SM:** The hierarchy Δ ~ 10⁵·¹³ is comparable to 
   the Standard Model hierarchy y_t/y_u ~ 10⁵ and y_t/y_e ~ 10⁶. 
   Our model does not worsen the situation.

3. **Geometric interpretation:** The coefficients are now related to 
   overlaps of wavefunctions on T²/ℤ₃, opening a path to a 
   geometric explanation via flux stabilization.

**Changes in manuscript:** §6.3, Table 3.

---

## Referee Comment 3: "ε is not derived from geometry"

**Comment:** The suppression factor ε = 2.86×10⁻⁴ is a free 
parameter and is not derived from first principles. This undermines 
the claim of "geometry-derived" cosmology.

**Response:** We fully agree. The revised manuscript explicitly 
states:

> "Only α_G is derived from first principles. All other parameters 
> are phenomenological."

We have tested **30+ combinations** of modular forms, η-functions, 
and α_G. The best candidate is α_G⁵, which gives a **50% error** — 
insufficient for a derivation.

We have added this as the **first open problem** in Section 9.1 and 
as Phase I of the roadmap.

**Changes in manuscript:** Abstract, §3.1, §9.1, §10.

---

## Referee Comment 4: "Moduli stabilization is not demonstrated"

**Comment:** The moduli τ_u, τ_d are introduced phenomenologically. 
A realistic model must stabilize them.

**Response:** We agree. We have:

1. **Tested simple KKLT** — it does not produce a minimum at the 
   required points (τ_u ≈ −0.21 + 2.37i, τ_d ≈ 0.40 + 1.25i). 
   The result is documented in the supplementary Python script.

2. **Identified the required potential** — a multi-modulus flux 
   potential of the form
   W = W₀ + A_u e^(−c_u τ_u) + A_d e^(−c_d τ_d) + B e^(−b(τ_u+τ_d))

3. **Added to roadmap** (Phase I, high priority).

We do not claim that the model is fully stabilized. This is an 
honest limitation.

**Changes in manuscript:** §9.1, §10 (Phase I).

---

## Referee Comment 5: "θ_i = 1.112 is not a prediction"

**Comment:** The dark matter density Ω_a h² = 0.12 is achieved at 
θ_i = 1.112, but this value is not predicted by the model. Therefore 
the "dark matter prediction" is not a prediction.

**Response:** The Referee is correct. We have carefully rewritten 
Section 8.3:

> "The calculation is consistent. The value θ_i = 1.112 is natural 
> O(1), falling within the range expected for a pre-inflationary 
> axion. **However, θ_i is not predicted by the model.** This is 
> consistency, not prediction."

We added:
- rms value for uniform distribution: θ_i^rms = π/√3 ≈ 1.814;
- natural range: θ_i ∈ [0.5, 2.0];
- comparison table (Table 6) showing that θ_i = 1.112 is natural, 
  while 0.4342 would be anomalous.

To convert this into a prediction, θ_i must be derived from a 
specific inflation model. This is Phase I of the roadmap.

**Changes in manuscript:** §8.3, Abstract, §9.1.

---

## Referee Comment 6: "Comparison with other modular models is missing"

**Comment:** The paper should compare its results with other modular 
flavor models in the literature.

**Response:** We have added a brief comparison in Section 1 
(Introduction):

| Model | Group | Level | Main result |
|---|---|---|---|
| Feruglio 2017 | A₄ | 3 | Lepton mixing |
| Kobayashi 2019 | A₄ | 3, 5 | Quark+lepton |
| **MEML 75** | A₄ | 3 | α_G from geometry |

The key distinguishing feature of our work is the **strict derivation 
of α_G from the orbifold geometry**, which is not present in other 
models.

**Changes in manuscript:** §1.

---

## Referee Comment 7: "The CP phase δ_CP has 180° ambiguity"

**Comment:** The lepton CP phase is determined only up to a 180° 
shift, giving δ_CP ∈ {17°, 197°}. This is a serious limitation.

**Response:** The 180° ambiguity is a genuine feature of the modular 
A₄ level-3 structure. It arises from the discrete symmetry of the 
modular forms. We have:

1. **Explicitly stated** this in Section 5 and in the Abstract;
2. **Noted that it can be resolved** by future experiments (DUNE, 
   Hyper-K) which are sensitive to the sign of sin δ_CP;
3. **Not claimed** to determine δ_CP uniquely.

This ambiguity is not a defect — it is an honest feature of the 
model, consistent with the current experimental situation.

**Changes in manuscript:** §5, Abstract.

---

## Referee Comment 8: "RGE running is not discussed"

**Comment:** The paper does not discuss renormalization group 
evolution from the high scale to M_Z.

**Response:** We agree this is important. We have:

1. **Added a brief discussion** in Section 8.4 explaining that 
   one-loop RGE corrections are small for the ratio 
   Δm²₂₁/Δm²₃₁ (~1%).

2. **Noted the limitation** — a full two-loop analysis would require 
   specifying the complete UV completion, which is beyond the scope 
   of the present work.

3. **Added to the roadmap** as a future task.

**Changes in manuscript:** §8.4, §9.1.

---

## Referee Comment 9: "The number of parameters is too large"

**Comment:** 11 parameters for the quark sector is comparable to 
the SM (13 Yukawa couplings + 4 CKM parameters = 17). What is 
the advantage?

**Response:** The advantage is **structural**, not numerical:

1. **SM:** 17 arbitrary parameters with no explanation.
2. **MEML 75:** 11 parameters with geometric origin 
   (τ_u, τ_d, coefficients from modular form overlaps).

The model provides:
- Topological explanation for 3 generations (3 fixed points);
- Natural hierarchy from modular form weights;
- Connection to cosmology (axion, dark matter).

We do not claim to reduce the number of parameters — we claim to 
give them geometric meaning.

**Changes in manuscript:** §6.1, §7.

---

## Referee Comment 10: "How do you respond to the claim that the axion is not a genuine prediction?"

**Comment:** Since ε is phenomenological, the axion mass and 
frequency are not genuine predictions.

**Response:** Correct. We have carefully rewritten Section 3.4:

> "The values f_a, m_a, ν_a **depend on** the phenomenological 
> parameter ε. The analytical expression for ε through geometric 
> invariants was not found. Therefore, these values are 
> **conditional predictions** given ε = 2.860924×10⁻⁴, not strict 
> predictions from first principles."

We have also added a status table (Table 1) that explicitly 
categorizes every quantity as:
- ✅ Strictly derived
- ⚠️ Conditionally derived
- ❌ Phenomenological
- ✅ Reproduced
- ⚠️ Consistent (not predicted)

**Changes in manuscript:** §3.4, Table 1, Abstract.

---

## Summary of changes in the revised manuscript

| Section | Change |
|---|---|
| Abstract | Added honest separation of derived vs phenomenological |
| §1 | Added comparison with other modular models |
| §3.1 | Stated α_G as the only strict derivation |
| §3.4 | Added conditional status of axion predictions |
| §5 | Added 180° ambiguity discussion |
| §6.3 | Reduced fine-tuning to Δ ~ 10⁵·¹³ |
| §6.4 | Added LOO analysis (Table 4) |
| §8.3 | Added θ_i interpretation |
| §8.4 | Added RGE discussion |
| §9.1 | Expanded open problems (5 items) |
| §10 | Roadmap without calendar dates |
| References | Added Preskill 1983 |

---

## Concluding remark

We thank the Referee again for the thorough review. We believe the 
revised manuscript is significantly stronger due to the explicit 
identification of limitations and the honest separation between 
strict derivations and phenomenological inputs.

The main contribution of the work — the strict derivation of 
**α_G = 2/(3π) = 0.212207** and the coincidence of M₆ with the 
GUT scale — remains unchanged and is, in our view, sufficient to 
justify publication in Physical Review D as a phenomenological 
study.

We hope the revised manuscript now meets the standards of the 
journal.

---

Sincerely,

D. V. Yurov