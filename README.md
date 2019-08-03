# docs

all docs about apisix and project around OpenResty

## usage

this docs is based on [hugo](https://gohugo.io/), so first of all you should install it(you can run this cmd on MacOSX `brew install hugo`). you can find much more usage obout hugo at its [quick start](https://gohugo.io/getting-started/quick-start/)

here is some simple example:

```bash
# clone this doc project from github
git clone https://github.com/iresty/docs.git ~/code/iresty/doc.iresty.com

# go into the doc path
cd ~/code/iresty/doc.iresty.com/

# using the `new` cmd to create a new markdown
hugo new apisix/start.md

# running hogo server at localhost then you'll get a alive doc address like "http://localhost:1313/"
hugo server
```