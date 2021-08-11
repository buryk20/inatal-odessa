<template>
  <div id="app">
    <main>
      <article>
        <section class="banner-main" style="background-image:url('../src/assets/bunMainInstaOdessa.jpg');">
          <div class="text-ban-wrp">
            <div class="text-ban-back">
              <h1>{{__('install-odessa.maimText')}}</h1>
              <h2>{{__('install-odessa.cityOd')}}</h2>
            </div>
          </div>  
        </section>
      </article>
      <article class="text-bot-ban-wrp">
          <p class="__text-main-inst">{{__('install-odessa.interest')}}</p>
      </article>
      <article class="line-wrp">
        <div class="line"></div>
      </article>
      <article>
        <div class="terms-action-back" style="background-image:url('src/assets/termsOfActiomBack.png');">
          <div class="terms-action-wrp">
            <h3>{{__('install-odessa.stock')}}</h3>
            <p>{{__('install-odessa.cost')}}
            </p>
            <p class="terms-action-text">{{__('install-odessa.residentsOfOdessa')}}
            </p>
            <a href="#product"><button>{{__('install-odessa.catalog')}}</button>
            </a>
          </div>
        </div>
        <!--мобилная версия-->
        <div class="terms-action-back-mob" style="background-image:url('../src/assets/linearMobInstOdessa.png');">
          <div class="terms-action-wrp">
            <h3>{{__('install-odessa.stock')}}</h3>
            <p>{{__('install-odessa.residentsOfOdessa')}}
            </p>
            <p class="terms-action-text">{{__('install-odessa.residentsOfOdessa')}}
            </p>
            <a href="#product"><button>{{__('install-odessa.catalog')}}</button>
            </a>
          </div>
        </div>
        <div class="terms-action-text-wrp">
          <h4>{{__('install-odessa.conditionOfPromotion')}}</h4>
          <div class="mech-act-inst-odessa">
            <div class="mech-act-money">
              <p>{{__('install-odessa.ipCam')}}</p>
              <img src="../src/assets/customerTerms.png" alt="Покупатель">
            </div>
            <img src="../src/assets/arrowTerms.svg" alt="стрелка">
            <div class="mech-act-inst">
              <p>{{__('install-odessa.ipCamText')}}</p>
              <img src="../src/assets/instalTerms.png" alt="монтажник">
            </div>
          </div>
        </div>
        <section class="product-wrp">
          <p class="attention-text">{{__('install-odessa.attention')}}</p>
          <p>{{__('install-odessa.timing')}}</p>
          <article id="gallery" class="product-gallery">
            <!-- Тут должны быть товары которые будут копированы из основных категорий -->
          </article>
        </section>
        <article class="sali-wpr">
          <img class="sali-img" src="../src/assets/free-inst-odessa.png" alt="В ПАКЕТ БЕСПЛАТНЫХ УСЛУГ ПО УСТАНОВКЕ ВХОДИТ:">
          <div class="sali-list-wrp">
            <div class="wrp-sali-text">
              <h3>{{__('install-odessa.packageOfFreeServices')}}</h3>
              <ul class="list-sale">
                <li>{{__('install-odessa.packageList1')}}</li>
                <li>{{__('install-odessa.packageList2')}}</li>
                <li>{{__('install-odessa.packageList3')}}</li>
                <li>{{__('install-odessa.packageList4')}}</li>
                <li>{{__('install-odessa.packageList5')}}</li>
                <li>{{__('install-odessa.packageList6')}}</li>
              </ul>
              <a href="#product"><button>{{__('install-odessa.catalog')}}</button>
              </a>
            </div>    
          </div>
        </article>
        <section class="expendable-materials-wrp">
          <p class="text-sale-ras">
            {{__('install-odessa.expendableMaterials')}}
          </p>
          <div class="motto-wrp">
            <p>{{__('install-odessa.tagline')}}<span>{{__('install-odessa.taglineText')}}</span></p>
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
      maimText: 'Змонтуємо вам безоплатно!'
    }
  }
}
</script>

<style lang="scss" scoped>
@import "scss/abstract.scss";
@import "scss/main.scss";


</style>
