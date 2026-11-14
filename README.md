# Dog Nutrition Review

A text-only assistant skill for evidence-led, owner-facing dog nutrition education.

## Scope

- Review food labels, portions, treats, body condition and weight trends.
- Show checked hypothetical calorie calculations with explicit assumptions and units.
- Prioritize urgent veterinary care when symptoms warrant it.
- Refer therapeutic diets, complete homemade recipes, growth and medically fragile dogs to qualified veterinary professionals.

This is not veterinary diagnosis, a treatment prescription, an official WSAVA/AAHA product, or a clinically validated calculator. It does not recommend a pet-food brand.

## Skill files

The installable skill is in [skills/review-dog-nutrition](skills/review-dog-nutrition):

- [SKILL.md](skills/review-dog-nutrition/SKILL.md): workflow and safety boundaries.
- [calculation-checks.md](skills/review-dog-nutrition/references/calculation-checks.md): units, equations, calorie allocation and reverse checks.
- [sources.md](skills/review-dog-nutrition/references/sources.md): direct professional and regulatory references.
- [openai.yaml](skills/review-dog-nutrition/agents/openai.yaml): presentation and invocation metadata.

Use the supported skill installation method of your assistant. In compatible clients, invoke review-dog-nutrition explicitly or allow relevant automatic invocation. Installing these text files does not grant tool or data-sharing permissions.

## Safety and review

The package contains no scripts, executable files, dependencies, credentials, scheduled tasks or automatic updates. Nutrition statements should be checked against current sources; formulas are estimates, not proof of the right intake for an individual animal.

Development review included 16 fictional calculation and safety scenarios. This limited review does not establish clinical efficacy, security certification or guaranteed future behavior.

## Sources and rights

The workflow uses original instructional wording and links to WSAVA, AAHA, AAFCO and other veterinary sources. Third-party documents, charts and software are not bundled. Their copyrights and terms remain with their owners.

No open-source license has been selected for this private repository.
