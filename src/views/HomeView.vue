<template>
  <div class="container">
    <div class="colors">
      <div class="pink-light"></div>
      <div class="pink"></div>
      <div class="purple"></div>
      <div class="turquoise"></div>
      <div class="blue"></div>
    </div>
    <div class="card">
      <div class="title">
        <h4 class="title__head">Panda app</h4>
        <h1 class="title__main">
          How to Write the Title Page of a Book [With Examples]
        </h1>
        <p class="title__sub">
          This is main page sub title, let's go. I am developer and ui designer,
          nice to meet you
        </p>
      </div>
    </div>
    <div class="card">
      <h1>Title H1</h1>
      <h2>Title H2</h2>
      <h3>Title H3</h3>
      <h4>Title H4</h4>
      <h5>Title H5</h5>
      <h6>Title H6</h6>
    </div>

    <div class="card">
      <h2>Badge card title</h2>
      <div class="badge badge--s-1">Badge size 1</div>
      <div class="badge badge--s-2">Badge size 2</div>
      <div class="badge badge--s-3">Badge size 3</div>
      <div class="badge badge--s-4">Badge size 4</div>
    </div>

    <div class="card">
      <div class="card__title">success button</div>
      <button class="button button--success">Click me</button>
    </div>
    <div class="card">
      <div class="card__title">danger button</div>
      <button class="button button--danger">Click me</button>
    </div>
    <div class="card">
      <div class="card__title">warning button</div>
      <button class="button button--warning">Click me</button>
    </div>
    <div class="card">
      <div class="card__title">primary button</div>
      <button class="button button--primary">Click me</button>
    </div>
    <div class="card">
      <div class="card__title">close button</div>
      <button class="button button--close"></button>
    </div>

    <div class="card">
      <label class="field field--valid">
        <span class="field__label">Name: </span>
        <input class="field__input" placeholder="Name" />
        <span class="field__message"></span>
      </label>
    </div>
    <div class="card">
      <label class="field field--invalid">
        <span class="field__label">Last name: </span>
        <input class="field__input" placeholder="Last name" />
        <span class="field__message">Invalid value</span>
      </label>
    </div>
    <div class="card">
      <label class="toggle">
        <!-- Hidden field -->
        <input type="checkbox" />
        <!-- Custom toggle -->
        <div class="toggle__wrapper">
          <div class="toggle__inner">
            <span class="toggle__state"></span>
          </div>
        </div>
        <!-- Label -->
        <span class="toggle__label">Do you have?</span>
      </label>
    </div>
    <div class="card">
      <!-- Radio 1 -->
      <label class="radio">
        <input name="choice" type="radio" />
        <div class="radio__wrapper">
          <span class="radio__state"></span>
        </div>
        <span class="radio__label">One choice 1</span>
      </label>
      <!-- Radio 2 -->
      <label class="radio">
        <input name="choice" type="radio" />
        <div class="radio__wrapper">
          <span class="radio__state"></span>
        </div>
        <span class="radio__label">One choice 2</span>
      </label>
      <!-- Radio 3 -->
      <label class="radio">
        <input name="choice" type="radio" />
        <div class="radio__wrapper">
          <span class="radio__state"></span>
        </div>
        <span class="radio__label">One choice 3</span>
      </label>
    </div>
    <div class="card">
      <label class="checkbox">
        <input type="checkbox" />
        <div class="checkbox__wrapper">
          <span class="checkbox__state"></span>
        </div>
        <span class="radio__label">Many choice 1</span>
      </label>
      <label class="checkbox">
        <input type="checkbox" />
        <div class="checkbox__wrapper">
          <span class="checkbox__state"></span>
        </div>
        <span class="radio__label">Many choice 2</span>
      </label>
      <label class="checkbox">
        <input type="checkbox" />
        <div class="checkbox__wrapper">
          <span class="checkbox__state"></span>
        </div>
        <span class="radio__label">Many choice 3</span>
      </label>
    </div>
    <div class="card">
      <select class="select">
        <option value="1">Option 1</option>
        <option value="2">Option 2</option>
        <option value="3">Option 3</option>
        <option value="4">Option 4</option>
      </select>
    </div>
    <!-- <div class="card">
      <div class="alert">
        <div class="alert__title"></div>
      </div>
    </div> -->
    <div class="card">
      <h2>Головний заголовок</h2>
      <p class="text text--s-1">
        У професійному контексті це часто буває, що приватні або корпоративні
        клієнти Corder публікацію, які будуть зроблені і представлені з
        фактичний зміст все ще не готовий. Подумайте про прес- блозі, що
        наповнилися змістом погодинна в день буде жити. Однак рецензенти схильні
        відволікатися на зрозумілій змісту, скажімо, випадкового тексту,
        скопійованого з газети або в інтернеті., Швидше за все, зосередитися на
        тексті, не звертаючи уваги на макет і його елементів.
      </p>
      <p class="text text--s-2">
        У професійному контексті це часто буває, що приватні або корпоративні
        клієнти Corder публікацію, які будуть зроблені і представлені з
        фактичний зміст все ще не готовий. Подумайте про прес- блозі, що
        наповнилися змістом погодинна в день буде жити. Однак рецензенти схильні
        відволікатися на зрозумілій змісту, скажімо, випадкового тексту,
        скопійованого з газети або в інтернеті., Швидше за все, зосередитися на
        тексті, не звертаючи уваги на макет і його елементів.
      </p>
      <p class="text text--s-3">
        У професійному контексті це часто буває, що приватні або корпоративні
        клієнти Corder публікацію, які будуть зроблені і представлені з
        фактичний зміст все ще не готовий. Подумайте про прес- блозі, що
        наповнилися змістом погодинна в день буде жити. Однак рецензенти схильні
        відволікатися на зрозумілій змісту, скажімо, випадкового тексту,
        скопійованого з газети або в інтернеті., Швидше за все, зосередитися на
        тексті, не звертаючи уваги на макет і його елементів.
      </p>
    </div>

    <!-- <div class="colors">
      <div class="turquoise"></div>
      <div class="grey"></div>
      <div class="blue"></div>
      <div class="purple"></div>
      <div class="pink-light"></div>
      <div class="pink"></div>
    </div> -->
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {}
}
</script>

<style lang="scss">
.card {
  padding: 15px 25px;
  margin-bottom: 10px;

  &__title {
    font-size: 18px;
    font-weight: 700;
    margin-bottom: 10px;
  }
}

.card > label {
  margin-bottom: 5px;
}
</style>
