<template>
  <div class="container-fluid" id="continer">
    <div class="row">
      <div class="col-sm-12">
        <div class="d-flex flex-row-reverse pt-2 mx-5">
          <div class="flex_item">
            <div class="dropdown">
              <img
                src="../../assets/arrow-b.png"
                width="10"
                height="10"
                alt=""
              />
              <a class="dropbtn px-1">موبایل و تبلت</a>
              <div class="dropdown-content">
                <a class="mt-2" href="#">Link 1</a>
                <a href="#">Link 2</a>
                <a class="mb-2" href="#">Link 3</a>
              </div>
            </div>
          </div>
          <div class="flex_item">
            <div class="dropdown">
              <img
                src="../../assets/arrow-b.png"
                width="10"
                height="10"
                alt=""
              />
              <a class="dropbtn px-1">لب تاپ و کامپیوتر</a>
              <div class="dropdown-content">
                <a class="mt-2" href="#">Link 1</a>
                <a href="#">Link 2</a>
                <a class="mb-2" href="#">Link 3</a>
              </div>
            </div>
          </div>
          <div class="flex_item">
            <div class="dropdown">
              <img
                src="../../assets/arrow-b.png"
                width="10"
                height="10"
                alt=""
              />
              <a class="dropbtn px-1">گجت های هوشمند</a>
              <div class="dropdown-content">
                <a class="mt-2" href="#">Link 1</a>
                <a href="#">Link 2</a>
                <a class="mb-2" href="#">Link 3</a>
              </div>
            </div>
          </div>
          <div class="flex_item">
            <div class="dropdown">
              <img
                src="../../assets/arrow-b.png"
                width="10"
                height="10"
                alt=""
              />
              <a class="dropbtn px-1">لوازم صوتی و تصویری</a>
              <div class="dropdown-content">
                <a class="mt-2" href="#">Link 1</a>
                <a href="#">Link 2</a>
                <a class="mb-2" href="#">Link 3</a>
              </div>
            </div>
          </div>
          <div class="flex_item">
            <div class="dropdown">
              <img
                src="../../assets/arrow-b.png"
                width="10"
                height="10"
                alt=""
              />
              <a class="dropbtn px-1">ماشین های اداری</a>
              <div class="dropdown-content">
                <a class="mt-2" href="#">Link 1</a>
                <a href="#">Link 2</a>
                <a class="mb-2" href="#">Link 3</a>
              </div>
            </div>
          </div>
          <div class="flex_item">
            <div class="dropdown">
              <img
                src="../../assets/arrow-b.png"
                width="10"
                height="10"
                alt=""
              />
              <a class="dropbtn px-1">کنسول بازی</a>
              <div class="dropdown-content">
                <a class="mt-2" href="#">Link 1</a>
                <a href="#">Link 2</a>
                <a class="mb-2" href="#">Link 3</a>
              </div>
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

<style lang="scss" scoped>
.flex_item {
  margin: 0 25px;
}
.dropbtn {
  font-size: 16px;
  border: none;
  padding-bottom: 25px;
}

.dropdown {
  position: relative;
  display: inline-block;
  text-align: center;
  a {
    color: #000;
  }
}

.dropdown-content {
  text-align: right;
  display: none;
  position: absolute;
  background-color: #ffffff;
  min-width: 200px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.1);
  z-index: 1;
  border-radius: 15px;
  border: 1px solid rgb(230, 230, 230);
  right: -45px;
  top: 45px;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  font-size: 15px;
}

.dropdown-content a:hover {
  background-color: rgba(235, 235, 235, 0.5);
  border-radius: 15px;
  margin: 0 5px;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>
