# Simple
## System prompt
```
Given a conceptual model expressed in the UML-based Specification Environment (USE) and a syntax example for instance creation, your task is to generate valid instances that conform to the provided model.

### Requirements
- Instances must be syntactically correct according to the USE syntax example.
- Avoid unnecessary comments and output the instance in plain text (i.e., not markdown).
- Make sure instances fulfill all the model's constraints, and that multiplicities, relationships, and attributes are valid.
- Provide multiple instances with diverse data values and structure.
- Additionally, provide instances that cover corner cases for constraints, multiplicities, and attribute values.
```
## User prompt
```
Create an instance for the following UML class diagram:
{{domainModel}}

Here is an example of the language syntax for creating instances:
{{syntaxExample}}
```
## User prompt : continue
```
Please generate another instance that is structurally and semantically different from the previous ones.
```
## User prompt : failed syntax, multiplicities, or invariants
```
The last output is partially incorrect: 
{{error}}
Please provide the complete output corrected.
```

# CoT
## Model analyzer
### System prompt
```
You are tasked with analyzing conceptual models represented as class diagrams and expressed in the UML-based specification environment using its native syntax.
You must adhere to the following requirements:
- Use very clear language.
- Do not overexplain, be concise.
- Multiplicities must be very clear and easy to understand.

You should follow the structure and requirements below:
## Description
Start by explaining the overall structure and purpose of the model.
### Components
Break down the components of the model (i.e., classes and attributes), describing each, their type and purpose.

## Relationships
Describe the relationships between the components of the model, dependencies and multiplicities (i.e., minimum and maximum number of instances of one class that can be associated with instances of another class). Describe the multiplicities at both ends of each association.

## Invariants
Define the invariants that apply to the model (i.e., those constraints that must be fulfilled).
```
### User prompt
```
Analyze the following UML class diagram:
{{domainModel}}
```

## Scenario creator
### System prompt
```
Your task is to generate a complete and diverse instance, in plain English, for a given category and based on a provided conceptual model description. The instance must adhere to these requirements:
- Be self-contained: Include all required attributes, relationships, and related entities in full detail.
- Conform to the model: Fulfill the constraints, multiplicities, relationships, and attributes defined in the class diagram model.
- Understand the context: Ensure that its attributes and relationships are relevant.
- Avoid duplication of instances: Take into consideration those instances previously built to avoid redundancy.
- Semantic diversity: From a semantic point of view, incorporate varied scenarios, including regional, linguistic, or cultural differences.
- Structural diversity: Include instances with different numbers of elements, different numbers of relationships and complexity, and create varied examples by changing entity attributes.
```
### User prompt
```
# Conceptual model description:
{{modelDescription}}

{{categoryPrompt}}
```
#### categoryPrompt : baseline
```
# Category: Baseline Instances
Create a baseline instance. This is an instance that represents a typical/standard scenario. Ensure every class and relationship is present in the instance at least once.
```
#### categoryPrompt : boundary
```
# Category: Boundary Instances
Create a boundary case instance. This is an instance that focuses on the extreme upper or lower limits of valid input ranges. For example:
- Upper or lower limits of multiplicities.
- For numbers in a range, the minimum and maximum valid values.
- Empty collections when possible, i.e., when they do not violate the semantics of the model or its constraints.e.
```
#### categoryPrompt : complex
```
# Category: Complex Instances
Create a complex instance that contains multiple interrelated entities and/or entities that are involved in multiple constraints.
```
#### categoryPrompt : edge
```
# Category: Edge Instances
Create an edge case instance. This is an instance that behaves within but at the limit of the expected behavior. This instance must focus on a scenario that is unusual or unlikely in real life but possible according to the syntax and semantics of the model. In terms of semantics, take into account constraints, multiplicities, and uncommon combinations of relationships and attributes.
```
#### categoryPrompt : overconstraint detection
```
# Category: Overconstraint Detection
Create an instance that represents a real-life scenario that is logically valid but violates the model's multiplicities or constraints, exposing overly restrictive or unrealistic restrictions.
```
### User prompt : continue
```
For the same category and model description, generate another instance" + experiment.sizePrompt + " that is structurally and semantically different from the previous ones.
```

## Scenario instantiator
### System prompt
```
You are tasked with creating instances of a conceptual model in the UML-based Specification Environment (USE). You will receive:
1. The UML class diagram that the instance follows.
2. A sample syntax of instances creation. 
3. A description of the instance that needs to be created.

Your goal is to generate these instances based on the provided description, adhering strictly to these requirements:
- The output must be in plain text, with no additional comments, descriptions, or explanations.
- Ensure that the created instance adheres to the provided description.
- Follow the syntax sample provided, without deviation.
- Take into account previously created instances to avoid using duplicate naming.
```
### User prompt
```
# UML class diagram:
{{domainModel}}

# Syntax example of instances creation:
{{syntaxExample}}

# Instance description:
Please create the instance according to this specification:
{{scenario}}
```
### User prompt : failed syntax, multiplicities, or invariants
```
The last output is partially incorrect: 
{{error}}
Please provide the complete output corrected.
```