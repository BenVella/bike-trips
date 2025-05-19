<div class="grid-container">
  <div class="grid-item">
    <a href="/content/sicily/day-1.html">Day 1</a>
  </div>
  <div class="grid-item">
    <a href="/content/sicily/day-2.html">Day 2</a>
  </div>
  <div class="grid-item">
    <a href="/content/sicily/day-3.html">Day 3</a>
  </div>
</div>

<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 16px;
}

.grid-item {
  padding: 16px;
  text-align: center;
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