{% extends "layout.html" %}

{% block body %}

<div class="col-md-10 col-md-offset-1">

{% filter markdown(extensions=['toc'], extension_configs= {'toc' : [('anchorlink', True)]}) %}

# CASES Partners

[TOC]

## Japanese American WWII CASE Module:
![Densho.org](http://densho.org/wp-content/uploads/2015/06/densho-logo.png)


## Mapping Inequality:
![University of Richmond](https://assets.richmond.edu/articles/images/features/large/scs/newsletter-osher/2014-01/ervine-feature.jpg =350x)
![Virginia Tech](https://bloximages.newyork1.vip.townnews.com/roanoke.com/content/tncms/assets/v3/editorial/1/4f/14f828d3-26e6-570b-985c-4827de48765d/5ca688b30faeb.image.png =350x)
![JHU](https://brand.jhu.edu/assets/uploads/sites/5/2016/01/university.logo_.small_.horizontal.white_.png =350x)

## Legacy of Slavery:
![Maryland State Archives](https://fromthepage.com/uploads/collection/picture/273/ftp_logo.JPG =350x)

# Other cases that have yet to be brought into Jupyter Notebooks:

## Global Journeys, Local Communities:

## White House Correspondents Association Pool Reports:
![UMD college of Journalism](http://merrill.umd.edu/wp-content/uploads/2015/06/Merrill-logo.jpg =350x)
![UMD Libraries](https://pbs.twimg.com/profile_images/517019440265695232/pQaby57P.jpeg =350x)
![WHCA](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/Seal_of_the_White_House_Communications_Agency.png/1200px-Seal_of_the_White_House_Communications_Agency.png =350x)


![Newseum Institute](http://www.newseum.org/wp-content/uploads/2017/07/Logo_NI_RGB.jpg.jpg =350x)

## Human Face of Big Data:
### Asheville Southside Community Association (Priscilla Robinson)

{% endfilter %}

</div>

{% endblock %}
