# Grounded Intuition of GPT-Vision's Abilities with Scientific Images

This is the GitHub repository for my recent article, [Grounded Intuition of GPT-Vision's Abilities with Scientific Images](https://alyssahwang.com/assets/files/project_resources/Grounded_Intuition_GPT-Vision.pdf). The arXiv preprint is scheduled to go live at 8 PM EST on Sunday, November 5th, 2023.

This paper contributes:

- an in-depth qualitative analysis of GPT-Vision's generations of images from scientific papers, and
- a formalized procedure for qualitative analysis based on grounded theory and thematic analysis in social science/HCI literature,
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
