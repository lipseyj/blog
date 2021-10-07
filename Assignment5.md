# Assignment 5 Tokenization
1. Format
2. Regular Expressions <br>
  a. [a-z][a-z0-9]* <br>
  b. [0-9]*\\\\.[0-9] <br>

3. Backus-Naur form <br>
  a. cat myfile && cat yourfile <br>
    conditional && pipeline <br>
    pipeline && pipeline <br>
    pipeline && command <br>
    command && command <br>
    command && word <br>
    command && redirection <br>
    command && command word <br>
    command && command redirection <br>
    command && command redirectionop filename <br>
    word && command redirectionop filename <br>
    redirection && command redirectionop filename <br>
    command word && command redirectionop filename <br>
    command redirection && command redirectionop filename <br>
    command redirectionop filename && command redirectionop filename <br>
  
  b. ls | grep something > somefile <br>
    pipeline | command redirection <br>
    pipeline | command redirectionop filename <br>
    pipeline | word redirection <br>
    pipeline | redirection redirection <br>
    pipeline | command word redirection <br>
    command | command word redirection <br>
    word | command word redirection <br>
    redirection | command word redirection <br>
    command word | command word redirection <br>
    command redirection | command word redirection <br>
    
  c. somecmd someparm || othercmd; gcc myfile > output <br>
    
    
  d. cmd1; cmd2 && cmd3; less output
    
