---
Title: "{{title | escape}}"
Year: {{date | format("YYYY")}}
Authors: {{authors}}
Tags: {% if allTags %}{{allTags}}{% endif %}
---

# Cita Bibliográfica Formateada

{{bibliography}}
{% if abstractNote %}

# Resumen

{{abstractNote}}
{% endif %}


# Resaltados y notas
{% for annotation in annotations %}
{% if annotation.annotatedText %}

> {{annotation.annotatedText}}
> {% endif %}
> {% if annotation.comment %}
> {{annotation.comment}}
{% endif %}
{% endfor %}