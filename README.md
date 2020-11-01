# Gitipedia

This project is a reflexion in progress around using git or some derived version control system to store wiki content. A little more specifically, it is targeted to be used for online encyclopedia like Wikipedia.

## Why ?
Wikipedia is a wonderful project and a wonderful man-made treasure. It is, however, a centralized project, held by one foundation which depends on fundings to survive and to run it. It's existence could be threatened anytime if one of its major support was deciding to stop supporting it.

It is then essential to find a way to make this project more safe and ensure it's content is more decentralized and organized without central point. Of course, the question of hosting the content and running a website is important, but the main value of the encyclopedia is it's content.

The first goal of this project is about storing and sharing the content. Hosting, rendering, editing are not primary goals as they can be added around the content.

In the IT industry, GIT is a widespread, well-known tool that is decentralized, and that enables worldwide collaboration. So the reflexion here is to see if GIT could be used as a backend tool for Wikis like Wikipedia.

## How ?
Wiki pages are simply text files, which are kept with their history and list of contributors. Git makes this perfectly and also enables collaboration over the boundaries of one silo website as Wikipedia is as of today. 

There is already quite a couple of Wiki relying on Git : https://paulhammant.com/2017/09/23/wikis-that-use-source-control-for-their-backing-store/

### Pros
 - Decentralized
 - Version control
 - Well known
 - Can be forked, copied, modified, and changes can be spread through pull requests
 - Other projects could join the movement and Wikipedia could be enriched in many new ways

### Cons
 - A wiki is not just files
 - History can be rewritten
 - Many non-official copies may exist and could dilute the value of the main project

## Git or not ?
Git is a good basis, but we have to think of all advantages and consequences. The principles are good, but the solution is maybe something similar, but more specialized. Therefore a new tool could be made from scratch, starting from zero like described in : https://wyag.thb.lt/
