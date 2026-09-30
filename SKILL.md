---
description: Forces website agents to produce brief-specific,
  structurally distinct, high-quality interfaces instead of converging
  on generic AI templates. Apply to website, landing page, frontend,
  product-site, portfolio, campaign-site, and interactive web-design
  tasks.
name: creative-diversity
version: 1
---

# Creative Diversity

## Purpose

Create websites that feel intentionally art-directed for the specific
brief.

A successful result must be:

-   appropriate to the product, audience, and content;
-   visually coherent;
-   structurally distinctive;
-   usable and responsive;
-   accessible;
-   technically sound;
-   meaningfully different from generic AI-generated landing pages.

Originality is not decoration. Changing colors, fonts, icons, copy,
gradients, or images on the same underlying layout does **not**
constitute a different design.

Do not optimize for novelty at the expense of usability. The goal is
**appropriate distinction**, not randomness.

------------------------------------------------------------------------

## 1. Non-negotiable workflow

For every website task, follow this order:

1.  Understand the brief.
2.  Extract design constraints.
3.  Generate three materially different concept directions.
4.  Select the direction that best fits the brief.
5.  Create a Design Genome.
6.  Identify common/default patterns to avoid.
7.  Define one project-specific Signature Element.
8.  Implement.
9.  Validate functionality, responsiveness, and accessibility.
10. Run the Genericity Test and Structural Diversity Review.
11. Revise generic elements before delivery.

Do not begin implementation before steps 1--7 are complete internally.

------------------------------------------------------------------------

## 2. Brief analysis

Determine:

-   site purpose;
-   primary audience;
-   primary user action;
-   content hierarchy;
-   brand/product personality;
-   trust requirements;
-   accessibility requirements;
-   device priorities;
-   technical constraints;
-   required components;
-   available assets;
-   subject-specific visual opportunities.

Derive the design from the brief.

Do not start from a preferred template and force the brief into it.

------------------------------------------------------------------------

## 3. Concept divergence

Generate three concepts that differ **structurally**, not cosmetically.

Each concept should make different decisions about at least five of:

-   composition;
-   information hierarchy;
-   navigation;
-   hero structure;
-   typography;
-   section rhythm;
-   content density;
-   geometry;
-   image treatment;
-   interaction model;
-   motion language;
-   use of whitespace;
-   content progression.

Bad divergence:

-   Concept A: blue cards
-   Concept B: red cards
-   Concept C: green cards

Good divergence:

-   Concept A: editorial index with strong typography and asymmetric
    chapters;
-   Concept B: immersive full-viewport narrative with spatial
    transitions;
-   Concept C: dense modular interface organized around
    tools/data/content.

Select the concept because it best serves the brief, not because it is
easiest to code.

------------------------------------------------------------------------

## 4. Design Genome

Before implementation, establish an internal Design Genome:

``` yaml
design_genome:
  archetype:
  composition:
  information_hierarchy:
  navigation_model:
  hero_strategy:
  typography_strategy:
  geometry:
  spacing_rhythm:
  density:
  color_strategy:
  image_strategy:
  motion_language:
  interaction_language:
  signature_element:
  intentional_avoidances:
```

Values must describe actual design decisions.

Example:

``` yaml
design_genome:
  archetype: "editorial technology"
  composition: "asymmetric chapter grid"
  information_hierarchy: "headline-led progressive disclosure"
  navigation_model: "persistent vertical index"
  hero_strategy: "typographic statement with contextual visual"
  typography_strategy: "large grotesk display + restrained reading face"
  geometry: "sharp, thin-rule divisions"
  spacing_rhythm: "alternating compressed and expansive sections"
  density: "medium-low"
  color_strategy: "warm neutral base with one signal color"
  image_strategy: "cropped documentary imagery"
  motion_language: "restrained directional transitions"
  interaction_language: "chapter exploration"
  signature_element: "interactive vertical project index"
  intentional_avoidances:
    - "generic centered SaaS hero"
    - "three equal feature cards"
    - "decorative glass panels"
```

The genome is a decision framework, not a checklist to display to the
end user.

------------------------------------------------------------------------

## 5. Creative seed

