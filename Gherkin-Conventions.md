The conventions of Gherkin for writing requirement details include:

1. **Feature:**
   ```
   Feature: [Title of the feature]
       [Description of the feature]
   ```

2. **Scenario:**
   ```
   Scenario: [Title of the scenario]
       [Description of the scenario]
   ```

3. **Given, When, Then:**
   - **Given:** Describes the initial context or setup for the scenario.
     ```
     Given [precondition]
     ```

   - **When:** Represents the action or event that triggers the scenario.
     ```
     When [action/event]
     ```

   - **Then:** Specifies the expected outcome or result of the scenario.
     ```
     Then [expected outcome]
     ```

4. **And, But:**
   - Allows for additional steps in the scenario.
     ```
     And [additional step]
     But [exceptional case]
     ```

5. **Background:**
   - Defines steps that are common to all scenarios within a feature.
     ```
     Background:
         Given [common precondition]
     ```

6. **Scenario Outline:**
   - Used for parameterization, allowing the same scenario to be executed with different inputs.
     ```
     Scenario Outline: [Title of the scenario outline]
         Given [precondition]
         When [action with <parameter>]
         Then [expected outcome with <parameter>]

     Examples:
         | parameter |
         | value1    |
         | value2    |
     ```

7. **Tags:**
   - Allows for categorization and filtering of scenarios.
     ```
     @tag1 @tag2
     Feature: [Title of the feature]
         [Description of the feature]

     @tag3
     Scenario: [Title of the scenario]
         [Description of the scenario]
     ```

8. **Comments:**
   - Lines starting with `#` are treated as comments.
     ```
     # This is a comment
     ```

These conventions help in creating structured and readable Gherkin scenarios, making it easier for both technical and non-technical stakeholders to understand and collaborate on the software requirements.