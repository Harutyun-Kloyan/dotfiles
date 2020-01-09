1. Install vim-plug plugin manager:

   `curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`
2. Install llvm/clang for the cpp code completion:

   `brew install llvm`
3. Install python-language-server for python completion:

   `pip3 install python-language-server`
   
4. Make sure you have node and npm for javascript typescript completion:

   ```
   brew install node
   npm install -g ts-node
   npm install -g typescript
   ```
4. Install MacVim it has a gui:

   `brew install macvim`
5. Launch gvim and execute:

   `:PlugInstall`
