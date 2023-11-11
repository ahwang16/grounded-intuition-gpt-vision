![Grounded Intuition of GPT-Vision's Abilities with Scientific Images](grounded_intuition_github.png)

## Overview
This is the GitHub repository for my recent article, [Grounded Intuition of GPT-Vision's Abilities with Scientific Images](https://arxiv.org/abs/2311.02069).

**~Coming soon: Colab notebook for running GPT-Vision on the API.~ Now available!**

This paper contributes:

- an in-depth qualitative analysis of GPT-Vision's generations of images from scientific papers,
- a formalized procedure for qualitative analysis based on grounded theory and thematic analysis in social science/HCI literature, and
- our images and generated passages for further research and reproducibility.

We used two prompts to generate passages for each image:

- Write alt text to describe this \<type\>.
- Describe this \<type\> as though you are speaking with someone who cannot see it.

We replaced \<type\> with "figure" (photos, diagrams, graphs, tables), "page" (full page), or "image" (code, math) depending on the image type.

The images can be found in the `images` directory. Each file is named with the following convention:

```
<type>_<id>_<short-description>.png
```

with decimals in image IDs replaced by hyphens. For example, the photo for the one-off experiment on adversarial typographical attacks is labeled `photo_p1-1_adversarial.png`.

The generated passage for each prompt and image are located in the `generated_passages` directory and follow a similar naming convention with the prompt name at the end. The prompts for `photo_p1-1_adversarial.png` can be found in `photo_p1-1_adversarial_alt.png` and `photo_p1-1_adversarial_desc.png`.

## We're on the news!

- As OpenAI's Multimodal API Launches Broadly, Research Shows It's Still Flawed, [TechCrunch](https://techcrunch.com/2023/11/06/openai-gpt-4-with-vision-release-research-flaws/)
- ChatGPT-Maker OpenAI Hosts its First Big Tech Showcase as the AI Startup Faces Growing Competition, [Associated Press](https://apnews.com/article/chatgpt-openai-tech-showcase-da850be425aaa269e2915e9e0b1c726a)

## Suggested citation

If you would like to cite the paper or repository, you can use

```
@misc{hwang_grounded_2023,
      title={Grounded Intuition of GPT-Vision's Abilities with Scientific Images}, 
      author={Alyssa Hwang and Andrew Head and Chris Callison-Burch},
      year={2023},
      eprint={2311.02069},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
