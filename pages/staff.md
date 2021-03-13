---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% include landing_staff.html image='/assets/img/staff-photos/stat100_impact_website.png'%}
<!-- {% include landing_small.html title='About Us' %} -->

<div id="about" class="offset" style="margin-top: 5px;">
  <div class="bg-light py-4">
    <div class="container py-4">
      <div class="col-12 text-center">

      <div class="text-center" style="margin-bottom: 3em;">
        <h2 class="display-5 font-weight-light">Course Staff</h2>
      </div>

      <p class="lead text-left" style="font-size: 1.15em;">{{ site.data.staff.about }}</p>
      </div>

      <div class="col-xl-12 col-sm-12 mb-5 d-flex justify-content-center">
        <div class="staff-card bg-white rounded shadow-sm py-5 px-4 d-flex justify-content-center"><a href="{{ site.data.info.rickroll }}"><img src="{{ site.baseurl }}/assets/img/staff-photos/stat100_impact_website.png" class="img-fluid mb-3 img-thumbnail shadow-sm"></a>
        </div>
      </div>

      <div class="row text-center">
        {% include staff_cards.html role='Lead Instructor' %}
        {% include staff_cards.html role='Course Assistant' %}
      </div>

    </div>
  </div>
</div>
