<template>
    <div>
        <div class="container">
  <div class="row">
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="col">col</div>
  </div>
  <div class="row">
    <div class="col-8">col-8</div>
    <div class="col-4">col-4</div>
  </div>
</div>
        <!-- ======= Nav ======= -->
        <header id="header" class="fixed-top">
            <div class="container d-flex align-items-center">

                <h1 class="logo mr-auto"></h1>
                <!-- Uncomment below if you prefer to use an image logo -->
                <!-- <a href="index.html" class="logo mr-auto"><img src="assets/img/logo.png" alt="" class="img-fluid"></a>-->

                <nav class="nav-menu d-none d-lg-block">
                    <ul>
                        <li class="active"><a href="#feature">自動化特點</a></li>
                        <li><a href="#subsidy">政府補助</a></li>
                        <li><a href="#programme">整合方案</a></li>
                        <li><a href="#application">申請服務</a></li>
                        <li><a href="#about">關於</a></li>
                    </ul>
                </nav>

            </div>
        </header>

        <!-- ======= Section-Top ======= -->
        <section id="section-top" class="d-flex align-items-center">
            <div class="container position-relative" data-aos="fade-up" data-aos-delay="500">
                <h1>000000</h1>
                <h2></h2>
            </div>
        </section>

        <!-- ======= Section-Top ======= -->
        <section id="section-top" class="d-flex align-items-center">
            <div class="container position-relative" data-aos="fade-up" data-aos-delay="500">
                <h1>000000</h1>
                <h2></h2>
            </div>
        </section>

        <main id="main">
            <!-- ======= Feature ======= -->
            <section id="feature" class="why-us d-flex" >  
                <div class="container">
                    <div class="section-title mt-2">
                        <h2>自動化特點</h2>
                        <hr class="col-sm-2">
                        <h4>Feature</h4>
                    </div>

                    <div class="col-lg-12" data-aos="fade-up">
                        <div class="box" style="margin-top: 20px">
                            <h1>01</h1>
                            <h4>自主開發智能設備及系統</h4>
                            <p>智能整合系統，一支手機即可完成入住到退房的繁瑣過程，旅客即刻享有全自動化個人空間。</p>
                            </div>
                        </div>

                        <div class="col-lg-12 mt-4 mt-lg-0"  data-aos="fade-up" data-aos-delay="150">
                            <div class="box" style="margin-top: 50px">
                            <h1>02</h1>
                            <h4>系統化管理節省人力成本</h4>
                            <p>PMS大師旅宿管理系統提供業者掌握線上及機台即時訂單、統一房源控管。</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- ======= Subsidy ======= -->
            <section id="subsidy" class="services">
                <div class="container">
                    <div class="section-title mt-2">
                        <h2>政府補助</h2>
                        <hr class="col-4">
                        <h4>Government Subsidy</h4>
                    </div>

                    <div class="row justify-content-md-center">
                        <p class="col-lg-6 col-md-6 mt-4 mt-lg-0 ">觀光局為鼓勵觀光旅館業、旅館業及民宿打造友善、智慧服務空間及提升服務品質，提供國內外旅客優質住宿，新增補助方案。</p>
                    </div>
                </div>
            </section>

            <!-- ======= Programme ======= -->
            <section id="programme" class="section-bg">
                <div class="container">
                    <div class="section-title mt-2">
                        <h2>敦謙整合方案</h2>
                        <hr class="col-sm-2">
                        <h4>Integration Programme</h4>
                    </div>

                    <div class="row justify-content-md-center">
                        <p class="col-lg-4 col-md-6 mt-4 mt-lg-0">秉持公司理念『透過ANTCROSSING資源協助業者邁向智能經營的未來趨勢』，推出整合方案。</p>
                        <p class="col-lg-4 col-md-6 mt-4 mt-lg-0" >購置導入智能機台，並免費提供PMS大師旅宿管理系統，快速將傳統旅店轉型為智能旅店。</p>
                    </div>
                </div>
            </section>

            <!-- ======= Application ======= -->
            <section id="application" class="contact">
                <div class="container">

                    <div class="section-title mt-2">
                        <h2>申請</h2>
                        <hr class="col-sm-2">
                        <h4>Application</h4>
                    </div>

                    <div class="row" >

                        <div class="col-lg-12">
                            <form action="forms/contact.php" method="post" role="form" class="php-email-form">
                                <div class="form-group">
                                    <input type="text" class="form-control" name="name" id="subject" placeholder="姓名" data-rule="" data-msg="請填入姓名。" />
                                    <div class="validate"></div>
                                </div>

                                <div class="form-group">
                                    <input type="text" class="form-control" name="email" id="email" placeholder="Email" data-rule="" data-msg="請填入信箱。" />
                                    <div class="validate"></div>
                                </div>

                                <div class="form-group">
                                    <input type="text" class="form-control" name="phone" id="phone" placeholder="電話" data-rule="minlen:10" data-msg="請填入電話。" />
                                    <div class="validate"></div>
                                </div>

                                <div class="mb-3">
                                    <div class="loading">Loading</div>
                                    <div class="error-message"></div>
                                    <div class="sent-message">Your message has been sent. Thank you!</div>
                                </div>

                                <div class="text-center">
                                    <button type="submit">申請</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </section>

            <!-- ======= About ======= -->
            <section id="about"  style="background-color: #D0D2E5">
                <div class="row">
                    <div class="col-lg-4 col-md-6 mt-4 mt-lg-0 text-center" style="margin-left: 50px">
                        <h2 style="color: #FFFFFF">關於</h2>
                        <hr style="color: #FFFFFF; width: 200px; height: 2px">
                        <h4 style="color: #FFFFFF"> About Us</h4>
                    </div>
                    <div class="col-lg-6 col-md-6 mt-4 mt-lg-0">
                        <p>敦謙DUNQIAN為旅宿市場上智能無人化旅店的先驅，提供智能相關技術、產品、服務與資源，串連並集結各個品牌旅店，帶動欲轉型之業者往智能/無人化旅店的方向前進，共同打造全球智能無人化旅店生態，解決傳統旅宿產業面臨到的問題，並將成為全球市場上最大的一股力量。</p>
                    </div>
                </div>
            </section>
        </main>

       <!-- ======= Footer ======= -->
        <footer id="footer">
            <div class="footer-top">
                <div class="container" style="text-align: right">
                    <p>
                        <strong>敦謙國際智能酒店股份有限公司</strong><br>
                        <strong>Email:</strong> service@dunqian.tw<br>
                        <strong>Tel:</strong> 04 2452 9446<br>
                    </p>
                </div>
            </div>

            <div class="container">
                <div class="copyright">
                    &copy; Copyright <strong><span> © 2020 - Dun-Qian Intelligent Hotel Management Co.,Ltd.</span></strong>
                </div>
            </div>
        </footer>
        <!-- End Footer -->

        <!-- return top -->
        <a href="#" class="back-to-top">
            <i class="icofont-simple-up"></i>
        </a>

       
        <h1>{{ msg }}</h1>
        <h2>Essential Links</h2>
        <ul>
            <li>
                <a
                href="https://vuejs.org"
                target="_blank"
                >
                Core Docs
                </a>
            </li>
            <li>
                <a
                href="https://forum.vuejs.org"
                target="_blank"
                >
                Forum
                </a>
            </li>
            <li>
                <a
                href="https://chat.vuejs.org"
                target="_blank"
                >
                Community Chat
                </a>
            </li>
            <li>
                <a
                href="https://twitter.com/vuejs"
                target="_blank"
                >
                Twitter
                </a>
            </li>
            <br>
            <li>
                <a
                href="http://vuejs-templates.github.io/webpack/"
                target="_blank"
                >
                Docs for This Template
                </a>
            </li>
        </ul>
        <h2>Ecosystem</h2>
        <ul>
            <li>
                <a
                href="http://router.vuejs.org/"
                target="_blank"
                >
                vue-router
                </a>
            </li>
            <li>
                <a
                href="http://vuex.vuejs.org/"
                target="_blank"
                >
                vuex
                </a>
            </li>
            <li>
                <a
                href="http://vue-loader.vuejs.org/"
                target="_blank"
                >
                vue-loader
                </a>
            </li>
            <li>
                <a
                href="https://github.com/vuejs/awesome-vue"
                target="_blank"
                >
                awesome-vue
                </a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'HelloWorld',
    data () {
        return {
            msg: 'Welcome to Your Vue.js App'
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "bootstrap/dist/css/bootstrap.min.css";
@import "../assets/css/style.scss";

h1, h2 {
    font-weight: normal;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
a {
    color: #42b983;
}


</style>
