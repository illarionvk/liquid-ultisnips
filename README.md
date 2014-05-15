liquid-ultisnips
================

Liquid templating snippets for UltiSnips and vim

### hl

Jekyll-specific snippet for code blocks highlighting:

```django
{% highlight ruby %}
  Code example
{% endhightlight %}
```

Select code, press <kbd>tab</kbd>, enter `hl`, press <kbd>tab</kbd> again.

### inc 

Include tag as used in Shopify and Jekyll:

```django
{% include ${1} %}
```
