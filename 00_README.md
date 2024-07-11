# mark
This folder shows examples of using **mark**.  
See github: [mark](https://github.com/relston/mark)

## call mark
1. write your prompt into a md file
2. call mark ./path-to.md

## install mark
```
pipx install git+https://github.com/relston/mark.git
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