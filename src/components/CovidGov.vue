<template>
  <v-app>
    <!--header-->
    <v-header class="grid">
      <div class="header__top">
        <v-container class="grid wide">
          <div style="padding-left: 140px" class="d-flex justify-space-between">
            <div>Thứ bảy, 22/7/2023</div>
            <div class="d-flex">
              <div>
                <v-icon>mdi-magnify</v-icon>
              </div>
              <div class="ml-5">
                <a class="header__top-hotline">Đường dây nóng: 19009095</a>
              </div>
            </div>
          </div>
        </v-container>
      </div>

      <div class="header__middle">
        <v-container class="grid wide">
          <div class="d-flex">
            <h1 class="header__logo">
              <v-img src="../assets/img/logo-header.png" alt="logo" />
            </h1>
            <p class="header-slg">CỔNG THÔNG TIN CỦA BỘ Y TẾ VỀ ĐẠI DỊCH COVID-19 </p>
          </div>
        </v-container>
      </div>

      <div class="header__bot">
        <v-container class="grid wide">
          <div class="header__nav">
            <ul >
              <li>
                <a style="font-size: 11px" class="nav-link">
                  <v-icon>mdi-home</v-icon>
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Bản tin Covid-19
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Chỉ đạo chống dịch
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Dự phòng - Điều trị
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Vaccine - Tiêm chủng
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Hoạt động địa phương
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Hướng dẫn
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Video
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Tin tức
                </a>
              </li>
              <li>
                <a title="Bản tin Covid-19" class="nav-link">
                  Tình hình thế giới
                </a>
              </li>
            </ul>
          </div>
        </v-container>
      </div>
    </v-header>

    <!--content-->
    <v-container class="grid wide mt-lg-10">
      <v-row class="grid wide">
        <div class="home__statistical-nav">
          <ul class="d-flex align-content-center">
            <li>
              <a id="tabvi" title="" class="active">Việt Nam</a>
            </li>
            <li>
              <a id="taben" title="" class="non-active">Thế giới</a>
            </li>
          </ul>
        </div>
      </v-row>

      <v-row>
        <v-col lg="4">
          <div class="item" style="text-align: center; background-color: #fde8e9; padding: 8px">
            <p class="text">SỐ CA NHIỄM</p>
            <p class="value">11.608.697</p>
            <p class="note">24 giờ qua<span> +1.043</span>
            </p>
          </div>
        </v-col>
        <v-col lg="4">
          <div class="item" style="text-align: center; background-color: #e9f6ec; padding: 8px">
            <p class="text">KHỎI</p>
            <p style="padding-bottom: 21px" class="value">10.637.138</p>
          </div>
        </v-col>
        <v-col lg="4">
          <div class="item" style="text-align: center; background-color: #F0EFF4; padding: 8px">
            <p class="text">TỬ VONG</p>
            <p style="padding-bottom: 21px" class="value">43.206</p>
          </div>
        </v-col>
      </v-row>

      <v-row class="pb-10">
        <v-col lg="7">
          <div>
            <v-img style="margin-bottom: 12px" src="../assets/img/img-body-1.jpg" alt="logo" />
            <p class="text-below-img">
              Thống nhất chuyển COVID-19 từ bệnh truyền nhiễm nhóm A xuống nhóm B
            </p>
            <p class="sub-text-below-img">
              Ban Chỉ đạo Quốc gia phòng, chống dịch COVID-19 thống nhất chuyển bệnh COVID-19 từ bệnh truyền nhiễm nhóm A sang bệnh truyền nhiễm nhóm B, đồng thời ban hành hướng dẫn việc áp dụng các biện pháp phòng, chống dịch COVID-19 phù hợp với dịch bệnh nhóm B.
            </p>
          </div>
        </v-col>
        <v-col lg="5">
          <div>
            <h2 class="title-section">
              <div class="home__statistical-nav">
                <ul class="d-flex align-content-center">
                  <li>
                    <a title="" class="active">Diễn biến dịch</a>
                  </li>
                </ul>
              </div>
            </h2>
            <div style="max-height: 67vh; overflow-y: auto">
              <p>
                Các tỉnh, thành phố ghi nhận ca bệnh như sau:  Hà Nội (191), Bắc Ninh (74), Nghệ An (42), Hồ Chí Minh (35), Quảng Ninh (34), Lào Cai (31), Yên Bái (28), Quảng Bình (24), Ninh Bình (24), Hà Nam (23), Hải Dương (21), Phú Thọ (20), Vĩnh Phúc (17), Thái Nguyên (14), Cao Bằng (14), Tuyên Quang (14), Sơn La (14), Thái Bình (13), Bắc Giang (12), Bắc Kạn (12), Quảng Trị (11), Thanh Hóa (11), Nam Định (10), Đà Nẵng (10), Hưng Yên (10), Hòa Bình (9), Quảng Ngãi (8), Lạng Sơn (8), Hà Tĩnh (7), Hải Phòng (7), Điện Biên (4), Khánh Hòa (4), Lâm Đồng (4), Bình Dương (3), Đồng Tháp (3), Lai Châu (2), Gia Lai (2), Tây Ninh (2), Bình Thuận (1), Bình Phước (1), Đồng Nai (1), Bà Rịa - Vũng Tàu (1), Bến Tre (1).
              </p>
              <p>
                Các tỉnh, thành phố ghi nhận ca bệnh như sau:  Hà Nội (191), Bắc Ninh (74), Nghệ An (42), Hồ Chí Minh (35), Quảng Ninh (34), Lào Cai (31), Yên Bái (28), Quảng Bình (24), Ninh Bình (24), Hà Nam (23), Hải Dương (21), Phú Thọ (20), Vĩnh Phúc (17), Thái Nguyên (14), Cao Bằng (14), Tuyên Quang (14), Sơn La (14), Thái Bình (13), Bắc Giang (12), Bắc Kạn (12), Quảng Trị (11), Thanh Hóa (11), Nam Định (10), Đà Nẵng (10), Hưng Yên (10), Hòa Bình (9), Quảng Ngãi (8), Lạng Sơn (8), Hà Tĩnh (7), Hải Phòng (7), Điện Biên (4), Khánh Hòa (4), Lâm Đồng (4), Bình Dương (3), Đồng Tháp (3), Lai Châu (2), Gia Lai (2), Tây Ninh (2), Bình Thuận (1), Bình Phước (1), Đồng Nai (1), Bà Rịa - Vũng Tàu (1), Bến Tre (1).
              </p>
              <p>
                Các tỉnh, thành phố ghi nhận ca bệnh như sau:  Hà Nội (191), Bắc Ninh (74), Nghệ An (42), Hồ Chí Minh (35), Quảng Ninh (34), Lào Cai (31), Yên Bái (28), Quảng Bình (24), Ninh Bình (24), Hà Nam (23), Hải Dương (21), Phú Thọ (20), Vĩnh Phúc (17), Thái Nguyên (14), Cao Bằng (14), Tuyên Quang (14), Sơn La (14), Thái Bình (13), Bắc Giang (12), Bắc Kạn (12), Quảng Trị (11), Thanh Hóa (11), Nam Định (10), Đà Nẵng (10), Hưng Yên (10), Hòa Bình (9), Quảng Ngãi (8), Lạng Sơn (8), Hà Tĩnh (7), Hải Phòng (7), Điện Biên (4), Khánh Hòa (4), Lâm Đồng (4), Bình Dương (3), Đồng Tháp (3), Lai Châu (2), Gia Lai (2), Tây Ninh (2), Bình Thuận (1), Bình Phước (1), Đồng Nai (1), Bà Rịa - Vũng Tàu (1), Bến Tre (1).
              </p>
              <p>
                Các tỉnh, thành phố ghi nhận ca bệnh như sau:  Hà Nội (191), Bắc Ninh (74), Nghệ An (42), Hồ Chí Minh (35), Quảng Ninh (34), Lào Cai (31), Yên Bái (28), Quảng Bình (24), Ninh Bình (24), Hà Nam (23), Hải Dương (21), Phú Thọ (20), Vĩnh Phúc (17), Thái Nguyên (14), Cao Bằng (14), Tuyên Quang (14), Sơn La (14), Thái Bình (13), Bắc Giang (12), Bắc Kạn (12), Quảng Trị (11), Thanh Hóa (11), Nam Định (10), Đà Nẵng (10), Hưng Yên (10), Hòa Bình (9), Quảng Ngãi (8), Lạng Sơn (8), Hà Tĩnh (7), Hải Phòng (7), Điện Biên (4), Khánh Hòa (4), Lâm Đồng (4), Bình Dương (3), Đồng Tháp (3), Lai Châu (2), Gia Lai (2), Tây Ninh (2), Bình Thuận (1), Bình Phước (1), Đồng Nai (1), Bà Rịa - Vũng Tàu (1), Bến Tre (1).
              </p>
            </div>
          </div>
        </v-col>
      </v-row>

      <v-row style="border-top: 1px solid; padding-top: 30px">
        <v-col style="border-right: 1px solid #e5e5e5" lg="6">
          <div class="home__statistical-nav">
            <ul class="d-flex align-content-center">
              <li>
                <a title="" class="active">Chỉ đạo chống dịch</a>
              </li>
            </ul>
          </div>
          <v-row>
            <v-col lg="5">
              <v-img src="../assets/img/img-body-1.jpg"></v-img>
            </v-col>
            <v-col lg="7">
              <p class="text-below-img-2">
                Thống nhất chuyển COVID-19 từ bệnh truyền nhiễm nhóm A xuống nhóm B
              </p>
              <p class="sub-text-below-img-2">
                Ban Chỉ đạo Quốc gia phòng, chống dịch COVID-19 thống nhất chuyển...
              </p>
            </v-col>

            <div class="d-flex mt-5 pt-5" style="border-top: 1px solid #e5e5e5">
              <v-col lg="5">
                <v-img src="../assets/img/img-body-1.jpg"></v-img>
              </v-col>
              <v-col lg="7">
                <p class="text-below-img-2">
                  Thống nhất chuyển COVID-19 từ bệnh truyền nhiễm nhóm A xuống nhóm B
                </p>
                <p class="sub-text-below-img-2">
                  Ban Chỉ đạo Quốc gia phòng, chống dịch COVID-19 thống nhất chuyển...
                </p>
              </v-col>
            </div>

            <div class="d-flex mt-5 pt-5" style="border-top: 1px solid #e5e5e5">
              <v-col lg="5">
                <v-img src="../assets/img/img-body-1.jpg"></v-img>
              </v-col>
              <v-col lg="7">
                <p class="text-below-img-2">
                  Thống nhất chuyển COVID-19 từ bệnh truyền nhiễm nhóm A xuống nhóm B
                </p>
                <p class="sub-text-below-img-2">
                  Ban Chỉ đạo Quốc gia phòng, chống dịch COVID-19 thống nhất chuyển...
                </p>
              </v-col>
            </div>
          </v-row>
        </v-col>
        <v-col lg="6">
          <div class="home__statistical-nav">
            <ul class="d-flex align-content-center">
              <li>
                <a title="" class="active">Bản tin Covid-19</a>
              </li>
            </ul>
          </div>
          <v-row>
            <v-col lg="5">
              <v-img src="../assets/img/img-body-1.jpg"></v-img>
            </v-col>
            <v-col lg="7">
              <p class="text-below-img-2">
                Thống nhất chuyển COVID-19 từ bệnh truyền nhiễm nhóm A xuống nhóm B
              </p>
              <p class="sub-text-below-img-2">
                Ban Chỉ đạo Quốc gia phòng, chống dịch COVID-19 thống nhất chuyển...
              </p>
            </v-col>

            <div class="d-flex mt-5 pt-5" style="border-top: 1px solid #e5e5e5">
              <v-col lg="5">
                <v-img src="../assets/img/img-body-1.jpg"></v-img>
              </v-col>
              <v-col lg="7">
                <p class="text-below-img-2">
                  Thống nhất chuyển COVID-19 từ bệnh truyền nhiễm nhóm A xuống nhóm B
                </p>
                <p class="sub-text-below-img-2">
                  Ban Chỉ đạo Quốc gia phòng, chống dịch COVID-19 thống nhất chuyển...
                </p>
              </v-col>
            </div>

            <div class="d-flex mt-5 pt-5" style="border-top: 1px solid #e5e5e5">
              <v-col lg="5">
                <v-img src="../assets/img/img-body-1.jpg"></v-img>
              </v-col>
              <v-col lg="7">
                <p class="text-below-img-2">
                  Thống nhất chuyển COVID-19 từ bệnh truyền nhiễm nhóm A xuống nhóm B
                </p>
                <p class="sub-text-below-img-2">
                  Ban Chỉ đạo Quốc gia phòng, chống dịch COVID-19 thống nhất chuyển...
                </p>
              </v-col>
            </div>
          </v-row>
        </v-col>
      </v-row>

      <v-row style="border-top: 1px solid; padding-top: 30px" class="mt-10 grid wide">
        <div class="home__statistical-nav">
          <ul class="d-flex align-content-center">
            <li>
              <a title="" class="active">Dự phòng - Điều trị</a>
            </li>
          </ul>
        </div>
      </v-row>
      <v-row>
        <v-col lg="6">
          <div>
            <v-img style="margin-bottom: 12px" src="../assets/img/img-body-2.png" alt="logo" />
            <p class="text-below-img">
              Những đối tượng tiêm chủng vaccine bắt buộc
            </p>
            <p class="sub-text-below-img">
              Cục Y tế dự phòng - Bộ Y tế vừa có văn bản hướng dẫn xác định nhu cầu, lập kế hoạch cung ứng các vaccine trong tiêm chủng mở rộng.
            </p>
          </div>
        </v-col>
        <v-col lg="6">
          <v-row>
            <v-col lg="5">
              <v-img src="../assets/img/img-body-1.jpg"></v-img>
            </v-col>
            <v-col lg="7">
              <p style="font-size: 14px" class="text-below-img-2">
                Hà Nội: Yêu cầu bảo trì hệ thống oxy sẵn sàng điều trị ca bệnh COVID-19 nếu có
              </p>
            </v-col>

            <div class="d-flex mt-5 pt-5" style="border-top: 1px solid #e5e5e5">
              <v-col lg="5">
                <v-img src="../assets/img/img-body-1.jpg"></v-img>
              </v-col>
              <v-col lg="7">
                <p style="font-size: 14px" class="text-below-img-2">
                  Ca COVID-19 tiếp tục tăng, cần tuân thủ 2K và đẩy nhanh tiêm vaccine trong phòng chống dịch
                </p>
              </v-col>
            </div>

            <div class="d-flex mt-5 pt-5" style="border-top: 1px solid #e5e5e5">
              <v-col lg="5">
                <v-img src="../assets/img/img-body-1.jpg"></v-img>
              </v-col>
              <v-col lg="7">
                <p style="font-size: 14px" class="text-below-img-2">
                  Thứ trưởng Nguyễn Thị Liên Hương: Không lơ là phòng chống dịch COVID-19, khám chữa bệnh dịp Tết
                </p>
              </v-col>
            </div>
          </v-row>
        </v-col>
      </v-row>

      <v-row style="border-top: 1px solid; padding-top: 30px" class="mt-10 grid wide">
        <div class="home__statistical-nav">
          <ul class="d-flex align-content-center">
            <li>
              <a title="" class="active">Tin tức</a>
            </li>
          </ul>
        </div>
      </v-row>
      <v-row>
        <v-col lg="3">
          <v-img src="../assets/img/img-body-3.jpg"></v-img>
          <div class="text-below-img-3">
            "COVID-19 không còn là tình trạng y tế khẩn cấp nhưng không có nghĩa chúng ta sẽ bỏ rơi..."
          </div>
        </v-col>
        <v-col lg="3">
          <v-img src="../assets/img/img-body-3.jpg"></v-img>
          <div class="text-below-img-3">
            "COVID-19 không còn là tình trạng y tế khẩn cấp nhưng không có nghĩa chúng ta sẽ bỏ rơi..."
          </div>
        </v-col>
        <v-col lg="3">
          <v-img src="../assets/img/img-body-3.jpg"></v-img>
          <div class="text-below-img-3">
            "COVID-19 không còn là tình trạng y tế khẩn cấp nhưng không có nghĩa chúng ta sẽ bỏ rơi..."
          </div>
        </v-col>
        <v-col lg="3">
          <v-img src="../assets/img/img-body-3.jpg"></v-img>
          <div class="text-below-img-3">
            "COVID-19 không còn là tình trạng y tế khẩn cấp nhưng không có nghĩa chúng ta sẽ bỏ rơi..."
          </div>
        </v-col>
        <v-col lg="3">
          <v-img src="../assets/img/img-body-3.jpg"></v-img>
          <div class="text-below-img-3">
            "COVID-19 không còn là tình trạng y tế khẩn cấp nhưng không có nghĩa chúng ta sẽ bỏ rơi..."
          </div>
        </v-col>
      </v-row>

      <v-row style="border-top: 1px solid; padding-top: 30px" class="mt-10 grid wide">
        <div class="home__statistical-nav">
          <ul class="d-flex align-content-center">
            <li>
              <a title="" class="active">Liên kết</a>
            </li>
          </ul>
        </div>
      </v-row>
      <v-row>
        <v-col lg="3">
          <v-img class="link" src="../assets/img/link-1.jpg" />
        </v-col>
        <v-col lg="3">
          <v-img class="link" src="../assets/img/link-2.jpg" />
        </v-col>
        <v-col lg="3">
          <v-img class="link" src="../assets/img/link-3.png" />
        </v-col>
        <v-col lg="3">
          <v-img class="link" src="../assets/img/link-4.png" />
        </v-col>
      </v-row>
    </v-container>

    <!--footer-->
    <div style="margin-top: 100px; background-color: #2e3192">
      <v-container class="grid wide">
        <div class="d-flex">
          <h1 class="header__logo">
            <v-img src="../assets/img/logo-header.png" alt="logo" />
          </h1>
          <div class="footer__name">
            <p class="text">QUẢN LÝ NỘI DUNG: BÁO SỨC KHỎE VÀ ĐỜI SỐNG CƠ QUAN NGÔN LUẬN CỦA BỘ Y TẾ</p>
            <p class="text">Địa chỉ: Số 138A Giảng Võ - Quận Ba Đình - TP. Hà Nội</p>
            <p class="text">Đường dây nóng: 19009095</p>
            <p class="text">Email: covid19@suckhoedoisong.vn</p>
          </div>
        </div>
      </v-container>
    </div>
  </v-app>
