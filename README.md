# Python Module and OOP Assignment Notes

`Assignment  Module Assignment.ipynb` is a 53-cell mixed assignment notebook. It includes basic collection/control-flow exercises, small object-oriented class examples, module/file-operation exercises and later Flask/authentication/deployment notes.

## What is implemented versus described

Early sections contain runnable Python snippets and class definitions for student/library/account/animal/menu/room/member/event/flight exercises. These are in-memory teaching models, not complete operational management or booking systems.

Prompts mention files such as `constants.py`, `calculator.py`, `string_utils.py` and an ecommerce package. The repository contains only the notebook; those modules/package files are not supplied as a standalone implementation. Some corresponding functions are written inside notebook cells.

Later Flask material is mostly comments, string-wrapped sketches or prose. There is no complete runnable web app, template set, database configuration or deployment package in this repository. Do not infer completed signup/signin, production deployment or security from a prompt or pasted route sketch.

## Read and run carefully

Open with Jupyter or a notebook-capable editor using Python 3. Early examples use built-ins and the standard-library `math` module; the later Flask notes do not constitute a dependency environment.

Several cells request input or loop until a sentinel is entered. File helpers can read, overwrite or append files. One example writes `employees.txt` when executed. Use a disposable working directory and inspect cells before running them; do not run all cells against important local files.

## Known limits

One-based cells 48-50 contain plain-language steps in code cells and fail Python parsing. Cell 52 starts an unterminated triple-quoted route sketch and also fails parsing. The final cell is empty. Other string-wrapped examples do not execute their displayed code.

No full interactive run, file-write execution, database connection, authentication flow or deployment was performed during this documentation review. Class encapsulation and illustrative booking/account methods are not authorization, persistence or real-service integrations.

This README-only update preserves all original exercises, definitions, saved outputs, filename and history. It documents incomplete work rather than adding invented modules, applications or completion claims.
