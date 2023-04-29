<template>
    <div class="profile-page">
        <section class="section-profile-cover section-shaped my-0">
            <div class="shape shape-style-1 shape-primary shape-skew alpha-4"/>
        </section>
        <section class="section section-skew">
            <div class="container">
                <card shadow class="card-profile mt--300" no-body>
                    <div class="px-4">
                        <div class="text-center mt-5">
                            <h1>문지은</h1>
                            <div class="h6 font-weight-300"><i class="ni location_pin mr-2"></i>Moon Jieun</div>
                            <div class="h5 mt-4"><i class="ni business_briefcase-24 mr-2"></i>백엔드 개발자 Backend Engineer</div>
                        </div>
                        <div class="mt-5 py-5 border-top">
                            <div class="row justify-content-center">
                                <div class="col-lg-9">
                                  <h4 class="text-primary text-uppercase font-weight-bold">Contact Information</h4>
                                  <table>
                                    <tr>
                                      <th>Email</th>
                                      <td>s2moon98@gmail.com</td>
                                    </tr>
                                    <tr>
                                      <th>Phone</th>
                                      <td>010-5542-2149</td>
                                    </tr>
                                    <tr>
                                      <th>Blog</th>
                                      <td><a href="https://velog.io/@s2moon98">https://velog.io/@s2moon98</a></td>
                                    </tr>
                                    <tr>
                                      <th>Github</th>
                                      <td><a href="https://github.com/s2moon98">https://github.com/s2moon98</a></td>
                                    </tr>
                                  </table>
                                </div>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>

      <!--Skills-->
        <section class="section section-lg pt-lg-0">
          <div class="container">
            <h3 class="text-primary text-uppercase font-weight-bold">Skills</h3>
            <div class="row justify-content-center">
              <div class="col-lg-12">
                <div class="row row-grid">
                  <div class="col-lg-4">
                    <card class="border-0" hover shadow body-classes="py-5">
                      <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                      </icon>
                      <h5 class="text-primary text-uppercase">Backend Skills</h5>
                      <ul class="navbar-nav ml-lg-auto">
                        <li>Spring Boot, Spring Batch</li>
                        <li>Java, Kotlin</li>
                        <li>JPA, MyBatis</li>
                        <li>Junit, Mockito</li>
                        <li>Gradle, Maven</li>
                        <li>Kafka</li>
                      </ul>
                    </card>
                  </div>
                  <div class="col-lg-4">
                    <card class="border-0" hover shadow body-classes="py-5">
                      <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                      </icon>
                      <h5 class="text-success text-uppercase">DevOps Skills</h5>
                      <ul class="navbar-nav ml-lg-auto">
                        <li>MySQL, MariaDB, H2</li>
                        <li>AWS EC2, S3, RDS</li>
                        <li>Docker</li>
                        <li>Github Action</li>
                      </ul>
                    </card>
                  </div>
                  <div class="col-lg-4">
                    <card class="border-0" hover shadow body-classes="py-5">
                      <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                      </icon>
                      <h5 class="text-warning text-uppercase">ETC</h5>
                      <ul class="navbar-nav ml-lg-auto">
                        <li>Linux</li>
                        <li>Git / Github / Bitbucket</li>
                        <li>Jira</li>
                        <li>Confluence</li>
                      </ul>
                    </card>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

      <!--Work Experience-->
      <section class="section section-lg pt-lg-0">
        <div class="container">
          <h3 class="text-primary text-uppercase font-weight-bold">Work Experience</h3>
          <div class="row justify-content-center">
            <div class="col-lg-12">
              <div class="row row-grid">
                <div class="col-lg-4">
                  <card shadow class="card-profile mt--300" no-body>
                    <div class="px-4">

                    </div>
                  </card>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--Side Project-->
      <section class="section section-lg pt-lg-0">
        <div class="container">
          <h3 class="text-primary text-uppercase font-weight-bold">Side Project</h3>
          <div class="row justify-content-center">
            <div class="col-lg-12">
              <div class="row row-grid">
                <div class="col-lg-4">
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--Education-->
      <section class="section section-lg pt-lg-0">
        <div class="container">
          <h3 class="text-primary text-uppercase font-weight-bold">Education</h3>
          <div class="row justify-content-center">
            <div class="col-lg-12">
              <div class="row row-grid">
                <div class="col-lg-4">
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
</template>

<script>
export default {};
</script>

<style>
th, td {
  padding: 5px;
}
</style>
