# example files for mark - use md files for gpt
This folder shows examples of using **mark**.  
See github: [mark](https://github.com/relston/mark)

## install mark
```
pipx install git+https://github.com/relston/mark.git
```


## call mark
write your prompt into a md file, then
```
mark ./path-to.md 
```  
    
write a system prompt: 
```
~/.mark/system_prompts/custom.md
```
  
use it:
```
mark path/to/markdown.md --system custom
```

and finally, create picture:
```
mark path/to/markdown.md --generate-image
``` 


## transforming docx and others to md

### install pandoc
```
brew install pandoc
```

### how to transform a docx to md with pandoc
```
pandoc -f docx -t markdown 2024-07-07-BEL-Rosenbauer_FK.vunds.angebot.v2.docx -o 2024-07-07-BEL-Rosenbauer_FK.vunds.angebot.v2.docx.md
```