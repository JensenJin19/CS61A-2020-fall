# Getting Started

## nteractive Sessions

- **Starting Python**: Use the terminal or Python application to start an interactive session.
- **Using the Interpreter**: Type commands after the prompt `>>>`, access history with `<Control>-P` and `<Control>-N`, and exit with `<Control>-D`.

### First Example

- **Statements and Expression**s: Differentiates between actions (*statements*) and computations (*expressions*).
- **Functions and Objects**: *Functions encapsulate logic; objects bundle data and logic*. Both are central to programming in Python.
- **Compound Expressions and Interpreters**: Demonstrates using complex expressions and the role of interpreters in evaluating code.

```
>>> from urllib.request import urlopen
>>> shakespeare = urlopen('https://www.composingprograms.com/shakespeare.txt')
>>> words = set(shakespeare.read().decode().split())
>>> {w for w in words if len(w) == 6 and w[::-1] in words}
{'diaper', 'drawer', 'redder', 'repaid', 'reward'}
```

### Errors

Debugging Principles:
- Test incrementally
- Isolate errors
- Check assumptions
- Consult others for help.