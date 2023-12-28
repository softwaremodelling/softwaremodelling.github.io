Data based exclusive OR Gateway helps us to decide the flow of sequence based on a data condition.

A conditional expression is evaluated. Based on the value of the expression, the outgoing flow is determined. 

Exclusive OR gateways are used while both splitting sequence as well as Merging sequence. 
![image](https://github.com/softwaremodelling/softwaremodelling.github.io/assets/14120650/f001774a-547f-442c-a83f-0e27be0e0014)


Among the multiple outgoing sequence flows, one can be designated as Default flow, whch requires no conditional expression. All other outgoing flows requires a conditional expression.

![image](https://github.com/softwaremodelling/softwaremodelling.github.io/assets/14120650/fbaaaf12-b331-4f11-9251-da8bb0b0827e)


Annotations can be added to each of the outgoing flows to describe additional details about the flow. 
![image](https://github.com/softwaremodelling/softwaremodelling.github.io/assets/14120650/1e383c5c-4503-480b-9ceb-8cb26f6cf2d7)


Exclusive gateways can also be used to introduce loops
![image](https://github.com/softwaremodelling/softwaremodelling.github.io/assets/14120650/0526bd96-169a-4c22-b331-7537e83f542e)


Reference

https://docs.camunda.io/docs/components/modeler/bpmn/exclusive-gateways/
