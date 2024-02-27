# Feature: [Title of the feature]
Description of the feature

## Scenario: [Title of the scenario]
Description of the scenario

### Given [precondition]
### When [action/event]
### Then [expected outcome]

### And [additional step]
### But [exceptional case]

## Background:
Given [common precondition]

## Scenario Outline: [Title of the scenario outline]
Given [precondition]
When [action with <parameter>]
Then [expected outcome with <parameter>]

Examples:
| parameter |
|-----------|
| value1    |
| value2    |

## Tags:
@tag1 @tag2 @tag3

# Comments:
Lines starting with # are treated as comments.
# This is a comment
