# sed3fit_read
A package mutuated from the magphys_read_output repository, to read outputs from sed3fit (available here http://steatreb.altervista.org/alterpages/sed3fit.html).

Usage:

```python
import sed3fit_read
results = sed3fit_read.Sed3FitOutput(path_to_fit, path_to_sed)        
```

Then all the sed3fit outputs will be stored in the results object.
