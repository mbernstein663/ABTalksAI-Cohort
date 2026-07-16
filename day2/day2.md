# Day 2 Results + Lessons

## Prompt Engineering Research

Today I started by looking at a few of the resource links. They led me to a prompt engineering course that outlined a few broad ways to improve AI output, especially with agents or LangChain outputs:

**Zero-shot prompting**: Instructions for general inquiries, most agency is given to the LLM rather than drill-sergeanting into exact output.

**One-Shot prompting**: Instructions for specific AI outputs by providing an example of a strong response. Example:

```
Input:
Format: [Question] -> [Answer in 5 words]Example: What is the capital of France? -> Paris is the capital.
Now do this: What is the capital of Japan?
```

The Claude website also describes a useful tool called a "metaprompt" that takes a plain language task with simple variables and develops it into a complex, multishot LLM invocation for stronger outputs: https://platform.claude.com/cookbook/misc-metaprompt

## Prompt Engineering Results

Specifics and order certainly matter when it comes to prompt engineering- my first prompt generated an image while the regenerated prompt using the Chrome extension did not specifically ask for an image and the LLM just built a content template

What I did notice is that the regenerated prompt was just a more specific version of the original prompt. Rather than giving general instructions and explaining that it should be in sections, the revised prompt distinctly separates the prompt into three sections and explains the specifics for each one- including what the visuals should contain.

I learned that specifics and very intentional language will save you a lot of time and tokens. I also learned that naming the "what" and "where" are important.

## Outputs

Non-altered:

![alt text](<ChatGPT Image Jul 16, 2026, 04_01_05 PM.png>)

Altered:

![alt text](<ChatGPT Image Jul 16, 2026, 04_19_44 PM.png>)

We can visually see that the second "improved" image is more less content-heavy and includes solely what was asked for.

The first image is more detailed and gives the AI more creative freedom. It's not as pretty, but includes definitions and is more informative.

Ultimately, it seems like a "stronger" prompt does not just means more details. It requires being intentional about those details too + really understanding whether the specifics will add something to being with.
