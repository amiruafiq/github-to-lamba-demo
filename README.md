# github-to-lamba-demo

1) Create Function (at AWS site)
    - give name function
    - runtime (python/node.js)
    
2) Create repo in Github (github-to-lamba-demo)
3) Clone repo from github via terminal
```
git clone https://github.com/amiruafiq/github-to-lamba-demo
```
4) Open VS Code in folder
```
/Users/amirulafiq/TestFunctionLambda/github-to-lamba-demo
```
5) Create all related file 
> lambda_function.py. [source code]([https://pages.github.com/](https://github.com/felixyu9/github-to-lambda-demo/blob/main/lambda_function.py))
> requirements.txt [source code]([https://github.com/felixyu9/github-to-lambda-demo/blob/main/requirements.txt])
> iam-policy.json -to be put in AWS [source code] ([https://github.com/felixyu9/github-to-lambda-demo/blob/main/iam-policy.json])


6) From VS Code - push to github
```
git add .
git commit -am 'added demo lamba code'
git push origin main
```


