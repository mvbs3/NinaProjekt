# NinaProjekt
## introdução
NinaProjekt tem como objetivo gerar descrições e imagens de animais hibridos (quimeras) utilizando tecnologias de IA

## Tecnologias utilizadas:
1. ChatGPT - https://openai.com/blog/chatgpt/
2. WebUI para stable diffusion - https://github.com/AUTOMATIC1111/stable-diffusion-webui
3. Waifu diffusion - https://huggingface.co/hakurei/waifu-diffusion

## Para que servem e como utilizar
### ChatGPT 
O ChatGPT está servindo basicamente para criar as características do animal híbrido. Utilizamos uma entrada padrão para o chatGPT e recebemos uma resposta em um modelo padrão, o exemplo de entrada abaixo é para um animal híbrido entra uma girafa e uma cacatua, caso você deseje a fusão de outros animais basta trocar as palavras "giraffe" e "cockatoo" pelos animais desejados.
```
create a description for an animal that is a fusion between a giraffe and a cockatoo containing: Scientific classification, general characteristics, behaviour and ecology

```
### WebUI para stable diffusion e Waifu Diffusion:
O WebUI serve para ter um interface gráfica para interagir com modelos de stable diffsion. Colocando palavras chaves tanto positivas quanto negativas para a geração de nossa imagem. Também é possivel utilizar modelos pré-treinados nessa interface WebUI.
A Waifu difussion é um modelo pré-treinado que foi treinado utilizando imagens de anime de alta resolução. Utilizando esse modelo é possivel gerar as imagens das quimeras com uma aparencia cartunesca estilo animações japonesas. Exemplo de prompt:
#### Positive:
```
masterpiece, best quality, high quality, (bear), (bee), monster, combination, mix, someOtherKeyWordsGeneratedByChatGPT...
```
#### Negative:
```
bad_art_, lowres,{}[bad anatomy]{}, text, logo, cropped, worst quality, normal quality, extra face, nsfw, abstract, ()(jpeg artifact)(), ((extra thumb)), extra face, jpeg
```
![teste](https://user-images.githubusercontent.com/51169281/215345674-05315654-966d-4756-8290-a2d120c4df4d.png)