If the runtime provides an agent ID, job ID, task ID, or creative seed,
use it as a **diversity influence**, never as a source of arbitrary
styling.

Recommended deterministic seed:

``` text
creative_seed = hash(agent_id + job_id)
```

Use the seed to bias choices among several brief-compatible directions,
such as:

-   composition family;
-   typographic character;
-   density;
-   geometry;
-   motion intensity;
-   navigation treatment;
-   image treatment;
-   experimental intensity.

The brief always outranks the seed.

A medical portal must not become difficult to use because a seed
selected high experimentation. A cultural campaign may support much
greater visual risk.

------------------------------------------------------------------------

## 6. Anti-template policy

Do not automatically reach for patterns commonly overproduced by AI
website generators.

Patterns requiring justification include:

-   centered headline/subheadline/two-button hero;
-   three equal feature cards;
-   repeated bento grids;
-   endless rounded rectangles;
-   excessive pill-shaped UI;
-   purple/blue gradient SaaS styling;
-   gradient text used as decoration;
-   glassmorphism without functional purpose;
-   generic dashboard mockups;
-   floating cards around a centered product image;
-   predictable alternating image/text sections;
-   generic logo-cloud sections;
-   generic testimonial-card grids;
-   decorative blobs and glow effects;
-   excessive icon-in-card sections;
-   identical border radius across every object;
-   identical section spacing throughout the page;
-   gratuitous scroll animations;
-   generic "future of X" visual language.

These patterns are not prohibited.

Use them when the brief genuinely benefits from them. When used, adapt
them to the content rather than reproducing the default form.

Never make a design "different" by simply swapping the gradient, border
radius, font, or stock imagery.

------------------------------------------------------------------------

## 7. Project-specific Signature Element

Every substantial website should contain at least one recognizable
design or interaction idea derived from the project's subject.

A Signature Element may be:

-   a navigation behavior;
-   a content-exploration mechanism;
-   a visualization;
-   a distinctive layout system;
-   a subject-specific interaction;
-   an unusual but usable transition;
-   a custom typographic behavior;
-   an interactive diagram;
-   a narrative device;
-   a unique content transformation.

Examples:

-   architecture studio → navigable floor-plan project index;
-   music platform → waveform-driven discovery interface;
-   space project → orbital content navigation;
-   publishing site → editorial margin annotation system;
-   logistics product → route-based information architecture.

Do not add a gimmick merely to satisfy this requirement.

The signature must strengthen the site's purpose or identity.

------------------------------------------------------------------------

## 8. Structural diversity rules

When seeking a different design, vary high-level structure first.

Priority order:

1.  information architecture;
2.  composition;
3.  hierarchy;
4.  navigation;
5.  content rhythm;
6.  interaction model;
7.  typography;
8.  imagery;
9.  motion;
10. color and surface styling.

The first six matter more for diversity than the last four.

A recolored clone is still a clone.

------------------------------------------------------------------------

## 9. Typography

Typography must have a reason.

Avoid defaulting to oversized sans-serif headlines merely because they
look contemporary.

Consider:

-   editorial serif/sans relationships;
-   condensed display faces;
-   monospace where conceptually relevant;
-   restrained single-family systems;
-   scale contrast;
-   unconventional but readable alignment;
-   line length;
-   rhythm;
-   hierarchy.

Prioritize readability for body content and controls.

Do not sacrifice accessibility for visual novelty.

------------------------------------------------------------------------

## 10. Motion and interaction

Motion should communicate hierarchy, causality, state, direction, or
character.

Do not animate everything.

Prefer:

-   meaningful state transitions;
-   spatial continuity;
-   responsive feedback;
-   section-specific interaction;
-   subtle choreography.

Avoid:

-   identical fade-up animation on every element;
-   excessive parallax;
-   animation that delays access to content;
-   motion that harms keyboard or reduced-motion users.

Respect `prefers-reduced-motion`.

------------------------------------------------------------------------

## 11. Responsive design

Mobile must be intentionally composed, not merely a collapsed desktop.

Review:

-   reading order;
-   navigation transformation;
-   touch targets;
-   typography scaling;
-   image crops;
-   complex interactions;
-   horizontal overflow;
-   content priority;
-   sticky/fixed elements.

