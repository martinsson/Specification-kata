# Specification-kata

One of the barriers to TDD is the difficulty to decompose a feature into tests. Starting with the tests require that we're able to formulate examples that illustrate the business rules. In fact a test is just one executable example of the specification. So a specification can be a list of tests. If we're *not* used to decompose a story into examples, aren't we condemned to do *test after* as opposed to TDD*?

The good news is that it is easy to learn, we usually just lack the habit and reflex to start with this.

To practice, take a feature description, decompose it into one or more business rules, then illustrate each business rule with a list of tests.

Typically this kata can be done with just about any subject, simple examples are the Leap Year kata, the FizzBuzz kata. They are short, but still contain several special cases.
You can find some examples in [subjects](https://github.com/martinsson/specification-kata/blob/main/subjects/)

I do **not** use a tool for this. A tool gives the impression that you need the tool to do it on a real project. That's a barrier to it's adoption and a distraction from the bulk of the value of this practice.

# Facilitation
The way I typically run this is to start by demonstrate how by leading one myself, this is the best way of explaining what is wanted. Then let the group do one on their own on another subject, typically simple and algorithmic. Following that, a UI feature can be an interesting option (login form, fill in an IBAN, ...). If you're doing this with a team the idea is to end with a real feature in your backlog. 

## Structure
To structure the activity I propose this template

### Feature name
Vague description of the feature. Done before the kata.

### Rules
Make the group explore and enumerate the business rules

1. ...
2. ...

### Examples
#### Rule 1 
1. example 1 for rule 1
2. example 2 for rule 1
3. ...



## Facilitation tips
If everything goes still, ask if there are any limit cases. If nothing happens, count silently to twenty (that'll feel very long), and if still nothing happens get things going with _What about ****_


## Credits
The first person to introduce me to this type of exercice (without tooling) was Gojko Adzic. He uses games like BlackJack and Poker. Those are good subjects as most of use think that we know the rules, only to discover that actually there are many variations, so it's a good idea to discuss it beforehand. 


## Notes
\* While I mention TDD I dont specifically target low level tests, in fact for almost every feature the list of examples will be translated into a mix of high and low level tests. Often this is called BDD (Behavior Driven Development) or specification by example. And it does not require any technology at all, 
a whiteboard or a text editor will suffice. 
And this is the activity that will be practised in this kata

