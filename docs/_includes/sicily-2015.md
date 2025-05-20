<div class="grid-container">
  <div class="grid-item">
    {% capture day1_content %}
      {% include /sicily-2015/day-1.md %}
    {% endcapture %}
    {{ day1_content | markdownify }}
  </div>
  <div class="grid-item">
    {% capture day1_content %}
      {% include /sicily-2015/day-2.md %}
    {% endcapture %}
    {{ day1_content | markdownify }}
  </div>
  <div class="grid-item">
    {% capture day1_content %}
      {% include /sicily-2015/day-3.md %}
    {% endcapture %}
    {{ day1_content | markdownify }}
  </div>
</div>

<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 16px;
}

.grid-item {
  padding: 16px;
  text-align: justify;
  background-color: #f4f4f4;
  border: 1px solid #ddd;
  border-radius: 8px;
}

.grid-item a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

@media (max-width: 768px) {
  .grid-container {
    grid-template-columns: 1fr;
  }
}
</style>