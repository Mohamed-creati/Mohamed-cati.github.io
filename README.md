# Mohamed-creati.github.io
A website for great minds to coalesce over politics, advancements and achievements
<h1>Hello!</h1>
<p>My name is Mark</p>
<p>I like <b>boxing</b> and <i>fishing</i>
- title: General Information
  type: map
  contents:
    - name: Full Name
      value: Albert Einstein
    - name: Date of Birth
      value: 14th March 1879
    - name: Languages
      value: English, German

- title: Education
  type: time_table
  contents:
    - title: PhD
      institution: University of Zurich, Zurich, Switzerland
      year: 1905
      description:
        - Description 1.
        - Description 2.
        - title: Description 3.
          contents:
            - Sub-description 1.
            - Sub-description 2.
    - title: Federal teaching diploma
      institution: Eidgenössische Technische Hochschule, Zurich, Switzerland
      year: 1900
      description:
        - Description 1.
        - Description 2.

- title: Experience
  type: time_table
  contents:
    - title: Professor of Theoretical Physics
      institution: Institute for Advanced Study, Princeton University
      year: 1933 - 1955
      description:
        - Description 1.
        - Description 2.
        - title: Description 3.
          contents:
            - Sub-description 1.
            - Sub-description 2.
    - title: Visiting Professor
      institution: California Institute of Technology, Pasadena, California, US
      year: 1933
      description:
        - Description 1.
        - Description 2.

    - title: Director
      institution: Kaiser Wilhelm Institute for Physics, Berlin, Germany.
      year: 1917-1933

    - title: Professor of Theoretical Physics
      institution: Karl-Ferdinand University, Prague, Czechoslovakia
      year: 1911 - 1917
      description:

    - title: Associate Professor of Theoretical Physics
      institution: University of Zurich, Zurich, Switzerland
      year: 1909 - 1911

- title: Open Source Projects
  type: time_table
  contents:
    - title: <a href="https://github.com/alshedivat/al-folio">al-folio</a>
      year: 2015-now
      description: A beautiful, simple, clean, and responsive Jekyll theme for academics.

- title: Honors and Awards
  type: time_table
  contents:
    - year: 1921
      items: 
        - Nobel Prize in Physics 
        - Matteucci Medal
    - year: 2029
      items: 
        - Max Planck Medal

- title: Academic Interests
  type: nested_list
  contents:
    - title: Topic 1.
      items: 
        - Description 1.
        - Description 2.
    - title: Topic 2.
      items:
        - Description 1.
        - Description 2.

- title: Other Interests
  type: list
  contents:
    - <u>Hobbies:</u> Hobby 1, Hobby 2, etc.
  
  
  ---
layout: default
---
<!-- _layouts/cv.html -->
        <div class="post">

          <header class="post-header">
            <h1 class="post-title">{{ page.title }} {% if page.cv_pdf %}<a href="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a>{% endif %}</h1>
            <p class="post-description">{{ page.description }}</p>
          </header>

          <article>
            <div class="cv">
              {% for entry in site.data.cv %}
                <div class="card mt-3 p-3">
                  <h3 class="card-title font-weight-medium">{{ entry.title }}</h3>
                  <div>
                  {% if entry.type == "list" %}
                    {% include cv/list.html %}
                  {% elsif entry.type == "map" %}
                    {% include cv/map.html %}
                  {% elsif entry.type == "nested_list" %}
                    {% include cv/nested_list.html %}
                  {% elsif entry.type == "time_table" %}
                   {% include cv/time_table.html %}
                  {% else %}
                    {{ entry.contents }}
                  {% endif %}
                  </div>
                </div>
              {% endfor %}
              </div>
          </article>

        </div>
