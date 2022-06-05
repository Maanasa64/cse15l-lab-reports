## LAB REPORT 5

I used `vimdiff my-markdown-parser/results.txt cse15lsp22-markdown-parser/results.txt'` on the results.txt file that we create after running a bash for-loop that exists 
in the `script.sh` file. Before this, I used the command `bash script.sh > results.txt` that saves the output of each result of the `.md` files to a separate file. After 
this, the `vimdiff` command helps us find the tests with different results. 

![Image](vimdiff.png)

In the above image, we can see that `test-files/194.md` has different outputs. The test can be found here[https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/194.md]
