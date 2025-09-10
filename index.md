# Data Scientist & Analyst

## Showcase

<table>
    <tr>
        <td style="text-align:center; vertical-align:middle; width:35%;">
            <h3>The Big 3 - Ratings Anime Breakdown</h3>
            <p>
                Description.
                <br><br>
                <a href="" target="_blank">View full viz</a>
            </p>
            <span style="background-color:#8e44ad; color:white; padding:3px 8px; border-radius:6px; font-size:12px;">
                Pop Culture
            </span>
        </td>
        <td width="65%">
            <div class="slider" style="margin:auto; text-align:center;">
                <img src="img/dataviz_4_1.png" class="slide" style="display:block; width:100%; height:auto;">
                <img src="img/dataviz_4_2.png" class="slide" style="display:none; width:100%; height:auto;">
                <br>
                <button class="prev slider-btn">◀</button>
                <button class="next slider-btn">▶</button>
            </div>
        </td>
    </tr>
    <tr>
        <td style="text-align:center; vertical-align:middle; width:35%;">
            <h3>UFC Expansion & Potential - Dashboard</h3>
            <p>
                Description.
                <br><br>
                <a href="" target="_blank">View full viz</a>
            </p>
            <span style="background-color:#8e44ad; color:white; padding:3px 8px; border-radius:6px; font-size:12px;">
                Pop Culture
            </span>
        </td>
        <td width="65%">
            <div style="margin:auto; text-align:center;">
                <img src="img/dataviz_3.png" style="display:block; width:100%; height:auto;">
            </div>
        </td>
    </tr>
    <tr>
        <td style="text-align:center; vertical-align:middle; width:35%;">
            <h3>The Diamond's Path - Tribute to Dustin Poirier</h3>
            <p>
                Description.
                <br><br>
                <a href="" target="_blank">View full viz</a>
            </p>
            <span style="background-color:#8e44ad; color:white; padding:3px 8px; border-radius:6px; font-size:12px;">
                Pop Culture
            </span>
        </td>
        <td width="65%">
            <div class="slider" style="margin:auto; text-align:center;">
                <img src="img/dataviz_4_1.png" class="slide" style="display:block; width:100%; height:auto;">
                <img src="img/dataviz_4_2.png" class="slide" style="display:none; width:100%; height:auto;">
                <br>
                <button class="prev slider-btn">◀</button>
                <button class="next slider-btn">▶</button>
            </div>
        </td>
    </tr>
    <tr>
        <td style="text-align:center; vertical-align:middle; width:35%;">
            <h3>2025 NBA Finals - Game Flow Dashboard</h3>
            <p>
                Description.
                <br><br>
                <a href="" target="_blank">View full viz</a>
            </p>
            <span style="background-color:#8e44ad; color:white; padding:3px 8px; border-radius:6px; font-size:12px;">
                Pop Culture
            </span>
        </td>
        <td width="65%">
            <div style="margin:auto; text-align:center;">
                <img src="img/dataviz_1.png" style="display:block; width:100%; height:auto;">
            </div>
        </td>
    </tr>
</table>


<script>
document.querySelectorAll('.slider').forEach(slider => {
  const slides = slider.querySelectorAll('.slide');
  const prev = slider.querySelector('.prev');
  const next = slider.querySelector('.next');
  let current = 0;

  const showSlide = (index) => {
    slides.forEach((s, i) => s.style.display = (i === index ? 'block' : 'none'));
  };

  next.addEventListener('click', () => {
    current = (current + 1) % slides.length;
    showSlide(current);
  });

  prev.addEventListener('click', () => {
    current = (current - 1 + slides.length) % slides.length;
    showSlide(current);
  });

  showSlide(current);
});
</script>


<style>
.slider-btn {
  background-color: #407ab4;
  color: white;
  border: none;
  border-radius: 6px;
  padding: 8px 14px;
  margin: 5px;
  cursor: pointer;
  font-size: 18px;
  transition: background-color 0.3s, transform 0.2s;
}

.slider-btn:hover {
  background-color: #2a6495;
  transform: scale(1.1);
}

.slider-btn:active {
  transform: scale(0.95);
}
</style>

