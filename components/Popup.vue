<!-- Please remove this file from your project -->
<template>
  <div>
    <!-- VIDEO POPUP -->
    <div class="popup" data-popup="video">
      <div class="popup__inner video__inner">
        <iframe
          id="video"
          width="100%"
          height="100%"
          src="https://www.youtube.com/embed/tgbNymZ7vqY"
        ></iframe>
        <!-- If you have Youtube video or any external video, use iframe above. Otherwise use video element below; -->
        <!-- <video id="video" src="/path-to-video"></video> -->
      </div>
    </div>

    <!-- OFFERS POPUP -->
    <div class="popup" data-popup="offers">
      <div class="popup__inner">
        <h2 class="popup__title">WHY CHOOSE ETRX ?</h2>
        <h2 class="popup__subtitle">Some of the things we do</h2>
        <div class="popup__content popup__offers">
          <div class="popup__offer">
            <h3 class="popup__offer-title">Marketing</h3>
            <ul>
              <li>Facbook ads</li>
              <li>Instagram ads</li>
              <li>Google ads</li>
              <li>Leaflet</li>
            </ul>
          </div>
          <div class="popup__offer">
            <h3 class="popup__offer-title">Analytics</h3>
            <ul>
              <li>Google Analytics</li>
              <li>Firebase</li>
              <li>Data science</li>
              <li>Dashboard</li>
            </ul>
          </div>
          <div class="popup__offer">
            <h3 class="popup__offer-title">Consulting</h3>
            <ul>
              <li>Growth</li>
              <li>First business</li>
              <li>Startup</li>
            </ul>
          </div>
          <div class="popup__offer">
            <h3 class="popup__offer-title">Research</h3>
            <ul>
              <li>Market research</li>
              <li>Competition reserach</li>
              <li>Product reserach</li>
            </ul>
          </div>
          <div class="popup__offer">
            <h3 class="popup__offer-title">Developing</h3>
            <ul>
              <li>WEB Design</li>
              <li>WEB apps</li>
              <li>Mobile apps</li>
              <li>Smart home apps</li>
            </ul>
          </div>
          <div class="popup__offer">
            <h3 class="popup__offer-title">Product growing</h3>
            <ul>
              <li>Influencers</li>
              <li>Invests</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- TEAM POPUP -->
    <div class="popup" data-popup="team">
      <div class="popup__inner">
        <h2 class="popup__title">PEOPLE BEHIND THIS</h2>
        <h3 class="popup__subtitle">
          Good company does not exist without good people
        </h3>
        <div class="slider">
          <div
            class="slider__arrow slider__arrow-left slider__arrow--disabled"
            data-follow="centered_y"
          >
            <img
              class="slider__arrow-icon"
              src="/resources/images/icons/arrow.svg"
              alt="Arrow icon"
            />
          </div>
          <div
            class="slider__arrow slider__arrow-right"
            data-follow="centered_y"
          >
            <img
              class="slider__arrow-icon"
              src="/resources/images/icons/arrow.svg"
              alt="Arrow icon"
            />
          </div>
          <div class="slider__inner" id="slider">
            <div class="slider__item">
              <img
                class="slider__item-image"
                src="/resources/images/persons/person1.jpg"
                alt="Team photo"
              />
              <div class="slider__item-content">
                <h2 class="slider__item-name">John Johnson</h2>
                <h2 class="slider__item-position">CEO</h2>
              </div>
            </div>
            <div class="slider__item">
              <img
                class="slider__item-image"
                src="/resources/images/persons/person2.jpg"
                alt="Team photo"
              />
              <div class="slider__item-content">
                <h2 class="slider__item-name">Ann Harling</h2>
                <h2 class="slider__item-position">CTO</h2>
              </div>
            </div>
            <div class="slider__item">
              <img
                class="slider__item-image"
                src="/resources/images/persons/person3.jpg"
                alt="Team photo"
              />
              <div class="slider__item-content">
                <h2 class="slider__item-name">Margarit Pitersen</h2>
                <h2 class="slider__item-position">HR</h2>
              </div>
            </div>
            <div class="slider__item">
              <img
                class="slider__item-image"
                src="/resources/images/persons/person4.jpg"
                alt="Team photo"
              />
              <div class="slider__item-content">
                <h2 class="slider__item-name">Harold Smith</h2>
                <h2 class="slider__item-position">MARKETING</h2>
              </div>
            </div>
            <div class="slider__item">
              <img
                class="slider__item-image"
                src="/resources/images/persons/person5.jpg"
                alt="Team photo"
              />
              <div class="slider__item-content">
                <h2 class="slider__item-name">David Sumer</h2>
                <h2 class="slider__item-position">PRODUCT</h2>
              </div>
            </div>
            <div class="slider__item">
              <img
                class="slider__item-image"
                src="/resources/images/persons/person6.jpg"
                alt="Team photo"
              />
              <div class="slider__item-content">
                <h2 class="slider__item-name">Jenifer Turdlo</h2>
                <h2 class="slider__item-position">DEVELOPER</h2>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
