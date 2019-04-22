{% extends "layout.html" %}

{% block body %}

<div class="col-md-10 col-md-offset-1">

{% filter markdown(extensions=['toc'], extension_configs= {'toc' : [('anchorlink', True)]}) %}

# Contribute a CASE Module

[TOC]

![Diagram showing steps for contributing]({{ static_url("img/contribute.png") }} "Steps for Contributing a CASE Module")

{% endfilter %}

</div>

{% endblock %}
