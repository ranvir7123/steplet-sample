# steplet-sample

A tiny Python module and its tests, used to try Steplet end to end: a signed `.steplet` file asks an AI agent to run these tests inside Steplet's sealed Linux, and Steplet's report shows the real exit code.

Nothing to install. Run the tests with:

```
python3 -m unittest discover -s tests -t .
```
