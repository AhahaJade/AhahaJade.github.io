---
title: Photos of the Year 2023!
date: '2023-12-18'
summary: Easily blog from Jupyter notebooks!
private: true
---
{{ partial "image-gallery" (dict "context" . "gallery_dir" "album") }}

```python
from IPython.core.display import Image
Image('https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png')
```
* ![Image 1](http://example.com/image1.jpg)
* [![Image 2](http://example.com/image2.jpg)](http://example.com/image2_full.jpg)
* ![](http://example.com/image3.jpg)
    
![png](output_1_0.png)
    

```python
print("Welcome to Academic!")
```

    Welcome to Academic!

## Organize your notebooks

Place the notebooks that you would like to publish in a `notebooks` folder at the root of your website.

## Import the notebooks into your site

```bash
pipx install academic
academic import 'notebooks/**.ipynb' content/post/ --verbose
```

The notebooks will be published to the folder you specify above. In this case, they will be published to your `content/post/` folder.