If the desktop Signature Element cannot work on mobile, design an
equivalent mobile behavior rather than simply removing core
functionality.

------------------------------------------------------------------------

## 12. Accessibility and usability

Creative diversity never overrides:

-   semantic HTML;
-   keyboard navigation;
-   visible focus;
-   sufficient contrast;
-   meaningful labels;
-   appropriate headings;
-   form usability;
-   reduced-motion support;
-   responsive behavior;
-   readable type;
-   understandable navigation.

Experimental does not mean confusing.

------------------------------------------------------------------------

## 13. Genericity Test

Before delivery, ask:

> If the logo, product name, copy, and images were replaced, could this
> exact design plausibly be used for an unrelated AI-generated website?

If the answer is clearly yes, identify why.

Check for:

-   generic hero composition;
-   generic card grammar;
-   generic section sequence;
-   generic typography;
-   generic visual effects;
-   generic interaction;
-   lack of subject-specific design logic.

Then revise the weakest generic elements.

Do not respond to this test by adding more decoration.

Change structure or interaction where appropriate.

------------------------------------------------------------------------

## 14. Self-critique

Perform a final internal review:

### Brief fit

-   Does the visual language emerge from the subject?
-   Does the hierarchy support the primary user goal?

### Distinction

-   Is there a recognizable design idea?
-   Is variation structural rather than cosmetic?
-   Is the Signature Element meaningful?

### Coherence

-   Do typography, geometry, spacing, imagery, and motion belong to the
    same system?
-   Is novelty controlled rather than random?

### Usability

-   Is navigation obvious enough?
-   Is important content easy to find?
-   Does mobile remain intentional?

### Technical quality

-   Does the project build?
-   Does typecheck/lint pass when available?
-   Are interactions functional?
-   Are there broken assets, overflow, console errors, or dead controls?

Revise before submission if any critical answer is no.

------------------------------------------------------------------------

## 15. Optional design fingerprint

When the task/runtime supports metadata artifacts, emit a lightweight
design fingerprint for network-level diversity checks.

Suggested schema:

``` json
{
  "schema": "imd.design-fingerprint.v1",
  "archetype": "editorial-tech",
  "composition": "asymmetric-chapters",
  "navigation": "vertical-index",
  "hero": "typographic-contextual",
  "typography": "display-grotesk",
  "geometry": "sharp",
  "density": 0.38,
  "color_strategy": "neutral-plus-signal",
  "motion": "restrained-directional",
  "interaction": "chapter-exploration",
  "signature": "interactive-project-index"
}
```

This artifact should describe the design; it must not contain secrets,
credentials, private user data, or unnecessary source content.

------------------------------------------------------------------------

## 16. Network-level similarity handling

If a verifier provides similarity feedback such as:

``` text
DESIGN_TOO_SIMILAR
```

do not merely:

-   recolor;
-   change fonts;
-   replace images;
-   alter border radius;
-   reorder otherwise identical cards.

Preserve the requirements and functionality, then change the strongest
structural similarities:

-   composition;
-   hero architecture;
-   navigation;
-   section progression;
-   information hierarchy;
-   interaction model;
-   signature element.

Re-run validation after redesign.

------------------------------------------------------------------------

## 17. What must remain deterministic

Creative diversity must never create instability in:

-   required functionality;
-   data behavior;
-   API contracts;
-   forms;
-   routes;
-   security;
-   accessibility;
-   required copy;
-   user-specified branding;
-   build and deployment behavior.

The creative layer changes presentation and interaction strategy, not
contractual requirements.

------------------------------------------------------------------------

## 18. Priority order

When requirements conflict, use this priority:

1.  explicit user requirements;
2.  functional correctness and security;
3.  accessibility and usability;
4.  content clarity;
5.  brand/brief fit;
6.  coherent creative direction;
7.  diversity/novelty.

Never violate a higher priority merely to obtain a more unusual website.

------------------------------------------------------------------------

## 19. Completion criteria

A website is ready only when:

-   required functionality works;
-   the layout is responsive;
-   accessibility basics are satisfied;
-   the design clearly fits the brief;
-   the result has a coherent Design Genome;
-   generic AI defaults were not used without reason;
-   at least one meaningful Signature Element exists for substantial
    creative builds;
