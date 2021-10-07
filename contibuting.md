# How to contribute?

Follow these guidelines to make your and the repositoriy maintainer's work simpler.

## Found a bug?

- **Ensure that the bug has not been reported already**. Before creating a new issue, search for it in [project issues](https://github.com/GDSC-AUM/OpenOcto-AI-ML/issues).

- If you're are unable to find any open issues for the problem, follow one of the steps mentioned below:

### Contributing to the documentation?

- Make sure you read and understand the [Contributing Guidelines](CONTRIBUTING.md) thoroughly, [open a new issue](https://github.com/GDSC-AUM/OpenOcto-AI-ML/issues/new), make changes to the `DOC.md` file of the related category and finally create a pull request. It would be put under review and accepted if appropriate.

- To add any new program to the document, use the syntax given below:

    ```markdown
    ## Program name

    - [Source code](./file_name.ipynb)

    - A short description of the program. [[<Reference Source Name>](link to the reference webpage)]
    ```

- Check [here](https://raw.githubusercontent.com/GDSC-AUM/OpenOcto-AI-ML) to see an example.

### A New Program?

- Want to add something new 😎? Great! [Open a new issue](https://github.com/GDSC-AUM/OpenOcto-AI-ML/issues/new), include a **clear title and description**.

- Add some **test cases** showing what the program does.

- If an appropriate directory for your program doesn't exist, add them to the `others` folder.

- Please name you files with lowercase letters and word seperated by underscores (**snake case**)

    ```cpp
    SieveOfEratosthenes.cpp ❌
    ```

    ```cpp
    sieve_of_eratosthenes.cpp ✅
    ```

- Update the appropriate `DOC.md` file to include the new program to the list (use the template provided above to do so).

### Bug Fixes?

- Found and fixed a bug 🐜? [Open a new issue](https://github.com/GDSC-AUM/OpenOcto-AI-ML/issues/new), include a **clear title and description**.

- Make sure to include a **test case** where the program does not show expected behaviour. (Try to include input, expected output and actual output. An explaination of the bug fix would be appreciated).

### Improving an existing program?

- [Open a new issue](https://github.com/GDSC-AUM/OpenOcto-AI-ML/issues/new), include a **clear title and description**.

- Description should show what was improved (sometimes even changing badly named variables can be considered as an improvement) 👍.


#### 🎊🎉That's all, happy contributing and thank you again!🎉🎊
