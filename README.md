# AIread

Got a long article that you don’t have the time to read? 😫 Or a complicated paper that you don’t understand? 📚

Introducing AIread! 🤖📖 AIread is a tool that allows readers to upload PDFs to summarize.

## How It Works 

AIread breaks the original content up into “chunks” and feeds them to OpenAI’s Text Completion model to summarize. In a split screen view, readers can enjoy the summaries while also referring to the original content on the other side. 📝📋

AIread is built using React and Vite. It interacts with a node + express backend and utilizes OpenAI language models in order to perform text summary / analysis. 🚀

It uses Firebase Storage to store uploaded PDFs and Cloud Firestore to store the extracted “chunks”, summaries, and user notes. The application also utilizes Firebase Authentication to handle account creation and maintenance. 

## Demo

Upload a PDF:

![ezgif-3-be7d3e9b1b](https://github.com/dartmouth-cs52-23s/project-airead/assets/20538238/9ae5a55f-38e6-46d3-b6cc-06bbb2f5082c)

**Generate summaries**, **chat with GPT**, and **add notes**, all in one platform!

![ezgif-2-110478e41b](https://github.com/dartmouth-cs52-23s/project-airead/assets/20538238/b48cd7b0-5bf8-4d4d-8511-e3c424fe83a3)


Please email jasonchen2023@gmail.com for code