-   diversity is structural rather than cosmetic;
-   the Genericity Test has been performed;
-   obvious genericity discovered during review has been corrected.

The objective is not to make every website strange.

The objective is to make every website feel **designed for its own
reason to exist**.

------------------------------------------------------------------------

# 20. Web3 / DeFi / Crypto Product Intelligence

Apply this section when the brief involves blockchain, cryptocurrency,
DeFi, NFTs, DAOs, wallets, trading, on-chain analytics, explorers,
tokenized assets, staking, lending, bridges, launch platforms,
prediction markets, or related financial interfaces.

The objective is not to make a conventional website with crypto
decoration. The interface must reflect the actual transaction model,
data density, risk, and user intent of the product.

## 20.1 Classify the product first

Identify the product type before designing:

-   DEX / swap;
-   aggregator;
-   bridge / cross-chain transfer;
-   staking / restaking;
-   lending / borrowing;
-   liquidity pools / LP management;
-   yield / vault products;
-   perpetuals / derivatives / spot trading;
-   portfolio / treasury management;
-   token analytics;
-   blockchain explorer;
-   wallet;
-   NFT marketplace / collection / mint;
-   DAO / governance;
-   launchpad / token distribution;
-   prediction market;
-   payments;
-   token/project website;
-   protocol documentation;
-   institutional/on-chain finance.

Do not apply the same dashboard structure to every category.

## 20.2 Web3 Design Genome extension

Extend the normal Design Genome when relevant:

``` yaml
web3_genome:
  domain:
  product_type:
  chain_context:
  wallet_context:
  transaction_frequency:
  transaction_ux:
  data_density:
  market_data_priority:
  risk_visibility:
  chart_language:
  position_visibility:
  approval_model:
  network_switching:
  signature_element:
```

The values must follow the actual product requirements.

## 20.3 Transaction UX

For value-moving actions, prioritize comprehension over visual novelty.

Where applicable, clearly expose:

-   asset/token;
-   amount;
-   fiat/reference value when available;
-   source and destination chain;
-   source and destination address/context;
-   exchange rate;
-   price impact;
-   slippage tolerance;
-   minimum received;
-   protocol/network fees;
-   gas estimate;
-   route;
-   approval requirement;
-   allowance implications;
-   expected transaction sequence;
-   pending state;
-   success/failure state;
-   transaction hash/explorer path;
-   warnings and irreversible consequences.

Never visually disguise a transaction, approval, signature, fee, or
destination.

A primary action must describe what the user is actually doing. Prefer
precise labels such as `Swap`, `Bridge`, `Supply`, `Borrow`, `Repay`,
`Stake`, `Unstake`, `Claim`, `Approve` or `Confirm` over ambiguous
labels when the action moves value.

## 20.4 Wallet and chain context

When relevant, make the current wallet/network context understandable
without dominating the interface.

Support appropriate states for:

-   disconnected wallet;
-   connected wallet;
-   wrong network;
-   unsupported network;
-   network switching;
-   insufficient native gas token;
-   insufficient balance;
-   pending signature;
-   rejected signature;
-   transaction submitted;
-   transaction confirmed;
-   transaction failed.

Never assume wallet connection succeeded.

Never represent a wallet signature as harmless login when it carries
permissions or transaction consequences.

## 20.5 Financial data integrity

Never fabricate live-looking financial data as if it were real.

This includes:

-   token prices;
-   balances;
-   TVL;
-   APY/APR;
-   market capitalization;
-   volume;
-   PnL;
-   liquidity;
-   yields;
-   rewards;
-   gas;
-   transaction status;
-   historical performance.

When real data is unavailable, use clearly identified sample/mock/demo
data or neutral placeholders.

Preserve precision. Do not silently round values in a way that changes
financial meaning.

Distinguish where relevant:

-   token amount vs fiat value;
-   APR vs APY;
-   realized vs unrealized PnL;
-   supplied vs borrowed value;
-   available vs locked balance;
-   estimated vs confirmed values;
-   current vs historical values.

## 20.6 Risk communication

Risk information is part of the product interface, not footer
decoration.

Surface relevant risks close to the action, including where applicable:

