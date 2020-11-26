# homepage_generator

### requirements
- hugo==0.78.2 (with extended version)


### locally run
```
hugo  server --bind "0.0.0.0" -p port
```

### generate static website and deploy
```
hugo
cd public
git add *
git commit -m "xxxx"
git push origin master
```
