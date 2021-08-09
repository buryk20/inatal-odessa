<template>
  <div id="app">
    <main>
      <article>
        <section class="banner-main" style="background-image:url('../src/assets/bunMainInstaOdessa.jpg');">
          <div class="text-ban-wrp">
            <div class="text-ban-back">
              <h1>{{maimText}}</h1>
              <h2>{{cityOd}}</h2>
            </div>
          </div>  
        </section>
      </article>
      <article class="text-bot-ban-wrp">
          <p class="__text-main-inst">{{interest}}</p>
      </article>
      <article class="line-wrp">
        <div class="line"></div>
      </article>
      <article>
        <div class="terms-action-back" style="background-image:url('src/assets/termsOfActiomBack.png');">
          <div class="terms-action-wrp">
            <h3>{{stock}}</h3>
            <p>{{cost}}
            </p>
            <p class="terms-action-text">{{residentsOfOdessa}}
            </p>
            <a href="#product"><button>{{catalog}}</button>
            </a>
          </div>
        </div>
        <!--мобилная версия-->
        <div class="terms-action-back-mob" style="background-image:url('../src/assets/linearMobInstOdessa.png');">
          <div class="terms-action-wrp">
            <h3>{{stock}}</h3>
            <p>{{residentsOfOdessa}}
            </p>
            <p class="terms-action-text">{{residentsOfOdessa}}
            </p>
            <a href="#product"><button>{{catalog}}</button>
            </a>
          </div>
        </div>
        <div class="terms-action-text-wrp">
          <h4>{{conditionOfPromotion}}</h4>
          <div class="mech-act-inst-odessa">
            <div class="mech-act-money">
              <p>{{ipCam}}</p>
              <img src="../src/assets/customerTerms.png" alt="Покупатель">
            </div>
            <img src="../src/assets/arrowTerms.svg" alt="стрелка">
            <div class="mech-act-inst">
              <p>{{ipCamText}}</p>
              <img src="../src/assets/instalTerms.png" alt="монтажник">
            </div>
          </div>
        </div>
        <section class="product-wrp">
          <p class="attention-text">{{attention}}</p>
          <p>{{timing}}</p>
          <article id="product" class="product-gallery">
            <!-- Тут должны быть товары которые будут копированы из основных категорий -->
          </article>
        </section>
        <article class="sali-wpr">
          <img class="sali-img" src="../src/assets/free-inst-odessa.png" alt="В ПАКЕТ БЕСПЛАТНЫХ УСЛУГ ПО УСТАНОВКЕ ВХОДИТ:">
          <div class="sali-list-wrp">
            <div class="wrp-sali-text">
              <h3>{{packageOfFreeServices}}</h3>
              <ul class="list-sale">
                <li>{{packageList1}}</li>
                <li>{{packageList2}}</li>
                <li>{{packageList3}}</li>
                <li>{{packageList4}}</li>
                <li>{{packageList5}}</li>
                <li>{{packageList6}}</li>
              </ul>
              <a href="#product"><button>В каталог</button>
              </a>
            </div>    
          </div>
        </article>
        <section class="expendable-materials-wrp">
          <p class="text-sale-ras">
            {{expendableMaterials}}
          </p>
          <div class="motto-wrp">
            <p>GREENVISION - это <span>просто!</span></p>
          </div>
        </section>
      </article>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      // Эти элементы удалить после того как будешь натянишь, переменые с укр рус текстом в соответсвующих апаках
      maimText: 'Змонтуємо вам безоплатно!',
      cityOd: 'для Одеси та передмістя!',
      interest: 'А Вы знали, что 80% случаев выхода из строя оборудования систем видеонаблюдения происходят по причине некачественного монтажа?',
      stock: 'АКЦИЯ ОТ GREENVISION: БЕСПЛАТНАЯ УСТАНОВКА СИСТЕМ ВИДЕОНАБЛЮДЕНИЯ',
      cost: 'Вы можете самостоятельно установить оборудование или воспользоваться услугами профессиональных монтажников. В первом случае – Вы потратите массу времени и сил, чтобы грамотно все подключить. Во втором – приготовьтесь выложить за работу специалистов 100-120$.',
      residentsOfOdessa: 'Акция «Бесплатная установка» – отличный вариант для жителей города Одессы получить эффективную систему видеонаблюдения при минимальных затратах на подключение оборудования!',
      catalog: 'В каталог',
      conditionOfPromotion: 'УСЛОВИЯ АКЦИИ:',
      ipCam: 'Вы приобретаете IP камеры на 200$ и более или любой комплект видеонаблюдения стоимостью 200$ и более (без жёстких дисков)',
      ipCamText: 'Получаете в подарок установку данного оборудования на своем объекте силами профессиональных монтажников из команды GreenVision.',
      attention: 'Внимание!',
      timing: 'Действие акции распространяется только на объекты, расположенные в пределах города Одесса.',
      packageOfFreeServices: 'В ПАКЕТ БЕСПЛАТНЫХ УСЛУГ ПО УСТАНОВКЕ ВХОДИТ:',
      packageList1: '• приезд специалиста на объект в любое удобное для Вас время;',
      packageList2: '• подключение акционного оборудования;',
      packageList3: '• наружная прокладка кабелей (без учёта дополнительных работ, а также настройки по выделяемому IP);',
      packageList4:'•	максимальная длина укладки кабеля не превышает 15 метров, предусмотренных в комплектации;',
      packageList5: '•	максимальная высота монтажа камеры не выше 5 метров;',
      packageList6: '•	рекомендации по эксплуатации системы видеонаблюдения.',
      expendableMaterials: 'Расходные материалы и дополнительное оборудование, которое необходимо для IP системы (коммутационные коробки, сетевой коммутатор, жёсткий диск, сетевой фильтр, видеорегистратор и т.д.) оплачиваются отдельно. Схема расположения камер не составляется.'
    }
  }
}
</script>

<style lang="scss" scoped>
@import "scss/abstract.scss";
@import "scss/main.scss";


</style>
