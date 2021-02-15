# Frequently Asked Questions

## Frequently Asked Questions

## wordcount is not installed

Sometimes a runtime error will be reported with the wordcount keyword, just run the following command

```bash
npm i --save hexo-wordcount
```

## Code highlighting issues

The theme has built-in code highlighting and it is automatically turned on. To avoid conflicts, please disable highlight in the \`\`site profile

```yaml
highlight:
  enable: false
```

## Home page overview

When Hexo is writing \(_**many blogs do this**_\), you need to add **`<! --more-->`** then the section before that marker becomes the overview of the article and is displayed on the front page

The _Hexo is a new section in **`<! --more-->`** needs to have a paragraph_ 

! 

