# NinaProjekt

## Introdução
NinaProjekt tem como objetivo gerar descrições e imagens de animais híbridos (quimeras) utilizando tecnologias de IA.

## Tecnologias utilizadas:
1. ChatGPT - https://openai.com/blog/chatgpt/
2. WebUI para Stable Diffusion - https://github.com/AUTOMATIC1111/stable-diffusion-webui
3. Waifu Diffusion - https://huggingface.co/hakurei/waifu-diffusion

## Para que servem e como utilizar

### ChatGPT 
Usamos o ChatGPT para descrever as características do animal híbrido. Determinamos um modelo de _prompt_ padrão para as consultas e recebemos uma resposta também em um modelo padrão. O exemplo de entrada abaixo é para um animal híbrido entre uma girafa e uma cacatua:

```
create a description for an animal that is a fusion between a giraffe and a cockatoo containing: Scientific classification, general characteristics, behaviour and ecology
```

Caso você deseje testar a fusão entre outros animais, basta trocar as palavras "giraffe" e "cockatoo".

### WebUI para Stable Diffusion e Waifu Diffusion:
O WebUI funciona como uma interface gráfica para interagir com modelos de Stable Diffusion, através de palavras-chaves positivas e negativas para a geração de nossa imagem. Na interface também escolhemos qual modelo pré-treinado vai ser utilizado, bem como outros parâmetros (batch size, batch count, etc.).

O Waifu Diffusion é um modelo pré-treinado baseado no Stable Diffusion que teve um ajuste fino usando imagens de anime de alta resolução. Através desse modelo é possível produzir as imagens das quimeras com uma aparência cartunesca no estilo das animações japonesas. Exemplo de prompt:

#### Positive:
```
masterpiece, best quality, high quality, (bear), (bee), monster, combination, mix, someOtherKeyWordsGeneratedByChatGPT...
```

#### Negative:
```
bad_art_, lowres,{}[bad anatomy]{}, text, logo, cropped, worst quality, normal quality, extra face, nsfw, abstract, ()(jpeg artifact)(), ((extra thumb)), extra face, jpeg
```

![Snapshot](https://user-images.githubusercontent.com/51169281/215345674-05315654-966d-4756-8290-a2d120c4df4d.png)

## Entregas:
- [Apresentação](https://tome.app/chimera-project/nina-projekt-cldhfcj8a1pc27c41up832jhh)
- [Galeria](https://ninaprojekt.mystrikingly.com/)
- [Post-Mortem](https://docs.google.com/document/d/19dV3ti3k3NqiJGjNcJFTmlR_aoePRHdiOThrmTaRH-0/edit?usp=sharing)
