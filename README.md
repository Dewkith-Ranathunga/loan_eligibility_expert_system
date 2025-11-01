# Loan Eligibility Expert System

This repository contains a simple rule-based expert system written in Prolog for determining loan eligibility. It encodes rules and facts to evaluate whether an applicant qualifies for a particular loan based on criteria such as income, credit history, employment status, and collateral.

## Features

- Rule-based decision logic implemented in Prolog (.pl).
- Simple facts and rules that can be extended for additional criteria.
- Interactive usage via a Prolog REPL (for example, SWI-Prolog).

## Files

- `loan_eligibility_expert_system.pl` — Main Prolog source containing facts and rules for loan eligibility.

## Requirements

- SWI-Prolog (recommended) or another Prolog interpreter.

## Quick start

1. Install SWI-Prolog: https://www.swi-prolog.org/
2. Open a terminal in this repository:

```sh
cd e:\ExpertSystem
```

3. Start SWI-Prolog and load the program:

```sh
swipl -s loan_eligibility_expert_system.pl
```

4. Query the system according to the predicates defined in the file. Example (predicate names depend on the source):

```prolog
?- eligible_for_loan(Applicant).
```

Replace `eligible_for_loan/1` with the actual predicate(s) defined in the `.pl` file. Inspect the top of `loan_eligibility_expert_system.pl` for usage examples and available queries.

## Contributing

Contributions are welcome. If you add new rules or predicates, please:

- Add clear comments explaining new rules.
- Include example queries and expected outputs.

## License

This project is provided without an explicit license. If you want to publish it under a specific license (MIT, Apache-2.0, GPL, etc.), add a `LICENSE` file.

## Contact

Repo owner: Dewkith-Ranathunga
