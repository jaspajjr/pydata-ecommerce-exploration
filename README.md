# pydata-ecommerce-exploration

To get the dataset:

[Git clone explained](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone)

```
git clone git@github.com:jaspajjr/synthetic-ecommerce-dataset.git
```

Check parameters in src/config.json

```
docker build -t dataset-generation . docker run -it -v $(pwd):/output dataset-generation
```

That should give you a csv in your current file location.
