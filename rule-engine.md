# Rule Engine
RULE = CONDITIONS + ACTION

CONDITIONS = `Predicate<T>`

ACTION = `Function<T,R>`

```mermaid
mindmap
  root((rule engine))
    Rule
      conditions + action
        conditions = n x condition = Predicate#60;T#62;
            object to be tested
            how to test the object
                syntax to compare one condition: <br/>e.g. object.getAge >= 18<br/> object field >= value
                syntax to compose multiple conditions: <br/>e.g. c1 && c2
        action = Function#60;T,R#62;
    
```

## Reference
- [Lightweight External Business Rules](https://www.infoq.com/articles/java-external-rules-engine/)
- [JSON query and transformation language](https://jsonata.org/)
- [Introduction to the Evrete Rule Engine](https://www.baeldung.com/java-evrete-rule-engine)
- [JSR 94: JavaTM Rule Engine API](https://jcp.org/en/jsr/detail?id=94)
