# Diochallenge

Challenge of AI Bootcamp, Dio + Microsoft

# Challenge 2, using Copilot to extract text from imagem

The main ideia of this project is to extract text from images, usind Microsoft AI solutions, once I don't have an enterprise subscription, I will not make use of OpenAi API's, then the solution I'm bring is to make use of Copilot on Windows, input manually the images and prompt, it's enough to   demonstrate the core idea.

I'm using the prompt to ask about the context of the images from billboards extracted from this website: [**Comunicadores**](https://comunicadores.info/exemplos-outdoors-criativos-outdoor/).

## Step by step to reproduce

- Go to the [**Comunicadores**](https://comunicadores.info/exemplos-outdoors-criativos-outdoor/), or other to downloand images, save it locally, in my case I saved on the folder asset/inputs;

- Open Windows Copilot or Copilot on Bing;

- Input on chat something like: "Given the image below, extract the text on it and try explain what message it transmit:" , attach the image;

- After the first image, you can attach the subsequent images and input: "Do the same to following image".

## Results

Although it simple we can see the power of the Copilot to achieve this result easily, not just extract the text as also the explain the idea and message beyond the ads.

An automation approach should be very welcome, and we have some options to make it:

- Develop a kind of app to consumes the OpenAi API's, create an interface to user load the image and then show the results;

- Make use of some Low-Code / No-Code service like [**Microsoft Power Apps**] (https://make.powerapps.com/);

On the folder assets/result I share a video demonstrating the result:

![Copilot Show:](assets/result/Demo.mp4)
<video src="assets/result/Demo.mp4" width="320" height="240" controls></video>