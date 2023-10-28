# Сторінки та Pop-up
У цьому розділі ви можете редагувати потрібні вам сторінки або pop-up які присутні у вашому магазині.

# Pop-up
Після відкритя редактору у вас є можливість змініти в залежності від типу
- Затримка перед показом 
- Відобразити лише перший раз при відкритті сайту
- Редактор коду pop-up

### Як користуватись?

Щоб увімкнути попап вам достатньо додати код у редактор.
***
Ми пропонуємо вам декілька шаблонів для користування або ви можете самостійно створити свій попап якщо у вас є знання HTML, CSS.


Детальніше про можливості:
- Затримка перед показом це час у секундах який означає - через скільки часу цей попап буде відображений на стрінці клієнта. Наприклад якщо 0 він буде відображений одразу, якщо 5 він відобразится через 5 секунд на сайті, якщо 30 тоді він відобразится через 30 секунд... Використовуйте його для Акцій або щоб робити опитування ваших клієнтів.
- Відобразити лише перший раз при відкритті сайту - Означає що після закриття pop-up він більше не буде відображатись у клієнта та набридати йому.
- Редактор коду здатний додати на ваш сайт будь який HTML, CSS код. Його можливості обмежені лише вашою уявою та знанням HTML, CSS

## Наші шаблони
Скопіюйте потрібней вам код код, та додайте вставте в редактор.
### Будьте уважні !
У шаблонах що ми пропонуємо присутні текст "Lorem ipsum" ви можете редагувати його прямо у редакторі але редагуйте лише текст - не видаліть випадково `</p>` на кінці речення.

### Pop-up на старті
Якщо хочете щоб користувачі підтвердили свій вік при відкриті сайту.

    <div class="body">
        <div class="info-modal age-modal">
          <div class="modal-wrapper">
            <div class="modal-holder">
              <div class="content-modal">
                <div class="logo">
                  <img src="https://ux.im/images/landing-page/logo.svg">
                </div>
                <h2>Перевірка віку</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                <div class="button-holder">
                  <button href="javascript:void(0)" class="default-btn red-btn make-exit">
                    <span class="btn-text ">Мені немає 18 років :(</span>
                  </button>
                  <button href="javascript:void(0)" class="default-btn green-btn make-close">
                    <span class="btn-text">Мені 18 років і більше</span>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>
    <div class="back-blur"></div>
    <style type="text/css">.back-blur{background-color: black!important;}</style>

### Pop-up при спробі закрити магазин
Якщо хочете щоб при спробі закрити сайт клієнту пропонувалось отримати консультацію.

    <div class="body">
        <div class="info-modal consultant-modal ">
          <div class="modal-wrapper " >
            <div class="close make-close">
              <img src="/images/icons/close.svg">
            </div>
            <div class="modal-picture">
              <div class="img-desc bg" style="background-image:url('/images/consultant-modal-bg.png');"></div>
              <div class="img-mob bg" style="background-image:url('/images/consultant-modal-bg-mob.png');"></div>
            </div>
            <div class="modal-holder">
              <div class="content-modal">
                <h2>Отримай індивідуальну <br/>консультацію</h2>
                <p>Lorem ipsum dolor sit amet, adipisicing <br/>elit, sed do eiusmod
                  tempor</p>
                <div class="icons-items">
                  <div class="item">
                    <div class="icons">
                      <img src="/images/icons/call-center.svg" alt="">
                    </div>
                    <div class="item-text">
                      Безкоштовна <br/>косультація
                    </div>
                  </div>
                  <div class="item">
                    <div class="icons">
                      <img src="/images/icons/24-hours.svg" alt="">
                    </div>
                    <div class="item-text">
                      Завжди <br/>на зв'язку
                    </div>
                  </div>
                </div>
                <div class="button-holder">
                  <button href="javascript:void(0)" class="default-btn">
                    <span class="btn-text">Замовити консультацію</span>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>
    <div class="back-blur make-close"></div>