# Sirius group Opreation mannul for website with hugo template

## 1 You just need change the content folder

## 2 You can just copy the former one as a base folder and modify the content

## 3 After you finishing change the content,you can run hugo and hugo server to check the contents.

## 4 Run hugo and git push the root folder to github
## 5 Go to public folder to git push the webcode to github.

## insert filter in publication 
# {{% callout note %}}
# [Filtering](./publication/)
# {{% /callout %}}
if you meet this bugs: Error: from config: failed to resolve output format "headers" from site config
You can do 

`hugo mod clean` and then `hugo server`