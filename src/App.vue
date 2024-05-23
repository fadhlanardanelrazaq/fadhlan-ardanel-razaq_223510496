<template>
  <div id="app">
    <Navbar />
    <Carousel />
    <div class="container mt-5">
      <div class="row">
        <Card
          title="Nike Pegasus 41"
          description="Men's Road Running Shoes."
          imgUrl="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/927d3fef-0657-4b82-8b3a-b34f07ffdd28/pegasus-41-road-running-shoes-RZm89S.png"
        />
        <Card
          title="Nike Pegasus 41"
          description="Women's Road Running Shoes"
          imgUrl="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/870add6a-ba05-4546-80cc-f0e3d0268848/pegasus-41-road-running-shoes-SKDkNs.png"
        />
        <Card
          title="Nike Pegasus 41"
          description="Men's Road Running Shoes"
          imgUrl="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/8fb34fe2-cc91-4865-9fa6-79b3b26b8ac7/pegasus-41-road-running-shoes-RZm89S.png"
        />
      </div>
      <h2 class="text-center my-4">Additional Information</h2>
      <div class="row">
        <InfoCard
          title="Men's T-Shirt"
          description="Nike Sportswear"
          imgUrl="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/e08e8cb7-4009-48de-bff6-32742ff06ca7/sportswear-t-shirt-MV5kVX.png" 
        />
        <InfoCard
          title="Nike Sportswear Club"
          description="Women's Sleeveless Cropped Top"
          imgUrl="https://static.nike.com/a/images/t_PDP_1728_v1/f_auto,q_auto:eco/384585cc-bd9c-449a-b1c1-22099c0d6205/sportswear-club-sleeveless-cropped-top-GqxWKs.png" 
        />
        <InfoCard
          title="Nike Sportswear"
          description="Men's Max90 T-Shirt"
          imgUrl="https://static.nike.com/a/images/t_PDP_1728_v1/f_auto,q_auto:eco/12349013-d319-428b-aa4c-0d8202a50570/sportswear-max90-t-shirt-trzSnl.png" 
        />
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Carousel from './components/Carousel.vue';
import Card from './components/Card.vue';
import InfoCard from './components/InfoCard.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Carousel,
    Card,
    InfoCard,
    Footer
  }
}
</script>

<style>
body {
  font-family: 'Arial', sans-serif;
  background-color: #f8f9fa;
  color: #333;
}

h2 {
  color: #007bff;
}

.container {
  padding: 0 15px;
}

.text-center {
  text-align: center;
}

.mb-4 {
  margin-bottom: 1.5rem;
}

.mt-5 {
  margin-top: 3rem;
}

.mt-4 {
  margin-top: 1.5rem;
}

.my-4 {
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
}

.row {
  display: flex;
  flex-wrap: wrap;
}

.card,
.info-card {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover,
.info-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

hr {
  border: none;
  border-top: 2px solid #ddd;
}
</style>