</template>

<script>
export default {
  name: "CovidGov"
}
</script>

<style scoped>
.grid {
  width: 100%;
  display: block;
  padding: 0;
}

.grid.wide {
  max-width: 1110px;
  margin: 0 auto;
}

.header__top {
  padding: 4px 0;
}

.header__top-hotline {
  background: #ed1c24;
  border-radius: 10px;
  padding: 3px 14px;
  font-family: Roboto;
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 22px;
  display: flex;
  align-items: center;
  letter-spacing: -.005em;
  color: #fff;
}

.header__middle {
  background-image: url("../assets/img/bg-header.png");
  background-size: cover;
}

.header__logo {
  width: 121px;
  height: 121px;
  display: flex;
  position: relative;
  top: -38px;
}

.header-slg {
  display: block;
  flex: 1;
  font-weight: 600;
  font-size: 20px;
  line-height: 22px;
  letter-spacing: -.005em;
  color: #fff;
  margin-left: 20px;
  font-family: 'Merriweather';
  /*position: relative;*/
  /*bottom: -68px;*/
  align-self: flex-end;
  margin-bottom: 35px;
}

.header__bot {
  background: #2e3192;
}

.header__nav ul {
  display: flex;
  align-items: center;
  list-style: none;
}

.header__nav ul li .nav-link {
  display: block;
  padding: 0 6px 6px;
  border-bottom: 3px solid transparent;
  font-family: 'Merriweather';
  font-style: normal;
  font-size: 14px;
  line-height: 25px;
  color: #fff;
}