-   liquidation risk;
-   health factor;
-   collateral ratio;
-   price impact;
-   slippage;
-   smart-contract risk;
-   bridge/finality assumptions;
-   lock periods;
-   withdrawal delays;
-   variable yield;
-   impermanent loss;
-   oracle dependencies;
-   approval/allowance scope;
-   leverage;
-   network mismatch.

Do not use visual design to minimize or obscure material risk.

Do not imply guaranteed yield, profit, safety, or future performance
unless the supplied content legitimately establishes the claim.

## 20.7 Trading interfaces

Trading products may legitimately require high information density.

Design hierarchy around decision-making rather than decoration.

Potential components include:

-   market/pair selector;
-   price and percentage movement;
-   candlestick/market chart;
-   order book;
-   recent trades;
-   order entry;
-   positions;
-   open orders;
-   order history;
-   leverage/margin controls;
-   liquidation information;
-   PnL;
-   funding/fees;
-   account collateral.

Do not include every component merely because other exchanges do.

For mobile, determine which information is essential for the current
action and create deliberate modes/tabs rather than shrinking a desktop
terminal into an unreadable screen.

## 20.8 DEX / Swap

A swap interface should make the exchange relationship immediately
understandable.

Consider:

-   token selector;
-   amount;
-   balance;
-   quote;
-   route;
-   rate;
-   fee;
-   price impact;
-   slippage;
-   minimum received;
-   approval state;
-   swap state.

Avoid cloning the standard centered floating swap-card by default.

The swap mechanism can participate in a broader, project-specific
composition while remaining obvious and safe.

## 20.9 Lending / Borrowing

Prioritize:

-   supplied assets;
-   borrowed assets;
-   collateral status;
-   available capacity;
-   rates;
-   health factor;
-   liquidation threshold/risk;
-   repay/withdraw consequences.

Risk-changing actions should visibly show their expected effect before
confirmation when the required data exists.

## 20.10 Staking / Yield / Vaults

Distinguish clearly among:

-   deposited/staked principal;
-   rewards;
-   lock status;
-   unlock/withdrawal conditions;
-   APR/APY;
-   variable vs fixed characteristics;
-   strategy description;
-   relevant risk.

Avoid presenting high yield as decorative marketing without context.

## 20.11 Bridges

Bridge UX must make source and destination contexts unmistakable.

Where available, expose:

-   source chain;
-   destination chain;
-   source asset;
-   destination asset;
-   amount;
-   fees;
-   estimated route/time;
-   destination address if different;
-   bridge status;
-   required approvals/transactions.

Do not allow chain direction to become visually ambiguous.

## 20.12 NFT experiences

Do not default every NFT project to neon gradients, floating 3D cards,
or generic marketplace grids.

Derive the design from the collection/project.

For marketplaces or collections, consider:

-   ownership;
-   collection identity;
-   traits;
-   rarity information when legitimate;
-   floor/listing context;
-   offers/bids;
-   provenance;
-   chain;
-   token ID;
-   contract verification/context;
-   transaction state.

For mint flows, clearly distinguish:

-   eligibility;
-   quantity;
-   price;
-   network;
-   supply;
-   mint state;
-   wallet state;
-   transaction state.

Never create false scarcity, fake countdowns, fake sales, or misleading
wallet prompts.

## 20.13 DAO / Governance

Governance interfaces should emphasize:

-   proposal state;
-   proposal content;
-   author/proposer;
-   voting period;
-   quorum/threshold where applicable;
-   voting power;
-   choices;
-   execution state;
-   discussion/context;
-   historical decisions.

Do not turn governance into a decorative token dashboard.

## 20.14 Blockchain explorers and analytics

For explorers and analytics products, optimize for scanning,
verification, and navigation across entities.

Potential entities include:

-   address;
-   transaction;
-   block;
-   token;
-   contract;
-   validator;
-   event/log;
-   NFT;
-   chain/network.

Use typography, tables, grouping, labels, and progressive disclosure to
manage density.

Long addresses/hashes may be visually shortened only when the full value
remains accessible/copyable where appropriate.

Differentiate verified facts from derived analytics or estimates.

## 20.15 Token/project websites

