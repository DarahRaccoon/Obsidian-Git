>[!Info]
Autor(es): {{authors}}
Publicación: {{date | format("YYYY")}}

>[!Abstract]
>{{abstract}}

{{bibliography}}
# [Fuente]({{url}})
---
# .
{% for annotation in annotations %}{% if annotation.annotatedText %}
	{{annotation.annotatedText}}
{% endif %}{% endfor %}