/* content */
ul {
  list-style: none;
}

.home__statistical-nav {
  margin-bottom: 9.5px;
}

.home__statistical-nav ul li a.active:before {
  content: "";
  width: 3px;
  height: 24px;
  background: #2E3192;
  left: 0;
  top: 2px;
  position: absolute;
}

.home__statistical-nav ul li a.active:after {
  content: "";
  width: 3px;
  height: 24px;
  background: #ED1C24;
  left: 3px;
  top: 2px;
  position: absolute;
}

.home__statistical-nav ul li a.active {
  font-size: 22px;
  line-height: 130%;
  color: #2E3192;
  font-weight: 700;
  font-family: 'Merriweather';
  padding-left: 16px;
  position: relative;
}

.home__statistical-nav ul li a {
  font-weight: bold;
  font-size: 18px;
  line-height: 130%;
  color: rgba(46, 49, 146, 0.6);
  display: block;
  position: relative;
  font-family: 'Merriweather';
}

.home__statistical-nav ul li a.non-active:before {
  content: "/";
  height: 24px;
  left: 0;
  font-size: 28px;
  margin: 0 16px;
  position: relative;
  top: 2px;
  color: #C0C1DE;
}

/**/
.text {
  font-size: 13px;
  line-height: 160%;
  text-align: center;
  color: #333333;
  font-family: 'Merriweather';
  font-weight: 600;
}

