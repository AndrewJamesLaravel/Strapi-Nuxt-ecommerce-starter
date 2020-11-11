<template>
  <div>
    <!--Hero-->
    <section class="hero">
      <div class="hero-body">
        <div class="container">
          <!-- Main container -->
          <nav class="level">
            <!-- Left side -->
            <div class="level-left">
              <div class="level-item">
                <h1 class="title">Hero title</h1>
              </div>
            </div>

            <!-- Right side -->
            <div class="level-right">
              <p class="level-item"><strong>All</strong></p>
              <p class="level-item"><a>Published</a></p>
              <p class="level-item"><a>Drafts</a></p>
              <p class="level-item"><a>Deleted</a></p>
              <!--Search-->
              <div class="level-item">
                <div class="field has-addons">
                  <p class="control">
                    <input
                      class="input"
                      type="text"
                      placeholder="Find a post"
                    />
                  </p>
                  <p class="control">
                    <button class="button">Search</button>
                  </p>
                </div>
              </div>
              <!--End Search-->
              <p class="level-item"><a class="button is-success">New</a></p>
            </div>
          </nav>
        </div>
      </div>
    </section>
    <!--End Hero-->
    <!--Nav-->
    <nav
      class="navbar is-danger"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="columns">
        <div class="column is-7"></div>
        <div class="navbar-brand">
          <a
            role="button"
            class="navbar-burger burger"
            aria-label="menu"
            aria-expanded="false"
            data-target="navbarBasicExample"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-start">
            <a class="navbar-item"> Каталог </a>

            <a class="navbar-item"> Акции </a>

            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link"> Услуги </a>

              <div class="navbar-dropdown">
                <a class="navbar-item has-text-dark"> Вышивка </a>
                <a class="navbar-item has-text-dark">
                  Прямая печать по ткани
                </a>
                <a class="navbar-item has-text-dark"> Шелкография </a>
                <hr class="navbar-divider" />
                <a class="navbar-item has-text-dark"> Лазерная гравировка </a>
              </div>
            </div>
            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link"> Как купить </a>

              <div class="navbar-dropdown">
                <a class="navbar-item has-text-dark"> Условия оплаты </a>
                <a class="navbar-item has-text-dark"> Условия доставки </a>
                <a class="navbar-item has-text-dark"> Возврат товара </a>
                <a class="navbar-item has-text-dark"> Помощь </a>
                <hr class="navbar-divider" />
                <a class="navbar-item has-text-dark"> Сообщить о проблеме </a>
              </div>
            </div>
            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link"> Компания </a>

              <div class="navbar-dropdown">
                <a class="navbar-item has-text-dark"> Новости </a>
                <a class="navbar-item has-text-dark"> Отзывы </a>
                <a class="navbar-item has-text-dark"> Политика </a>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <a class="button is-primary">
              <strong>Sign up</strong>
            </a>
            <a class="button is-light"> Log in </a>
          </div>
        </div>
        <div class="column is-12"></div>
      </div>
    </nav>
    <!--End Nav-->
    <!--Breadcrumbs-->
    <div class="container">
      <nav
        class="breadcrumb is-dark has-succeeds-separator"
        aria-label="breadcrumbs"
      >
        <ul>
          <li><a href="#">Bulma</a></li>
          <li><a href="#">Documentation</a></li>
          <li><a href="#">Components</a></li>
          <li class="is-active">
            <a href="#" aria-current="page">Breadcrumb</a>
          </li>
        </ul>
      </nav>
    </div>
    <!--End Breadcrumbs-->
    <!--Product Info-->
    <div class="section">
      <div class="container">
        <div class="columns is-fixed-top">
          <div class="column is-2">
            <nav class="left-side-bar">
              <ul class="menu--vert">
                <li>
                  <a href="#">item-1</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>

                <li>
                  <a href="#">item-2</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>

                <li>
                  <a href="#">item-3</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>

                <li>
                  <a href="#">item-4</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>

                <li>
                  <a href="#">item-5</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>

                <li>
                  <a href="#">item-6</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>

                <li>
                  <a href="#">item-7</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>

                <li>
                  <a href="#">item-8</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>

                <li>
                  <a href="#">item-9</a>
                  <ul class="submenu">
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                    <li>
                      <a href="#"
                        ><article class="media">
                          <figure class="media-left">
                            <p class="image is-64x64">
                              <img src="~/assets/images/bag.jpg" />
                            </p>
                          </figure>
                          <div class="media-content">
                            <div class="field">
                              <p class="control">Sub Category</p>
                            </div>
                          </div>
                        </article></a
                      >
                    </li>
                  </ul>
                </li>
              </ul>
            </nav>
          </div>
          <div class="column is-10">
            <p>
              Chaos is not soft in hell, the body of love, or abstruse places,
              but everywhere.Simmer aged ramens in a sauté pan with mint sauce
              for about an hour to chamfer their sweetness.
            </p>
          </div>
        </div>
      </div>
    </div>

    <!--Footer-->
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>Bulma</strong> by
          <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is
          licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The
          website content is licensed
          <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/"
            >CC BY NC SA 4.0</a
          >.
        </p>
      </div>
    </footer>
    <!--End Footer-->
  </div>
</template>

<script>
export default {}
</script>

<style>
nav.breadcrumb.is-dark.has-succeeds-separator {
  margin-bottom: 1.5rem;
  margin-top: 1.5rem;
}

.section {
  padding: 1rem 1.5rem;
}

.left-side-bar ul {
  display: flex;
  padding-left: 0;
  list-style: none;
}

.left-side-bar li {
  position: relative;
}

.left-side-bar li:focus-within > .submenu,
.left-side-bar li:hover > .submenu {
  /*display: flex;*/
  clip: auto;
  width: auto;
  height: auto;
  margin: 0;
}

.left-side-bar a {
  display: block;
  color: black;
  text-decoration: none;
  border-bottom: 1px solid #feebef;
  background-color: #f8f5f7;
  padding: 1em;
  white-space: nowrap;
}

.left-side-bar li:hover > a,
.left-side-bar a:hover {
  background-color: #f7e7ef;
}

.left-side-bar a:focus {
  outline: none;
  background-color: coral;
}

.left-side-bar .submenu {
  /*display: none;*/
  flex-direction: row;
  position: absolute;
  /*padding-top: 1em;*/

  clip: rect(0 0 0 0);
  width: 1px;
  height: 1px;
  margin: -1px;
}

.left-side-bar .menu--vert {
  flex-direction: column;
  width: 200px;
}

.left-side-bar .menu--vert .submenu {
  top: 0;
  left: 100%;
}

.footer {
  background-color: #dfd8d9;
}
</style>
