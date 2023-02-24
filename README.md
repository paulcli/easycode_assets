<h2 align="center"><img src="https://github.com/chuangli94/easycode_assets/blob/main/easycode_blue_letter.png?raw=true" height="64"><br>EasyCode, backed by<br>
<img src="https://logos-download.com/wp-content/uploads/2016/11/Y_Combinator_logo_text_wordmark.png" width="15%"></h2>
<p align="center">Experience benefits of ChatGPT Pro in your IDE</p>

- **100% Free,** no session key or OpenAI key required.
- **Up to 5x faster** in generating responses.
- Generations are **relevant to your codebase**.
- **Follow up questions**, feels just like ChatGPT.
- **Security**, data not stored, or used for training.

### ChatGPT + ability to answer questions specific to your project.
<img src="https://github.com/chuangli94/easycode_assets/blob/main/demo_final.gif?raw=true" width="100%">

### Code Suggestion

![Code Suggestion](https://github.com/chuangli94/easycode_assets/blob/main/code_suggestion_annotated.jpg?raw=true)

### Code Explanation

![Code Explanation](https://github.com/chuangli94/easycode_assets/blob/main/code_explanation_annotated.jpg?raw=true)

### Semantic Search

![Semantic Search](https://github.com/chuangli94/easycode_assets/blob/main/semantic_search_annotated.jpg?raw=true)

### General Search

![General Search](https://github.com/chuangli94/easycode_assets/blob/main/general_search_annotated.jpg?raw=true)

## Getting Started

1. **`Index codebase`** (optional) → Upon installation, you will see the option to “Index codebase”, this is an important step that helps AI provide answers that are **relevant** to your specific situation. This is required to use **`Ask Codebase`** feature. ⚠️ **Make sure to index a folder that contains most of the logic.**
    
    ![Index](https://github.com/chuangli94/easycode_assets/blob/main/index_codebase.gif?raw=true)
    
2. **`Ask Codebase`** → ask a question that is related to your specific codebase, such as “How does this application work?"
3. **`Ask Internet`** → ask a questions such as “how to send http request in react native?”

## How to use EasyCode

### **Understanding the Big Picture**

<img src="https://github.com/chuangli94/easycode_assets/blob/main/main_panel.png?raw=true" width="50%">

- **`Ask Codebase` →** For understanding how things work at a high level that are specific to your codebase. For example:
    - “What does this application do?”
    - “How does the user registration work?”
    
    Can also be used for finding relevant code:
    
    - “Where is user authentication handled?”
    
    And of course code generation:
    
    - “What are the changes needed to do (insert feature) ?”
    - “How do I implement (inser idea)?”
- **`Ask Internet` →** Think of this as chatGPT in your IDE. Good for understanding concepts that are general, not related to your codebase. For example:
    - “How to sort an array in python?”
    - “How to handle exceptions in python?”

### **Understandings the Specifics**

<img src="https://github.com/chuangli94/easycode_assets/blob/main/context_menu.png?raw=true" width="50%">

- **`Ask EasyCode` →** For open ended questions that are specific to the code you selected. Useful for questions that have a narrower scope.
    
- **`Ask EasyCode: What does this do?` →** Explains in detail what the code is doing. Useful for code that’s hard to read for various reasons (unfamiliar language, next level regex, yaml/config files, etc).
    
- **`Ask EasyCode: Why is this here?` →** Explains why a line/chunk of code is needed. This is a little unpredictable, it can be either very useful, or just re-iterate what the code does in a different way.

- **`Ask EasyCode: How is this method used?` →** Explains the usages of the method, ie how the method affects or is affected by other parts of codebase.

- **`Ask EasyCode: How is this file used?` →** Similar to “How is this method used”, but for a file or class.

- **`Ask EasyCode: Write Code` →** Get code suggestion that are specific to the code you selected. For example
    - “Modify a function so that it does ____”
    - “Write a test case that tests _____”
    - “Write documentation for this function”

**`EasyCode: Index Codebase` →** Allows for re-indexing of codebase, or indexing a different part of the codebase.

## FAQs

- What languages are supported?
    
    `Ask Internet` and the Context Menu features work for most common languages. 
    
    `Ask Codebase` works for Typescript, Javascript, Python, Java, C# for now. Support for more coming soon. 
    * VS Code Language Exension pack needs to be installed for [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) and [Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack). 
    
- Is EasyCode free to use?
    
    EasyCode is free to use during alpha. We may introduce paid plans in the future, but there will also be a free version. 
    
- Do I have to index my code base?
    
    No. Indexing is required to use the **`Ask Codebase`** feature which provides answers relevant to your codebase. If you don’t want to index your codebase, you can still use all the other features. 
    
- What happens to my data?
    
    We never store your code. We use OpenAI to process the data. Your data is **not being used** for training other AI models. See OpenAI’s [Privacy Policy](https://openai.com/privacy/). 
    

## Contact

Please email **[paul@personabo.com](mailto:paul@personabo.com)** with your feedback & questions!

<div align="center">
  <br />
Made with ❤️ + ☕ from 🇨🇦
  <br />
 © 2023 Personabo Technologies Inc.
</div>
