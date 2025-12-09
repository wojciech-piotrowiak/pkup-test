# Mięsieczny raport prac

**Imię i nazwisko autora:** 
**Miesiąc raportu:** 

---

## Lista Pull Requestów

{% for pr in pull_requests %}
### {{ pr.title }}
**URL:** [{{ pr.url }}]({{ pr.url }})

**Opis po polsku:**  
{{ pr.summary_pl }}

**Description in English:**  
{{ pr.summary_en }}

---
{% endfor %}