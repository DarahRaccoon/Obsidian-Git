>[!Info]
Autor(es): {{authors}}
Publicación: {{date | format("YYYY")}}

>[!Abstract]

{{bibliography}}
# [Fuente]({{url}})
---
# .
{% for annotation in annotations %}{% if annotation.annotatedText %}
	{{annotation.annotatedText}}
{% endif %}{% endfor %}