# Pandoc Document Converter

This repository outlines briefly how to utilize the Pandoc universal document converter command-line tool. The pandoc release version 3.2 for MacOS obtained from the official releases list on [jgm/pandoc](pandoc-3.2-x86_64-macOS.pkg) was utilized.

# Utilization

* After installing pandoc check if the installation was completed successfully by executing the following command:
    ```
        pandoc --version
    ```
* To convert between various document formats execute the following command, pandoc will automatically detect the types based on the document extensions.
    ```
        pandoc test.tex -s -o test.docx
        pandoc test.tex -s -o test.md
        pandoc test.md -s -o test_duplicate.tex
    ```
    The above are some example commands to convert between document types. For a complete set of pandoc commands visit the [Pandoc Website](https://www.pandoc.org/getting-started.html).
