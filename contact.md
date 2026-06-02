---

layout: page

title: "Contact"

---


**{{ site.title }}**  
Leibniz University Hannover  
Institute of Machine Design and Tribology (IMKT)

## Email
{% for mail in site.contact.emails %}
- {{ mail }}
{% endfor %}

## Website
- [LinkedIn]({{ site.contact.website }})

## GitHub
- [{{ site.github_username }}](https://github.com/{{ site.github_username }})




