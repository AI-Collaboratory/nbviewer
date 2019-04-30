{% extends "layout.html" %}

{% block body %}

<div class="col-md-10 col-md-offset-1">

{% filter markdown(extensions=['toc'], extension_configs= {'toc' : [('anchorlink', True)]}) %}

# Contribute a CASE Module

**The CASES team has worked to publish modules on the website. We would love for the public to contribute in any way possible to enhance the content on this website so students can learn.**

[TOC]

![Diagram showing steps for contributing]({{ static_url("img/contribute.png") }} "Steps for Contributing a CASE Module")

## How to Contribute

Here are a few guidelines for contributing to our website:

1. You will need to have a github account. If you do not own a github account, you can register [here](http://github.com).
1. Upon creation of your GitHub account, please fill out our CASES contributors form.
1. Keep in mind that you will need to review and accept our CASES Terms & Agreements (TBD).

Upon receiving your notebook submission, we will work with you to include the content you've contributed.


## List of Existing CASE FILES
1. [Legacy of Slavery](http://cases.umd.edu/github/cases-umd/Legacy-of-Slavery/blob/master/index.ipynb)
1. [Japanese American History](http://cases.umd.edu/github/cases-umd/Japanese-American-WWII/blob/master/index.ipynb)
1. [Baltimore Redlining](http://cases.umd.edu/github/cases-umd/Baltimore-Redlining-1/blob/master/notebook/index.ipynb)

## Frequently Asked Questions

Q: Do you have to be affiliated with University of Maryland to contribute to the website?
A: No. Cases welcomes everyone from different institutions

Q: Is there a limit to how many contributions one person can make?
A: There is no limit to how much someone can contribute. However, a form will need to be filled out for each contribution. A successful contribution doesn’t guarantee automatic approval next time.

Q: Are there any costs associated with making contributions?
A: It is free to make contributions to our website. CASES uses a GitHub repository.

Q: What programming language are the case files coded in?
A: Cases files are formatted in Jupyter notebooks using python language.

Q: For code contributions, are Github pull request used?
A: Yes. To contribute python code for a case file, Github pull request are used. Please see the Pull Request Checklist before sending off a pull request

Please refer to our Cases Community forum, where registered users can participate in discussions, post questions and view contact information for all other inquiries.

{% endfilter %}

</div>

{% endblock %}
