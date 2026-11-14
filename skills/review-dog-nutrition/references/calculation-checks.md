# Calculation Checks

Use for educational arithmetic and bounded healthy-adult estimates. Do not treat these equations as a patient-specific prescription.

## Inputs and units

- Require positive, finite weight and energy density. Ask when units are missing or inconsistent. Reject zero, negative or nonsensical values.
- Convert pounds to kilograms by multiplying by 0.45359237. Use kilograms in the exponent.
- Identify whether a supplied weight is current, hypothetical or a veterinarian-set target. Do not silently swap them.
- Use the exact product's labeled metabolizable energy in kcal/kg, kcal/cup, kcal/can or kcal/serving. Do not equate a cup to a fixed gram weight. Keep kilocalories distinct from kilojoules; 1 kcal = 4.184 kJ.

## Equations

RER (kcal/day) = 70 × (weight in kg)^0.75.

Estimated maintenance energy (kcal/day) = RER × a justified life-stage/activity factor.

AAHA's published starting ranges include 1.4–1.6 for neutered adult dogs and 1.0–1.2 for inactive/obesity-prone adults. These overlap with individual variation; do not automatically assign a factor by neuter status alone. Explain and label any chosen factor. Recheck the current AAHA table rather than copying factors for growth, reproduction, illness or weight loss into this workflow.

When a user supplies a factor for a hypothetical exercise, use it and identify it as an assumption, not a clinically recommended factor.

## Allocate calories before converting to food

Total daily estimate includes extras. Let E be calories from treats, toppers, supplements and other foods:
- Main-food calories = total estimate − E.
- Grams/day = main-food kcal/day × 1000 ÷ labeled kcal/kg.
- Cups/day = main-food kcal/day ÷ labeled kcal/cup.
- Cans/day = main-food kcal/day ÷ labeled kcal/can.

Do not subtract a hypothetical 10% and then add the actual treats again. Do not add treats on top of a calorie target that already includes them. If extras exceed 10% in a routine healthy-dog plan, flag the nutritional balance issue; subtracting them from complete food does not fix that issue. If E exceeds the total, stop and clarify.

For arithmetic-only questions, explicitly label any zero-extras assumption. Do not present a real feeding recommendation as complete while extras are unknown.

## Verification

1. Compute with a trusted calculator or a small calculation written for this task, not third-party downloaded code.
2. Independently check conversion and exponent order. Do not use 70 × weight × 0.75.
3. Retain precision until final display; round practical food amounts appropriately and avoid false precision.
4. Reverse-check: portion × product energy density + extras should recover the total within rounding tolerance.
5. Distinguish daily amount from amount per meal; divide only after stating meal count.
6. State that an equation cannot predict a precise weekly weight-loss rate. Do not derive one from kilograms or percentages alone.
7. For a real animal, recommend monitoring weight, body/muscle condition, appetite and tolerance with veterinary adjustment where needed.

Primary equation and factors: [AAHA energy requirements](https://www.aaha.org/wp-content/uploads/globalassets/02-guidelines/2021-nutrition-and-weight-management/resourcepdfs/nutritiongl_box1.pdf). The table describes estimates, not a universal standard of care.
