# AIread

Got a long article that you don’t have the time to read? 😫 Or a complicated paper that you don’t understand? 📚

Introducing AIread! 🤖📖 AIread is a tool that allows readers to upload PDFs to summarize.

## How It Works 

AIread breaks the original content up into “chunks” and feeds them to OpenAI’s Text Completion model to summarize. In a split screen view, readers can enjoy the summaries while also referring to the original content on the other side. 📝📋

AIread is built using React and Vite. It interacts with a node + express backend and utilizes OpenAI language models in order to perform text summary / analysis. 🚀

It uses Firebase Storage to store uploaded PDFs and Cloud Firestore to store the extracted “chunks”, summaries, and user notes. The application also utilizes Firebase Authentication to handle account creation and maintenance. 

## Demo

Upload a PDF:

![242737534-9ae5a55f-38e6-46d3-b6cc-06bbb2f5082c](https://github.com/jasonchen2023/AI-Read/assets/77142116/aa1145ba-e8a5-4107-bc14-7f8bfa0a901d)


**Generate summaries**, **chat with GPT**, and **add notes**, all in one platform!

![242736964-b48cd7b0-5bf8-4d4d-8511-e3c424fe83a3](https://github.com/jasonchen2023/AI-Read/assets/77142116/21216941-87ef-4139-b6d7-58758ee9403a)


If you're interested in seeing the code, please email jasonchen2023@gmail.com.
