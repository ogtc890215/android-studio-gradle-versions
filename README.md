Check newest release library available version:
```
gradle checkDeps:dependencyUpdates
```
Check the latest available version of a specific library:
```
gradle checkDeps:dependencyUpdates -Pspec=<keys-of-deps>
```
Multi-part of libraries use ',' as seperator

Check the unstable versions, such as 'alpha' or 'beta':
```
gradle checkDeps:dependencyUpdates -Pdev
```
