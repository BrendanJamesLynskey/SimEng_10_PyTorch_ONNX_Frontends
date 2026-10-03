# Simulation Engineering Toolkit 10 — From PyTorch and ONNX to an Accelerator Model

A working front end for an accelerator simulator: real model configurations (Llama-3-8B and -70B, Mistral, Qwen, GPT-2) traced without weights on the meta device and under fake tensors, torch.export, a torch.compile backend and an ONNX graph walk, all four agreeing exactly on the arithmetic, checked against closed forms and PyTorch's FLOP counter, costed on a roofline, with operator coverage counted three ways.

Topics: Meta device, Fake tensors, torch.export, torch.compile, ONNX, Operator coverage.

**Live site:** https://brendanjameslynskey.github.io/SimEng_10_PyTorch_ONNX_Frontends/

Part of the [Simulation Engineering Toolkit series](https://github.com/BrendanJamesLynskey/SimEng_Hub_Toolkit). Companion code: [Torch_Sim_Frontend](https://github.com/BrendanJamesLynskey/Torch_Sim_Frontend), [Disaggregated_Inference_Sim](https://github.com/BrendanJamesLynskey/Disaggregated_Inference_Sim). Interview questions: [Interview_AI_Accelerator_Architecture](https://github.com/BrendanJamesLynskey/Interview_AI_Accelerator_Architecture), [Interview_Machine_Learning](https://github.com/BrendanJamesLynskey/Interview_Machine_Learning). Every concept used here is explained, with links, in the [series glossary](https://brendanjameslynskey.github.io/SimEng_Hub_Toolkit/#glossary).

Slides and text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
