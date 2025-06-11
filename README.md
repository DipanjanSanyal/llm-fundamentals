# llm-fundamentals

## Pure Pytorch

GPT architecture by Karpathy explained in the following notebooks. In order to simplify, I have excluded some important but not so unique stuff like dropout, layernorm.

1. [Part1](./gpt-from-scratch-spelled-out-slower-part1.ipynb) includes the overall generative model set-up without using transformer, just keeping a placeholder for transformer.

2. [Part2](./gpt-from-scratch-spelled-out-slower-part2.ipynb) includes the details starting from self-attention finally wrapped into the generative model.

3. [GPT_Pretraining_Pytorch](./Simplified%20GPT%20Pretraining%20-%20Pure%20Pytorch.ipynb) notebook contains the training of the above explained model, but with the required dropout and layernorms and also using Pytorch's native attention class.

4. [GPT_Pretraining_Huggingface](./Simplified%20GPT%20Pretraining%20-%20Huggingface.ipynb) notebook shows how to do the similar exercise of pre-traning using Huggingface Transformer library.

## Credits

Part of this project is a simplification of [ng-video-lecture](https://github.com/karpathy/ng-video-lecture) by [Andrej Karpathy](https://github.com/karpathy). This version aims to provide a more accessible and streamlined interpretation of the original codebase for educational purposes.