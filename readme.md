# Valiant

**Vali**dation, eleg**ant**ly.


new validator, add rules, use on any data, multiple times.

decorate existing instance

validate - check/throw/inspect option


```php



```

assumptions:

- to be reusable, the validators are created in factories, that is, passing data to the constructor is a/ not practical b/ not reusable, since the validator is bound to the data.
- binding to data is not practical for "validata - fail - recover - validate again" workflow

