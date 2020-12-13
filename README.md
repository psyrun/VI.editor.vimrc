# Vi Editor

* The soul editor of shell VI, this script will change the look of vi development env.
     
* If you dont have one, execute the following shell query to install vim.
        
        sudo apt-get install vim

* Create a new file 

        
        $ vi ~\.vimrc


* Add the following code in file
       

        syntax on
        colorscheme pablo
        :set number
        :set tabstop=8
        :set expandtab
        :set shiftwidth=4
        :set autoindent
        :set smartindent
        :set cindent

* Save the file.
