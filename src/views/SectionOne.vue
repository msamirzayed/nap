<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-12 col-lg-8 col-12">
        <div
          id="carouselExampleIndicators"
          class="carousel slide"
          data-bs-ride="carousel"
        >
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="0"
              class="active dot-btn"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="1"
              class="dot-btn"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="2"
              class="dot-btn"
              aria-label="Slide 3"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <article class="card card--horizontal">
                <section class="card-content">
                  <header class="card__header">
                    <div class="card__header-upper">
                      <div class="card__header-upper__start">
                        <img
                          src="../assets/images/logo.png"
                          alt="card source"
                        />
                        <span class="card__header-upper__start-source"
                          >بوابة الأهرام</span
                        >
                      </div>
                      <div class="card__header-upper__end">
                        <span class="icon-three-dots">
                          <img src="../assets/images/dots-white.svg" alt="" />
                        </span>
                        <div class="likes">
                          <span class="icon-like">
                            <img src="../assets/images/like-white.svg" alt="" />
                          </span>
                        </div>
                        <p>244</p>
                      </div>
                    </div>
                    <div class="card__header-bottom">
                      <a href=""></a>
                      <h3>
                        إنهاء تجهيزات المتحف المصرى الكبير على أكمل وجه الرئيس:
                        رفع كفاءة المنشآت فى محيط الموقع بما يتواكب مع قيمته
                      </h3>
                      <div class="card__header-bottom__extra-info">
                        <span> أخبار مصر . منذ ٣ ساعات </span>
                      </div>
                    </div>
                  </header>
                  <div class="card__image-container">
                    <a>
                      <img
                        src="../assets/images/img-1.jpg"
                        class="d-block w-100 card_image--vertical"
                        alt="card image"
                      />
                    </a>
                  </div>
                </section>
              </article>
            </div>
            <div class="carousel-item">
              <article class="card card--horizontal">
                <section class="card-content">
                  <header class="card__header">
                    <div class="card__header-upper">
                      <div class="card__header-upper__start">
                        <img
                          src="../assets/images/logo.png"
                          alt="card source"
                        />
                        <span class="card__header-upper__start-source"
                          >بوابة الأهرام</span
                        >
                      </div>
                      <div class="card__header-upper__end">
                        <span class="icon-three-dots">
                          <img src="../assets/images/dots-white.svg" alt="" />
                        </span>
                        <div class="likes">
                          <span class="icon-like">
                            <img src="../assets/images/like-white.svg" alt="" />
                          </span>
                        </div>
                        <p>244</p>
                      </div>
                    </div>
                    <div class="card__header-bottom">
                      <a href=""></a>
                      <h3>
                        إنهاء تجهيزات المتحف المصرى الكبير على أكمل وجه الرئيس:
                        رفع كفاءة المنشآت فى محيط الموقع بما يتواكب مع قيمته
                      </h3>
                      <div class="card__header-bottom__extra-info">
                        <span> أخبار مصر . منذ ٣ ساعات </span>
                      </div>
                    </div>
                  </header>
                  <div class="card__image-container">
                    <a>
                      <img
                        src="../assets/images/img-1.jpg"
                        class="d-block w-100 card_image--vertical"
                        alt="card image"
                      />
                    </a>
                  </div>
                </section>
              </article>
            </div>
            <div class="carousel-item">
              <article class="card card--horizontal">
                <section class="card-content">
                  <header class="card__header">
                    <div class="card__header-upper">
                      <div class="card__header-upper__start">
                        <img
                          src="../assets/images/logo.png"
                          alt="card source"
                        />
                        <span class="card__header-upper__start-source"
                          >بوابة الأهرام</span
                        >
                      </div>
                      <div class="card__header-upper__end">
                        <span class="icon-three-dots">
                          <img
                            class=""
                            src="../assets/images/dots-white.svg"
                            alt=""
                          />
                        </span>
                        <div class="likes">
                          <span class="icon-like">
                            <img
                              class=""
                              src="../assets/images/like-white.svg"
                              alt=""
                            />
                          </span>
                        </div>
                        <p>244</p>
                      </div>
                    </div>
                    <div class="card__header-bottom">
                      <a href=""></a>
                      <h3>
                        إنهاء تجهيزات المتحف المصرى الكبير على أكمل وجه الرئيس:
                        رفع كفاءة المنشآت فى محيط الموقع بما يتواكب مع قيمته
                      </h3>
                      <div class="card__header-bottom__extra-info">
                        <span> أخبار مصر . منذ ٣ ساعات </span>
                      </div>
                    </div>
                  </header>
                  <div class="card__image-container">
                    <a>
                      <img
                        src="../assets/images/img-1.jpg"
                        class="d-block w-100 card_image--vertical"
                        alt="card image"
                      />
                    </a>
                  </div>
                </section>
              </article>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-12 col-12 col-lg-4">
        <div class="row card--horizontal--contain">
          <article
            class="card card--horizontal col-md-6 col-12 col-lg-12 content__hero"
          >
            <section class="card-content">
              <header class="card__header">
                <div class="card__header-upper">
                  <div class="card__header-upper__start">
                    <img src="../assets/images/logo.png" alt="card source" />
                    <span class="card__header-upper__start-source"
                      >بوابة الأهرام</span
                    >
                  </div>
                  <div class="card__header-upper__end">
                    <span class="icon-three-dots">
                      <img src="../assets/images/dots-white.svg" alt="" />
                    </span>
                    <div class="likes">
                      <span class="icon-like">
                        <img src="../assets/images/like-white.svg" alt="" />
                      </span>
                    </div>
                    <p>244</p>
                  </div>
                </div>
                <div class="card__header-bottom">
                  <a href=""></a>
                  <h3>
                    إنهاء تجهيزات المتحف المصرى الكبير على أكمل وجه الرئيس: رفع
                    كفاءة المنشآت فى محيط الموقع بما يتواكب مع قيمته
                  </h3>
                  <div class="card__header-bottom__extra-info">
                    <span> أخبار مصر . منذ ٣ ساعات </span>
                  </div>
                </div>
              </header>
              <div class="card__image-container">
                <a>
                  <img
                    src="../assets/images/img-1.jpg"
                    class="d-block w-100 card_image--vertical"
                    alt="card image"
                  />
                </a>
              </div>
            </section>
          </article>
          <article
            class="card card--horizontal col-md-6 col-12 col-lg-12 content__hero"
          >
            <section class="card-content">
              <header class="card__header">
                <div class="card__header-upper">
                  <div class="card__header-upper__start">
                    <img src="../assets/images/logo.png" alt="card source" />
                    <span class="card__header-upper__start-source"
                      >أخبار اليوم</span
                    >
                  </div>
                  <div class="card__header-upper__end">
                    <span class="icon-three-dots">
                      <img src="../assets/images/dots-white.svg" alt="" />
                    </span>
                    <div class="likes">
                      <span class="icon-like">
                        <img src="../assets/images/like-white.svg" alt="" />
                      </span>
                    </div>
                    <p>244</p>
                  </div>
                </div>
                <div class="card__header-bottom">
                  <a href=""></a>
                  <h3>الرئيس السيسي يهنئ سلطان عمان بحلول شهر رمضان الكريم</h3>
                  <div class="card__header-bottom__extra-info">
                    <span> أخبار مصر . ٢ / ٤ / ٢ ٠٢ ٢ </span>
                  </div>
                </div>
              </header>
              <div class="card__image-container">
                <a>
                  <img
                    src="../assets/images/img-3.jpg"
                    class="d-block w-100 card_image--vertical"
                    alt="card image"
                  />
                </a>
              </div>
            </section>
          </article>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionOne",
};
</script>
