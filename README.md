## Prompt Engineering

[Link](https://learn.deeplearning.ai/chatgpt-prompt-eng)

### Principles of Prompting

- **Principle 1 : Write clear and specific instructions**
  -  [summary](image.png)
    - Tactic 1 **Use Delimiters**
      - Use delimiters like backticks [example](https://prnt.sc/0FnWT_SdlQP0)
      - Using delimiters help in avoiding the prompt
        injection [example](https://prnt.sc/ZlBVvEJWbkMF)
      - other delimiters that can be used [image](https://prnt.sc/bvhV3NOW8bqt)
    - Tactic 2 **Ask for structured output**
        - You can ask model to give the response in a JSON FORMAT [example](https://prnt.sc/W5c4eDaF4pAV)
    - Tactic 3 **Conditional Satisfaction**
        - ask model to generate the steps by following the steps given in the prompt [example](https://prnt.sc/NBP0y9zDI-Yu)
        - if no stpes are there then model may return no stpes provided [example](https://prnt.sc/8lnQPelVKUOv)
    - Tactic 4 **Few shot prompting**
        - model can figure out the style of answer in the prompt and try to answer in same style [example](https://prnt.sc/Bo2tpbCvstr2)

- **Principle 2 : Give model time to think**
    - Tactic 1 **Specify the steps to complete a task**
        -  [example](https://prnt.sc/9953G34bVqSc)
        - [Prompt answer](https://prnt.sc/qZ0bV20zX9YV)
    - Tactic 2 **Instruct model to work out its own solution before rushing to a conclusion**
        - Difference in prompt makes the response different
            - [without asking for its own solution](https://prnt.sc/-ph1d7fW0yAd)
            - [asking the model to work out its solution and then make conclusion](https://prnt.sc/E5B1IHJjzvKs) 
            - [2nd image](https://prnt.sc/SgML2TXtSnwe)
            - [response](https://prnt.sc/deGYv3-ZUj4q)

- Model Limitations : - 

- **Hallusination** : - model makes statements that sound plausible but are not true
 - [example](https://prnt.sc/b82jMYYyyRTy)
 - **Reduce Hallusination** by asking the model to first find relevent information and then answer the question based on that relevent information

## Iterative Prompt development
- [example](https://prnt.sc/58gecEMghzHf)
  - try different versions of prompt [example](https://prnt.sc/9JYbOhX6nQV-)
  - give more clearer instrcutions to the model [example](https://prnt.sc/NPFUBL-ULXkX)
  - [example](https://prnt.sc/Kl4EBVrdChfD)
  - [example 1](https://prnt.sc/muYNOOv7Qrx_)

## Inferred prompting

- Infer the model to extract sentiments, mood, details from the prompt or reviews and so on
  - [example](https://prnt.sc/537Ni9IGdG7G)
  - [example](https://prnt.sc/rEIAlM3ygp5o)
  - [example](https://prnt.sc/RUAkLUIGiUTF)
  - [example](https://prnt.sc/DTQH6I_Cxc14)
  - [example](https://prnt.sc/fcUYW9APBnKq)
  - [example](https://prnt.sc/650xQFVFFM9t)
  - [story](https://prnt.sc/c5DuGvunZjZv) [prompt](https://prnt.sc/dZ9N992dAKOZ) [response](https://prnt.sc/c6OhQWwiZvSB) 
  - [example](https://prnt.sc/9Q0AbVH6_b-o)
  - 
