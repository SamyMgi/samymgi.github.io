# Samy M.

## About me

---

Text about me...

## Showcase

---

<table>
    <tr>
        <td style="vertical-align:middle;">
            <div style="text-align:center;">
                <span style="background-color:#8e44ad; color:white; padding:3px 8px; border-radius:6px; font-size:12px;">
                    Pop Culture
                </span>
            </div>
            <br>
            <h3 style="text-align:center;">The Big 3 - Ratings Anime Breakdown</h3>
            <div class="slider" style="margin:auto; text-align:center;">
                <img src="img/dataviz_4_1.png" class="slide" style="display:block; width:100%; height:auto;">
                <img src="img/dataviz_4_2.png" class="slide" style="display:none; width:100%; height:auto;">
                <br>
                <button class="prev slider-btn">◀</button>
                <button class="next slider-btn">▶</button>
            </div>
            <p class="justified">
                In the anime community, "The Big 3" refers to the three iconic series of the 2000s: One Piece, Naruto and Bleach.
                <br>
                The dashboard explores MyAnimeList episode ratings across time, comparing yearly averages, arcs, fillers, top-rated episodes and more...
                <br>
            </p>
            <div style="text-align:center;">
                <a href="https://public.tableau.com/app/profile/samy.m6642/viz/TheBig3-AnimeRatingsBreakdown/TheBig3" target="_blank">View full viz</a>
            </div>
        </td>
    </tr>
    <tr>
        <td style="vertical-align:middle;">
            <div style="text-align:center;">
                <span style="background-color:#e67e22; color:white; padding:3px 8px; border-radius:6px; font-size:12px;">
                    Sports
                </span>
            </div>
            <h3 style="text-align:center;">UFC Expansion & Potential - Dashboard</h3>
            <div style="margin:auto; text-align:center;">
                <img src="img/dataviz_3.png" style="display:block; width:100%; height:auto;">
            </div>
            <p class="justified">
                Since its creation in 1993, the UFC has gradually expanded its presence across the world, going from 5 countries involved in 2002 to 29 by 2025.
                <br>
                This dashboard highlights the current state of UFC's international expansion and explores potential growth opportunities based on its active fighter roster.
            </p>
            <div style="text-align:center;">
                <a href="https://public.tableau.com/app/profile/samy.m6642/viz/UFCExpansionPotential-Dashboard/UFCExpansionPotential" target="_blank">View full viz</a>
            </div>
        </td>
    </tr>
    <tr>
        <td style="text-align:center; vertical-align:middle;">
            <h3>The Diamond's Path - Tribute to Dustin Poirier</h3>
            <p class="justified">
                Follow Dustin Poirier’s journey through the MMA world: key fights, milestones, and his impact both inside and outside the octagon.
                <br><br>
                <a href="https://public.tableau.com/app/profile/samy.m6642/viz/TheDiamondsPath-TributetoDustinPoirier/TheDiamondsPath" target="_blank">View full viz</a>
            </p>
            <span style="background-color:#e67e22; color:white; padding:3px 8px; border-radius:6px; font-size:12px;">
                Sports
            </span>
            <div class="slider" style="margin:auto; text-align:center;">
                <img src="img/dataviz_2_1.PNG" class="slide" style="display:block; width:100%; height:auto;">
                <img src="img/dataviz_2_2.PNG" class="slide" style="display:none; width:100%; height:auto;">
                <img src="img/dataviz_2_3.PNG" class="slide" style="display:none; width:100%; height:auto;">
                <br>
                <button class="prev slider-btn">◀</button>
                <button class="next slider-btn">▶</button>
            </div>
        </td>
    </tr>
</table>

## Contact

---

Contact links...

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
.justified {
  text-align: justify;
  text-justify: inter-word;
}

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

