>[!Info]
Autor(es): {{authors}}
Publicación: {{date | format("YYYY")}}

>[!Abstract]

{{bibliography}}
# [Fuente]()
---
# .
{% for annotation in annotations %}{% if annotation.annotatedText %}
	{{annotation.annotatedText}}
{% endif %}{% endfor %}