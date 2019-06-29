# aerial-cactus-identification

It's a [Kaggle](https://www.kaggle.com/c/aerial-cactus-identification/data) compittion to detect the cactus from aerial images 

## Getting Started
it's a classifier which classify images to have cactus and no cactus

## achievements

got a 99.5% valid accurcy and 0.018 valid loss with just 15 epochs 

100% of the public data classified well

### private data classification

4000 images with no labels classified well by 100% 



### use this code for testing 

Explain what these tests test and why

```
df.head()
df2=np.asarray(df)

testing=df2[20,:]

img_path = "/content/test/"+testing[0]
img = image.load_img(img_path, target_size=(32, 32))
#print(type(img))
plt.imshow(img)
print(testing[1])
```




## Authors

* **Sayed mohamed** - *Initial work* - [sayedmohamed](https://github.com/sayedmohamedscu)



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

