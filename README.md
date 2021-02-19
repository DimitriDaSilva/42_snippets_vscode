# 42_snippets_vscode

If you use VS Code at 42, this will probably interest you! :fire:<br>
I had a bit of fun creating custom snippets to improve my workflow at 42 :nerd_face: and wanted to share them with the 42 community! :hugs:<br>

## Setting up the snippets

You'll simply need to copy the snippet files in your computer. Yes, that's about it. :ok_hand:

Depending on your OS, your user snippets are located here:
- **Windows**: `%APPDATA%\Code\User\snippets`
- **Mac**: `$HOME/Library/Application Support/Code/User/snippets`
- **Linux**: `$HOME/.config/Code/User/snippets`

**WARNING :warning:**: if you already have custom snippets for .c files or for .h files, executing the commands below **will** overwrite them. So you'll have to copy them manually.

To quickly copy these sweet snippets, execute the upload command for your OS:
- **Mac**: `sh upload_mac.sh`
- **Linux**: `sh upload_linux.sh`

## Snippets for .c files
 
### 42_new_comment

**What it does:** creates a Norminette-approved boilerplate to comment a function. No more excuses not to comment your code :eyes:<br>
**Prefixes to use it:** `new_comment` or `nc`

![image](https://user-images.githubusercontent.com/66511903/105178528-08398300-5b20-11eb-82ec-6a8d78791aa7.png)
<br>

### main 

**What it does:** creates a boilerplate main to help you during your intense debugging section :bug:<br>
**Prefixes to use it:** `main` or `int main`

![image](https://user-images.githubusercontent.com/66511903/105178068-7762a780-5b1f-11eb-8cc3-4b2132845b6a.png)
<br>

### printf_w_var_name

**What it does:** creates a printf statement with the variable name you have on your clipboard. You just have to input its type and you are all set to find your bug :bug:<br>
**Prefixes to use it:** `printf_w_var_name`

![image](https://user-images.githubusercontent.com/66511903/108497635-acd7ed80-72a3-11eb-9ee3-cbb91a5e9918.png)
<br>

### printf_w_func_name

**What it does:** creates a printf statement with the name of your file (e.g. in ft_itoa.c see below)<br>
**Prefixes to use it:** `printf_w_func_name`

![image](https://user-images.githubusercontent.com/66511903/108498348-a72ed780-72a4-11eb-8b05-b4e8b49deed4.png)
<br>


### printf_wo_func_name

**What it does:** creates a simple boiler-plate printf statement<br>
**Prefixes to use it:** `printf_wo_func_name`
![image](https://user-images.githubusercontent.com/66511903/108498685-23c1b600-72a5-11eb-9ee2-c85c46704a07.png)
<br>

### includes_custom

**What it does:** adds an include with the same header file name as your current file (e.g. in ft_test.c: `#include "ft_test.h"`)<br>
**Prefixes to use it:** `include_custom` or `ic`

### includes_libft

**What it does:** simply adds `#include "libft.h`<br>
**Prefixes to use it:** `include_libft` or `il`

## Snippets for .h files
 
### 42_new_header_file

**What it does:** creates the boiler-plate `ifndef define endif` based on the name of your file<br>
**Prefixes to use it:** `new_header_file` or `nhf`

![image](https://user-images.githubusercontent.com/66511903/108499317-03dec200-72a6-11eb-9ddc-26e90b8592a4.png)
<br>

## Resources

If you want to tweak these snippets to your liking or even create brand new ones, here are ressources to help you! 

- VS Code's own documentation (https://code.visualstudio.com/docs/editor/userdefinedsnippets)
- A Snippet generator that works for VS Code, Sublime Text and Atom (https://snippet-generator.app/)

Have fun with it!
