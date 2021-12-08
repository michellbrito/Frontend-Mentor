<template>
  <div class="card">
    <div class="cardHeader"></div>

    <h3 class="title">Order Summary</h3>

    <p class="description">
      You can now listen to millions of songs, audiobooks, and podcasts on any
      device anywhere you like!
    </p>

    <div class="planBtn">
      <div class="musicIcon"></div>
      <div class="plan">
        <p class="type">Annual Plan</p>
        <p class="price">$59.99/year</p>
      </div>
      <p class="change">Change</p>
    </div>

    <div class="payBtn"><p>Proceed to Payment</p></div>

    <p class="cancel">Cancel Order</p>
  </div>
</template>

<script>
export default {
  name: "OrderSummary",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.card {
  background-color: white;
  height: 697px;
  width: 450px;
  background-color: #ffffff;
  box-shadow: 0px 40px 40px -20px rgba(13, 48, 189, 0.151826);
  border-radius: 20px;
  text-align: center;
}

.cardHeader {
  width: 100%;
  height: 220px;
  background-color: #382ae1;
  background-image: url("../assets/images/illustration-hero.svg");
  background-size: contain;
  background-repeat: no-repeat;
  border-radius: 20px 20px 0px 0px;
  margin-bottom: 45px;
}

.title {
  font-style: normal;
  font-weight: 900;
  font-size: 28px;
  line-height: 37px;
  color: #1f2e55;
}

.description {
  width: 354px;
  height: 78px;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 26px;
  text-align: center;
  color: #717fa6;
  margin-bottom: 20px;
  margin-left: 48px;
}

.planBtn {
  width: 354px;
  height: 98px;
  background: #f7f9ff;
  border-radius: 11px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-left: 48px;
}

.plan {
  flex-grow: 1;
  height: 48px;
  width: 92px;
}

.change {
  flex-grow: 1;
  height: 19px;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 19px;
  text-decoration-line: underline;
  color: #382ae1;
}

.change:hover {
  cursor: pointer;
  text-decoration: none;
  color: #766cf1;
}

.type {
  margin-bottom: 6px;
  margin-top: 0;
  font-style: normal;
  font-weight: 900;
  font-size: 14px;
  line-height: 19px;
  color: #1f2e55;
}

.price {
  margin: 0;
  height: 19px;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 19px;
  color: #717fa6;
}

.musicIcon {
  width: 48px;
  height: 48px;
  background-image: url("../assets/images/icon-music.svg");
  background-size: contain;
  background-repeat: no-repeat;
  margin-left: 24px;
}

.payBtn {
  margin-top: 32px;
  margin-bottom: 32px;
  margin-left: 48px;
  width: 354px;
  height: 50px;
  background: #382ae1;
  box-shadow: 0px 20px 20px rgba(56, 42, 225, 0.190291);
  border-radius: 11px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.payBtn:hover {
  cursor: pointer;
  background: #766cf1;
}

.payBtn p {
  height: 20px;
  font-style: normal;
  font-weight: 900;
  font-size: 15px;
  line-height: 20px;
  color: #ffffff;
}

.cancel {
  height: 20px;
  font-style: normal;
  font-weight: 900;
  font-size: 15px;
  line-height: 20px;
  color: #717fa6;
}

.cancel:hover {
  color: #1f2e55;
  cursor: pointer;
}
</style>
