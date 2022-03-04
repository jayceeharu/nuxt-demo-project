<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-4">
        <div class="real-estate-img">
          <img
            class="sm-hidden relative-img"
            src="https://www.temponw.com/storage/tps/192810003/84c4a2a17b0e02d484bb7cd5ccad789f.jpg"
            style="height: 347px; width: 260.511px"
          />
        </div>
      </div>

      <div class="col-md-8">
        <!-- REAL ESTATE TITLE -->
        <div class="row-between">
          <h1 class="real-estate-name">HOTEL GLOBAL VIEW Hachinohe 102</h1>
        </div>
        <hr />
        <!-- END REAL ESTATE TITLE -->

        <!-- ACCESS -->
        <div class="access-container">
          <div class="access-title">
            <h4>Access</h4>
          </div>
          <div class="access-details">
            <div class="access-address">
              <p>7 Jusannichimachi, Hachinohe City, Aomori Prefecture</p>
              <p class="address-link">
                <a
                  href="https://www.google.co.jp/maps/place/青森県八戸市大字十三日町7"
                  target="_blank"
                  rel="noopener noreferrer"
                  ><font style="vertical-align: inherit"
                    ><font style="vertical-align: inherit"
                      >GoogleMap</font
                    ></font
                  ><img
                    src="https://www.temponw.com/assets/consumer/img/open_link@2x.png"
                /></a>
              </p>
            </div>
          </div>
        </div>
        <!-- END OF ACCESS -->

        <div class="header-title">
          <div><h4>Rent, initial costs, etc.</h4></div>
        </div>

        <div class="container-div-father">
          <div class="container-div inline-container">
            <span>RENT</span>
            <span class="price-type"
              >Monthly fee 14.59 million yen including tax</span
            >
          </div>

          <div class="container-div">
            <div class="container-div inline-container">
              <span>Management fee / common service fee, etc. </span>
              <span>――――/ none</span>
            </div>

            <div class="container-div inline-container">
              <span>Right money / key money</span>
              <span>――――/ none</span>
            </div>
          </div>

          <div class="container-div">
            <div class="container-div inline-container">
              <span>Security deposit / security deposit</span>
              <span>-/ 3.00 months</span>
            </div>

            <div class="container-div inline-container">
              <span>Depreciation / depreciation</span>
              <span>none / -</span>
            </div>
          </div>
        </div>

        <div class="header-title">
          <div><h4>Property information</h4></div>
        </div>

        <div class="container-div-father">
          <div class="container-div">
            <div class="container-div inline-container">
              <span>Property No</span>
              <span>00000000000192810003</span>
            </div>

            <div class="container-div inline-container">
              <span>Property type</span>
              <span>Rental stores (partial)</span>
            </div>
          </div>

          <div class="container-div">
            <div class="container-div inline-container">
              <span>Building structure</span>
              <span>
                Steel-framed reinforced concrete structure (SRC structure) / 9
                floors above ground and 2 floors below ground
              </span>
            </div>

            <div class="container-div inline-container">
              <span>Floor / room number</span>
              <span> Room 102 on the 1st floor</span>
            </div>
          </div>

          <div class="container-div">
            <div class="container-div inline-container">
              <span>area</span>
              <span> 48.71㎡</span>
            </div>

            <div class="container-div inline-container">
              <span>Number of tsubo</span>
              <span> 14.73 tsubo</span>
            </div>
          </div>

          <div class="container-div">
            <div class="container-div inline-container">
              <span>Construction date</span>
              <span> November 1980</span>
            </div>

            <div class="container-div inline-container">
              <span>parking</span>
              <span> Nothing</span>
            </div>
          </div>

          <div class="container-div">
            <div class="container-div inline-container">
              <span>type of contract</span>
              <span> Ordinary rented house</span>
            </div>

            <div class="container-div inline-container">
              <span> Contract period</span>
              <span>2 years</span>
            </div>
          </div>

          <div class="container-div">
            <div class="container-div inline-container">
              <span>Current situation</span>
              <span>Sky</span>
            </div>

            <div class="container-div inline-container">
              <span> delivery</span>
              <span> ――――</span>
            </div>
          </div>

          <div class="container-div">
            <div class="container-div inline-container">
              <span>Renewal fee</span>
              <span> none</span>
            </div>

            <div class="container-div inline-container">
              <span> Feature transfer fee</span>
              <span> ――――</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  height: 100vh;
}
.row {
  margin: 50px;
}

.hr {
  background-color: red;
}
.access-title {
  margin-top: 50px;
}
.access-address {
  display: flex;
  align-items: center;
  margin-bottom: 18px;
}
.address-link {
  margin-left: 8px;
}
.access-details {
  margin-top: 20px;
  background: #f5f5f5;
  padding: 20px;
  margin-bottom: 40px;
}

.header-title {
  padding-bottom: 20px;
}
.container-div-father {
  margin-bottom: 20px;
}
.container-div-father > div {
  border-top: 1px solid #cccccc;
}

.inline-container {
  display: flex;
  align-items: center;
  height: auto;
  min-height: 30px;
}

.inline-container > span:nth-child(1) {
  width: 150px;
  background-color: #f5f5f5;
}
.inline-container > span:nth-child(2) {
  width: 240px;
}
.container-div-father .container-div.inline-container .price-type {
  width: 630px;
  font-size: 16px;
  font-weight: 600;
  margin-left: 8px;
}
.container-div {
  display: flex;
  align-items: stretch;
  height: auto;
}
.container-div-father span {
  display: flex;
  align-items: center;
  font-size: 14px;
  height: 100%;
}
</style>
