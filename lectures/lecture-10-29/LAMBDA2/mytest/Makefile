PYTHON ?= python3

.PHONY: check show-factorial

check:
	PYTHONPATH=.. $(PYTHON) check_examples.py

show-factorial:
	PYTHONPATH=.. $(PYTHON) -c 'from pathlib import Path; import lambda3 as L; source = Path("factorial.lam").read_text(); print(L.d0exp_compile(L.d0exp_parse(source)))'