A token/project marketing site must not automatically become a generic
meme-token or cyberpunk landing page.

Derive the visual identity from:

-   actual project purpose;
-   community;
-   protocol mechanics;
-   utility;
-   ecosystem;
-   documentation;
-   roadmap/status;
-   brand assets.

Avoid generic rockets, coins, candlesticks, astronauts, glowing chains,
cyber grids, and "to the moon" imagery unless the brief intentionally
calls for them.

## 20.16 Web3 anti-template additions

The following patterns require justification:

-   centered swap card copied from familiar DEX interfaces;
-   dark navy + purple neon as automatic crypto styling;
-   glowing token coin in every hero;
-   floating glass wallet cards;
-   generic candlestick chart used as decoration;
-   cyber-grid backgrounds;
-   random blockchain-node illustrations;
-   identical token-stat cards;
-   fake terminal aesthetics;
-   excessive green/red market coloring outside meaningful financial
    states;
-   giant APY used as the primary visual without risk context;
-   wallet-connect button treated as the entire information
    architecture.

Familiar interaction conventions may be retained when they reduce
transaction risk. Originality must not make financial actions harder to
understand.

## 20.17 Web3 signature elements

Strong project-specific signatures might include:

-   live liquidity-depth visualization;
-   route-oriented bridge visualization;
-   collateral/health-factor spatial model;
-   protocol-flow diagram integrated into navigation;
-   governance timeline;
-   treasury topology;
-   wallet activity narrative;
-   transaction lifecycle visualization;
-   on-chain relationship map;
-   market-regime visualization;
-   NFT trait explorer tailored to the collection.

A signature must help explain or operate the product. Do not add
computationally expensive visualizations with no user value.

## 20.18 Security-sensitive UI rules

Never:

-   request or display seed phrases/private keys;
-   imply a signature is risk-free without basis;
-   conceal token approvals;
-   preselect deceptive transaction permissions;
-   make a destructive/value-moving action visually indistinguishable
    from navigation;
-   imitate another protocol in a way that could confuse users about
    identity;
-   use fake verification/security badges;
-   hide destination addresses or material fees;
-   create dark patterns around wallet connection or approvals.

For destructive or high-impact actions, use appropriate confirmation and
clear consequence language.

## 20.19 Web3 responsive behavior

Do not force desktop trading density onto small screens.

On mobile:

-   prioritize the active transaction/action;
-   use deliberate views for chart/order book/positions where necessary;
-   preserve critical risk and fee information;
-   keep wallet/network context accessible;
-   maintain adequate touch targets;
-   prevent numeric input errors;
-   avoid hiding critical confirmation details behind decorative
    interactions.

## 20.20 Web3 diversity principle

Web3 familiarity and originality are compatible.

Keep conventions that protect users:

-   recognizable asset selectors;
-   explicit transaction confirmation;
-   clear wallet/network state;
-   familiar numeric input;
-   readable risk information.

Innovate around:

-   information architecture;
-   visualization;
-   navigation;
-   content storytelling;
-   protocol explanation;
-   layout composition;
-   project-specific interactions;
-   data exploration.

The objective is not to reinvent the `Confirm` button.

The objective is to prevent every DeFi product from looking like the
same exchange with a different logo.

------------------------------------------------------------------------

# 21. Extended domain coverage

The Creative Diversity protocol also applies to:

-   fintech;
-   banking;
-   SaaS;
-   AI products;
-   developer tools;
-   data products;
-   marketplaces;
-   e-commerce;
-   games;
-   media;
-   music;
-   entertainment;
-   portfolios;
-   agencies;
-   architecture;
-   fashion;
-   luxury;
-   education;
-   communities;
-   documentation;
-   dashboards;
-   mobile-first web applications.

For every domain, derive the visual system from the actual user task and
subject matter rather than importing a fashionable template from another
category.

------------------------------------------------------------------------

# 22. Final principle

A network of independent agents should not look like one designer
repeatedly changing themes.

Each result should preserve the reliability of a shared engineering
standard while expressing a design system appropriate to its own brief,
domain, audience, and interaction model.

For Web3 and financial products, creative distinction is subordinate to
transaction clarity, data integrity, risk visibility, security,
accessibility, and user control.
