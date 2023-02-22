<h2 align="center">EasyCode</h2>
<p align="center">GPT bot that understands your codebase</p>

### EasyCode helps you find relevant code, understand existing code, and write new code.

How is it different from other extensions? 

- Generations are **relevant to your codebase**.
- **Follow up questions**, feels just like chatGPT.
- **Free,** no browser session key or OpenAI key required.
- **Up to 5x faster** in generating responses.

### Code Suggestion

![Code Suggestion](https://github.com/chuangli94/easycode_assets/blob/96b4d55716b882e278403e4f9ac96b3a56f907b7/code_suggestion_annotated.jpg)

### Code Explanation

![Code Explanation](https://github.com/chuangli94/easycode_assets/blob/96b4d55716b882e278403e4f9ac96b3a56f907b7/code_explanation_annotated.jpg)

### Semantic Search

![Semantic Search](https://github.com/chuangli94/easycode_assets/blob/96b4d55716b882e278403e4f9ac96b3a56f907b7/semantic_search_annotated.jpg)

### General Search

![General Search](https://github.com/chuangli94/easycode_assets/blob/96b4d55716b882e278403e4f9ac96b3a56f907b7/general_search_annotated.jpg)

## How to use EasyCode

### **Understanding the Big Picture**

<img src="https://github.com/chuangli94/easycode_assets/blob/96b4d55716b882e278403e4f9ac96b3a56f907b7/main_panel.png" width="50%">

- **Ask Codebase →** For understanding how things work at a high level that are specific to your codebase. For example:
    - “What does this application do?”
    - “How does the user registration work?”
    
    Can also be used for finding relevant code:
    
    - “Where is user authentication handled?”
    
    And of course code generation:
    
    - “What are the changes needed to do <replace with a feature>?”
    - “How do I implement <replace with an idea>?”
- **Ask Internet →** Think of this as chatGPT in your IDE. Good for understanding concepts that are general, not related to your codebase. For example:
    - “How to sort an array in python?”
    - “How to handle exceptions in python?”

### **Understandings the specifics**

<img src="https://github.com/chuangli94/easycode_assets/blob/96b4d55716b882e278403e4f9ac96b3a56f907b7/context_menu.png" width="50%">

- **Ask EasyCode →** For open ended questions that are specific to the code you selected. Useful for questions that have a narrower scope.
- **Ask EasyCode: What does this do? →** Explains in detail what the code is doing. Useful for code that’s hard to read for various reasons (unfamiliar language, next level regex, yaml/config files, etc).
- **Ask EasyCode: Why is this here? →** Explains why a line/chunk of code is needed. This is a little unpredictable, it can be either very useful, or just re-iterate what the code does in a different way.
- **Ask EasyCode: How is this method used? →** Explains the usages of the method, ie how the method affects or is affected by other parts of codebase.
- **Ask EasyCode: How is this file used? →** Similar to “How is this method used”, but for a file or class.
- **Ask EasyCode: Write Code →** Get code suggestion that are specific to the code you selected. For example
    - “Modify a function so that it does ____”
    - “Write a test case that tests _____”
    - “Write documentation for this function”

**EasyCode: Index Codebase →** Allows for re-indexing of codebase, or indexing a different part of the codebase.

## Getting Started

1. **Index codebase** (optional) → Upon installation, you will see the option to “Index codebase”, this is an important step that helps AI provide answers that are **relevant** to your specific situation. This is required to use **Ask Codebase** features. ⚠️ **Make sure to index a folder that contains most of the logic.**
    
    ![Index](https://github.com/chuangli94/easycode_assets/blob/96b4d55716b882e278403e4f9ac96b3a56f907b7/index_codebase.gif)
    
2. **Ask Codebase** → ask a question that is related to your specific codebase, such as “How does this application work?
3. **Ask Internet** → ask a questions such as “how to send http request in react native?”

## FAQs

- What languages are supported?
    
    Typescript, Javascript, Python for now.
    
    Support for Java, C# coming soon.
    
- Is EasyCode free to use?
    
    EasyCode is free to use during alpha. We may introduce paid plans in the future, but there will also be a free version. 
    
- Do I have to index my code base?
    
    No. Indexing is required to use the “Ask Codebase” feature which provides answers relevant to your codebase. If you don’t want to index your codebase, you can still use all the other features. 
    
- What happens to my data?
    
    We never store your code. We use OpenAI to process the data. See OpenAI’s [Privacy Policy](https://openai.com/privacy/). 
    

## Contact

Please email **[paul@personabo.com](mailto:paul@personabo.com)** with your feedback & questions!

<div align="center">
  <br />
Made with ❤️ + ☕ from 🇨🇦
  <br />
 © 2023 Personabo Technologies Inc.
</div>
