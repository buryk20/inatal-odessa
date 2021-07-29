<template>
  <div id="app">
    <main>
      <article>
        <section class="banner-main" style="background-image:url('../src/assets/bunMainInstaOdessa.jpg');">
          <div class="text-ban-wrp">
            <div class="text-ban-back">
              <h1>Змонтуємо вас безоплатно!</h1>
              <h2>для Одеси та передмістя!</h2>
            </div>
          </div>  
        </section>
        <!-- <section class="banner-main-mob" style="background-image:url('../src/assets/bunMainInstaOdessaMob.jpg');">
          <div class="text-ban-wrp">
            <div class="text-ban-back">
              <h1>Змонтуємо вас безоплатно!</h1>
              <h2>для Одеси та передмістя!</h2>
            </div>
          </div>  
        </section> -->
      </article>
      <article class="text-bot-ban-wrp">
          <p class="__text-main-inst">А Вы знали, что 80% случаев выхода из строя оборудования систем видеонаблюдения происходят по причине некачественного монтажа?</p>
      </article>
      <article class="line-wrp">
        <div class="line"></div>
      </article>
      <article>
        <div class="terms-action-back" style="background-image:url('src/assets/termsOfActiomBack.png');">
          <div class="terms-action-wrp">
            <h3>АКЦИЯ ОТ GREENVISION: БЕСПЛАТНАЯ УСТАНОВКА СИСТЕМ ВИДЕОНАБЛЮДЕНИЯ</h3>
            <p>    Вы можете самостоятельно установить оборудование или воспользоваться услугами профессиональных монтажников. В первом случае – Вы потратите массу времени и сил, чтобы грамотно все подключить. Во втором – приготовьтесь выложить за работу специалистов 100-120$.
            </p>
            <p class="terms-action-text">Акция «Бесплатная установка» – отличный вариант для жителей города Одессы получить эффективную систему видеонаблюдения при минимальных затратах на подключение оборудования!
            </p>
            <a href="#product"><button>В каталог</button>
            </a>
          </div>
        </div>
        <!--мобилная версия-->
        <div class="terms-action-back-mob" style="background-image:url('../src/assets/linearMobInstOdessa.png');">
          <div class="terms-action-wrp">
            <h3>АКЦИЯ ОТ GREENVISION: БЕСПЛАТНАЯ УСТАНОВКА СИСТЕМ ВИДЕОНАБЛЮДЕНИЯ</h3>
            <p>    Вы можете самостоятельно установить оборудование или воспользоваться услугами профессиональных монтажников. В первом случае – Вы потратите массу времени и сил, чтобы грамотно все подключить. Во втором – приготовьтесь выложить за работу специалистов 100-120$.
            </p>
            <p class="terms-action-text">Акция «Бесплатная установка» – отличный вариант для жителей города Одессы получить эффективную систему видеонаблюдения при минимальных затратах на подключение оборудования!
            </p>
            <a href="#product"><button>В каталог</button>
            </a>
          </div>
        </div>
        <div class="terms-action-text-wrp">
          <h4>УСЛОВИЯ АКЦИИ:</h4>
          <div class="mech-act-inst-odessa">
            <div class="mech-act-money">
              <p>Вы приобретаете IP камеры на 200$ и более или любой комплект видеонаблюдения стоимостью 200$ и более (без жёстких дисков)</p>
              <img src="../src/assets/customerTerms.png" alt="Покупатель">
            </div>
            <img src="../src/assets/arrowTerms.svg" alt="стрелка">
            <div class="mech-act-inst">
              <p>Получаете в подарок установку данного оборудования на своем объекте силами профессиональных монтажников из команды GreenVision.</p>
              <img src="../src/assets/instalTerms.png" alt="монтажник">
            </div>
          </div>
        </div>
        <section class="product-wrp">
          <p class="attention-text">Внимание!</p>
          <p>Действие акции распространяется только на объекты, расположенные в пределах города Одесса.</p>
          <article id="product" class="product-gallery">
            <!-- Тут должны быть товары которые будут копированы из основных категорий -->
          </article>
        </section>
        <article>
            <div class="sali-list-wrp" style="background-image:url('../src/assets/free-inst-odessa.png');">
              <h3>В ПАКЕТ БЕСПЛАТНЫХ УСЛУГ ПО УСТАНОВКЕ ВХОДИТ:</h3>
              <ul class="list-sale">
                <li>• приезд специалиста на объект в любое удобное для Вас время;</li>
                <li>• подключение акционного оборудования;</li>
                <li>• наружная прокладка кабелей (без учёта дополнительных работ, а также настройки по выделяемому IP);</li>
                <li>•	максимальная длина укладки кабеля не превышает 15 метров, предусмотренных в комплектации;
                </li>
                <li>•	максимальная высота монтажа камеры не выше 5 метров;</li>
                <li>•	рекомендации по эксплуатации системы видеонаблюдения.</li>
              </ul>
              <a href="#product"><button>В каталог</button>
              </a>
            </div>
            <p class="text-sale-ras">
              Расходные материалы и дополнительное оборудование, которое необходимо для IP системы (коммутационные коробки, сетевой коммутатор, жёсткий диск, сетевой фильтр, видеорегистратор и т.д.) оплачиваются отдельно. Схема расположения камер не составляется.
            </p>
            <img class="slogon" src="../src/assets/GREENVISION-slog.svg" alt="GreenVision - это просто">
        </article>
      </article>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss" scoped>
@import "scss/abstract.scss";
@import "scss/main.scss";


</style>


Блок второй после товаров 
<article>
        <div style="background-image:url('src/assets/termsOfActiomBack.png');">
          <h3>В ПАКЕТ БЕСПЛАТНЫХ УСЛУГ ПО УСТАНОВКЕ ВХОДИТ:</h3>
          <ul>
            <li>• приезд специалиста на объект в любое удобное для Вас время;</li>
            <li>• подключение акционного оборудования;</li>
            <li>• наружная прокладка кабелей (без учёта дополнительных работ, а также настройки по выделяемому IP);</li>
            <li>•	максимальная длина укладки кабеля не превышает 15 метров, предусмотренных в комплектации;
            </li>
            <li>•	максимальная высота монтажа камеры не выше 5 метров;</li>
            <li>•	рекомендации по эксплуатации системы видеонаблюдения.</li>
          </ul>
        </div>
      </article>