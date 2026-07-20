# RAPID-MFA Table of contents

`RAPID-MFA-0: RAPID-MFA's conventions and common data structures`: Defines the basic building blocks of RAPID-MFA and their logic, including its modeling conventions, terminology, formats, and data structures.

`RAPID-MFA-1: The flow driven model`: The basic RAPID MFA flow driven model, explained step by step with the corresponding modeling equations. It's also the core building block for all other RAPID-MFA notebooks that use the flow driven model.

`RAPID-MFA-2: The stock driven model`: The basic RAPID MFA stock driven model, explained step by step with the corresponding modeling equations. It's also the core building block for all other RAPID-MFA notebooks that use the stock driven model.

`RAPID-MFA-3 The flow driven model with outflow generation curve`: This variant of the flow driven model utilizes an _outflow  generation curve_ instead of `RAPID-MFA-1`'s _survival curve_ as an input to the model, with the corresponding changes to the modeling equations. It also explains when to use each of these two variants.

`RAPID-MFA-4 The stock driven model with outflow generation curve`: This variant of the stock driven model utilizes an _outflow  generation curve_ instead of `RAPID-MFA-2`'s _survival curve_ as an input to the model, with the corresponding changes to the modeling equations. It also explains when to use each of these two variants.

`RAPID-MFA-5: A library of survival curves`: A selection of pairs of survival curves and outflow generation curves that are commonly used in dynamic MFA models, ready to be copied and pasted into any RAPID-MFA models. It also covers the mathematical relations between survival curves and outflow generation curves and how to consistently convert between them in Python, and notes and visualizations of the different curves.

`RAPID-MFA-6a: One-off varying lifetime` and `RAPID-MFA-6b: Varying lifetime over time`: Models in which lifetimes are not identical for all inflow cohorts. In `6a`, inflows from a certain timeframe onward have a new survival curve. In `6b`, inflows cohorts' lifetimes gradually change so each cohort has its own unique survival curve.

`RAPID-MFA-7a: Fixed recycling rate` and `RAPID-MFA-7b: Recycling rate increases gradually`: Models that extend the core dynamic MFA models to include recovery from outflow that replaces some of the virgin inflows, a basic extension of the core dynamic MFA models to also include upstream and downstream processes. In `7a`, the _transfer coefficient_ of % recovered from outflows is a fixed value, and in `7b` the recovery transfer coefficient changes over time. These models also describe how to account the _overflow_'_ of more recycled materials than required to meet inflows demands.

`RAPID-MFA-8: Splitting inflows for maintenance and for expansion`: dissagregate the inflows into their two purposes, and how this differs when the stocks grow, stabilize, and decline. This dissagregation can only be calculated after a full calculation of the entire basic dynamic MFA system.

`RAPID-MFA-9: Switching from products/services to materials with changing material compositions`: The basic RAPID MFA model of both products and materials within them, also known as the "demand-driven model" / "services-products-materials cascade" / "Müller 2006-style model" / "multi-layer dynamic model" / "stocks-flows-services nexus model" and many other names. It also introduces the __material intensity__ coefficient and the modeling of material compositions that change over time, to show how the flows and stocks of products diverge from the flows and stocks of a material within those products in such cases, as well as the _material stock productivity_ indicator.

RAPID-MFA-10a: Immediate material substitution: models two materials in one product and a substitution between them from a specific point in time onwards.

RAPID-MFA-10b: Material substitution over time: models two materials in one product and a gradual substitution between them.

