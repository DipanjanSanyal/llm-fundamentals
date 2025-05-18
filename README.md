# llm-fundamentals

## Introduction

Amazed by GPT explanation by Andrej Karpathy, I decided to understand it deeply.

As I try to implement it practically, I faced several questions, after a lot of search, the answers are found in the code itself 😊 Once again, I am amazed.

I try to explain the GPT architecture explained by Karpathy in his video lecture. In order to simplify, I have excluded some important but not so unique stuff like dropout, layernorm.

[Part1](./gpt-from-scratch-spelled-out-slower-part1.ipynb) includes the overall generative model set-up without using transformer, just keeping a placeholder for transformer.

[Part2](./gpt-from-scratch-spelled-out-slower-part2.ipynb) includes the details starting from self-attention finally wrapped into the generative model.

Training is not included yet. Training is straightforward and hence will be shown in a more compact code.

## Credits

This project is a simplification of [ng-video-lecture](https://github.com/karpathy/ng-video-lecture) by [Andrej Karpathy](https://github.com/karpathy).

This version aims to provide a more accessible and streamlined interpretation of the original codebase for educational purposes.