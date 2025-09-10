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
                <button class="slider-btn" onclick="prevSlide()">◀</button>
                <button class="slider-btn" onclick="nextSlide()">▶</button>
            </div>
        </td>
    </tr>
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
            </div>
        </td>
    </tr>
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
                <button class="slider-btn" onclick="prevSlide()">◀</button>
                <button class="slider-btn" onclick="nextSlide()">▶</button>
            </div>
        </td>
    </tr>
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
            </div>
        </td>
    </tr>
</table>


<script>
let current = 0;
const slides = document.querySelectorAll('.slide');

function showSlide(index){
  slides.forEach((s,i)=> s.style.display = (i===index)?'block':'none');
}

function nextSlide(){
  current = (current + 1) % slides.length;
  showSlide(current);
}

function prevSlide(){
  current = (current - 1 + slides.length) % slides.length;
  showSlide(current);
}
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

