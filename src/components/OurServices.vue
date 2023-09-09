<!-- <template>
    <div class="our-services">
      <h2 class="large-title">Our Services</h2>
      <swiper :options="swiperOptions" ref="mySwiper">
        <swiper-slide v-for="(service, index) in services" :key="index">
          <div class="service">
            <div class="service-image" :style="{'background-image': `url(${service.image})`}"></div>
            <div class="service-content">
              <h3>{{ service.title }}</h3>
              <p>{{ service.description }}</p>
            </div>
          </div>
        </swiper-slide>
        <div class="swiper-button-next" slot="button-next"></div>
        <div class="swiper-button-prev" slot="button-prev"></div>
      </swiper>
    </div>
  </template>
  
  <script>
  import 'swiper/css/swiper.css'; // Import Swiper styles
  import { Swiper, SwiperSlide } from 'vue-awesome-swiper';
  
  export default {
    name: 'OurServices',
    components: {
      Swiper,
      SwiperSlide,
    },
    data() {
      return {
        swiperOptions: {
          navigation: {
            nextEl: '.swiper-button-next',
            prevEl: '.swiper-button-prev',
          },
        },
        services: [
          {
            title: 'Service 1',
            description: 'Description for Service 1',
            image: '@/assets/images/service1.jpg',
          },
          {
            title: 'Service 2',
            description: 'Description for Service 2',
            image: '@/assets/images/service2.jpg',
          },
          {
            title: 'Service 3',
            description: 'Description for Service 3',
            image: '@/assets/images/service3.jpg',
          },
        ],
      };
    },
  };
  </script>
  
  <style scoped>
  /* Add CSS styles for your Our Services component here */
  .our-services {
    padding: 50px;
    background-color: rgba(0, 0, 255, 0.2); /* Washed-out blue background */
  }
  
  .large-title {
    font-size: 36px;
    text-align: center;
  }
  
  .service {
    display: flex;
    align-items: center;
    padding: 20px;
  }
  
  .service-image {
    flex: 1;
    background-size: cover;
    background-position: center;
    height: 300px;
  }
  
  .service-content {
    flex: 1;
    padding: 20px;
    background-color: rgba(255, 255, 255, 0.9); /* Semi-transparent white background */
    text-align: center;
  }
  
  .service h3 {
    font-size: 24px;
  }
  
  .service p {
    font-size: 18px;
  }
  
  /* Swiper navigation buttons */
  .swiper-button-next,
  .swiper-button-prev {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 40px;
    height: 40px;
    background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent black background */
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
    z-index: 10;
    color: #fff;
    font-size: 24px;
  }
  
  .swiper-button-next {
    right: 20px;
  }
  
  .swiper-button-prev {
    left: 20px;
  }
  </style>   -->