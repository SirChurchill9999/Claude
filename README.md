## Example
<!-- start:code block -->
```
Human: I have two pet cats. One of them is missing a leg. The other one has a normal number of legs for a cat to have. In total, how many legs do my cats have?

Assistant: Can I think step-by-step?

Yes, please do. When you reply, put your step-by-step thoughts in <thinking></thinking> XML tags. This is a space for you to write down relevant content and will not be shown to the user. Once you are done writing down your step-by-step thoughts, put your answer to the user inside <answer></answer> XML tags.

Do you understand the instructions?
```
<!-- end:code block -->

## Example
<!-- start:code block -->
Please follow these steps:

1. Write three topic sentences arguing for {{STATEMENT}}.
2. Write three topic sentences arguing against {{STATEMENT}}.
3. Write an essay by expanding each topic sentence from Steps 1 and 2, and adding a conclusion to synthesize the arguments. Please enclose the essay in &lt;essay&gt;&lt;/essay&gt; XML tags.

Do you understand the instructions?
<!-- end:code block -->

## Example
```
Please follow these steps:
1. Write three topic sentences arguing for {{STATEMENT}}.
2. Write three topic sentences arguing against {{STATEMENT}}.
3. Write an essay by expanding each topic sentence from Steps 1 and 2, and adding a conclusion to synthesize the arguments. Please enclose the essay in <essay></essay> XML tags.

Do you understand the instructions?
```