.value {
  font-weight: 800;
  font-size: 18px;
  line-height: 22px;
  color: #ED1C24;
  font-family: 'Merriweather';
}

.note {
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 160%;
  color: #666666;
}

/* body img */
.text-below-img {
  font-size: 24px;
  line-height: 130%;
  letter-spacing: .02em;
  color: #333;
  margin-bottom: 12px;
  font-family: 'Merriweather';
  font-weight: 600;
  display: block;
}

.sub-text-below-img {
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 130%;
  color: #444;
}

.title-section {
  border-bottom: 1px solid #f0eff4;
  padding-bottom: 3px;
}

/**/
.text-below-img-2 {
  font-weight: 600;
  font-size: 20px;
  line-height: 130%;
  letter-spacing: .02em;
  color: #333;
  font-family: 'Merriweather';
  margin-bottom: 10px;
  display: block;
}

.sub-text-below-img-2 {
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 140%;
  color: #444;
}

/**/
.text-below-img-3 {
  display: block;
  font-weight: 600;
  font-size: 16px;
  line-height: 160%;
  letter-spacing: .02em;
  color: #333;
  font-family: 'Merriweather';
  padding: 10px 0;
}

/**/
.link {
  width: 100%;
  max-width: 100%;
  display: block;
}

/*footer*/
.footer__name {
  font-family: 'Merriweather';
  font-style: normal;
  font-weight: 700;
  font-size: 20px;
  line-height: 160%;
  letter-spacing: -.005em;
  color: #fff;
  margin-left: 14px;
  flex: 1;
}

.footer__name .text {
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 130%;
  text-align: left;
  color: #fff;
}

.footer__name .text:first-child {
  margin-top: 10px;
  font-weight: 600;
}
</style>
