---

layout: page
special_page: true
no_index_link: true
title: The Hitchhiker's Guide to a PhD

---

<section class="advice-listings">

    This is a colleciton of observations and pieces of advice around doing a PhD, written by current CS PhD students at Glasgow university and curated via a [Github repo](https://github.com/Unofficial-Glasgow-PhD/unofficial-advice). Thanks for visiting! We hope there's something useful for you here.

    <p>Here's some pages on this project itself:</p>

    <div class="special pages">
        <ul>
            {% for page in site.pages %}
            {% if page.title and page.special_page %} {% unless page.no_index_link %}
            <li>
                <a href="{{ site.baseurl }}{{ page.url }}">
                    {{ page.title }}
                </a>
            </li>
            {% endunless %}{% endif %}
            {% endfor %}
        </ul>
    </div>

    Here's a list of the different pages of advice we've curated so far:

    <div class="page-listing">
        <ul>
            {% for page in site.pages %}
            {% if page.title %} {% unless page.special_page %}
            <li>
                <a href="{{ site.baseurl }}{{ page.url }}">
                    {{ page.title }}
                </a>
            </li>
            {% endunless %}{% endif %}
            {% endfor %}
        </ul>
    </div>

    Thanks for stopping by!

    If you've learned anything already or been given advice by people you've met which you haven't seen reflected on this page, let us know! You can learn how to add to the collective pool of advice at our [contributing page](https://unofficial-glasgow-phd.github.io/unofficial-advice/contributing.html).

</section>
