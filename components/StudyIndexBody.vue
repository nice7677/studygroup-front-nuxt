<template>
  <div class="body">
    <div class="container no-padding">
      <div style="padding-top: 2rem;">
        <div
          style="color: #845ef7; font-size: 1.3rem;font-family: 'Quicksand', sans-serif; letter-spacing: 0.7px; font-weight: bold; margin-bottom: 1rem;">
          스터디 찾기
            <div class="d-none d-xl-block">
              <div style="margin: 0px;" class="row no-padding">
                <div class="input-group mb-3 w-25" style="margin-top: 1rem;">
                  <div class="input-group-prepend">
                    <label class="input-group-text" for="sido">지역/시도</label>
                  </div>
                  <select class="custom-select" id="sido">
                    <option selected>선택해주세요...</option>
                    <option value="1">One</option>
                    <option value="2">Two</option>
                    <option value="3">Three</option>
                  </select>
                </div>
                <div class="input-group mb-3 w-25" style="margin-top: 1rem;margin-left: 1rem;">
                  <div class="input-group-prepend">
                    <label class="input-group-text" for="gu">지역/구</label>
                  </div>
                  <select class="custom-select" id="gu">
                    <option selected>선택해주세요...</option>
                    <option value="1">One</option>
                    <option value="2">Two</option>
                    <option value="3">Three</option>
                  </select>
                </div>
                <div class="input-group mb-3 w-25" style="margin-top: 1rem; margin-left: 1rem;">
                  <input type="text" class="form-control">
                  <div class="input-group-append">
                    <button class="btn btn-outline-secondary" type="button" id="button-addon2">검색</button>
                  </div>
                </div>
              </div>
            </div>
            <div class="d-block d-sm-none" style="">
              <div class="input-group mb-3" style="margin-top: 1rem;">
                <div class="input-group-prepend">
                  <label class="input-group-text" for="asd">지역/시도</label>
                </div>
                <select class="custom-select" id="asd">
                  <option selected>선택해주세요...</option>
                  <option value="1">One</option>
                  <option value="2">Two</option>
                  <option value="3">Three</option>
                </select>
              </div>
              <div class="input-group mb-3" style="margin-top: 1rem;">
                <div class="input-group-prepend">
                  <label class="input-group-text" for="sdf">지역 / 구</label>
                </div>
                <select class="custom-select" id="sdf">
                  <option selected>선택해주세요...</option>
                  <option value="1">One</option>
                  <option value="2">Two</option>
                  <option value="3">Three</option>
                </select>
              </div>
              <div class="input-group mb-3" style="margin-top: 1rem;">
                <input type="text" class="form-control">
                <div class="input-group-append">
                  <button class="btn btn-outline-secondary" type="button" id="button-addon3">검색</button>
                </div>
              </div>
            </div>
        </div>
      </div>
      <div class="d-none d-xl-block">
        <div class="row" style="margin-bottom: 2rem;">
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row" style="margin-bottom: 2rem;">
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row" style="margin-bottom: 2rem;">
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row" style="margin-bottom: 2rem;">
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row" style="margin-bottom: 2rem;">
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="card border-secondary mb-">
              <div class="card-header">Header</div>
              <div class="card-body text-secondary">
                <h5 class="card-title">Secondary card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="d-flex justify-content-center">
          <nav aria-label="Page navigation example">
            <ul class="pagination">
              <li class="page-item">
                <a class="page-link" href="#" aria-label="Previous">
                  <span aria-hidden="true">&laquo;</span>
                </a>
              </li>
              <li class="page-item"><a class="page-link" href="#">1</a></li>
              <li class="page-item"><a class="page-link" href="#">2</a></li>
              <li class="page-item"><a class="page-link" href="#">3</a></li>
              <li class="page-item">
                <a class="page-link" href="#" aria-label="Next">
                  <span aria-hidden="true">&raquo;</span>
                </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
      <div class="d-block d-sm-none">
        <div class="card border-secondary mb-3 w-100">
          <div class="card-header">Header</div>
          <div class="card-body text-secondary">
            <h5 class="card-title">Secondary card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
          </div>
        </div>
        <div class="card border-secondary mb-3 w-100">
          <div class="card-header">Header</div>
          <div class="card-body text-secondary">
            <h5 class="card-title">Secondary card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
          </div>
        </div>
        <div class="card border-secondary mb-3 w-100">
          <div class="card-header">Header</div>
          <div class="card-body text-secondary">
            <h5 class="card-title">Secondary card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
          </div>
        </div>
        <div class="card border-secondary mb-3 w-100">
          <div class="card-header">Header</div>
          <div class="card-body text-secondary">
            <h5 class="card-title">Secondary card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
          </div>
        </div>
        <div class="card border-secondary mb-3 w-100">
          <div class="card-header">Header</div>
          <div class="card-body text-secondary">
            <h5 class="card-title">Secondary card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
          </div>
        </div>
        <div class="card border-secondary mb-3 w-100">
          <div class="card-header">Header</div>
          <div class="card-body text-secondary">
            <h5 class="card-title">Secondary card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
          </div>
        </div>
        <div class="d-flex justify-content-center">
          <nav aria-label="Page navigation example">
            <ul class="pagination">
              <li class="page-item">
                <a class="page-link" href="#" aria-label="Previous">
                  <span aria-hidden="true">&laquo;</span>
                </a>
              </li>
              <li class="page-item"><a class="page-link" href="#">1</a></li>
              <li class="page-item"><a class="page-link" href="#">2</a></li>
              <li class="page-item"><a class="page-link" href="#">3</a></li>
              <li class="page-item">
                <a class="page-link" href="#" aria-label="Next">
                  <span aria-hidden="true">&raquo;</span>
                </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "StudyIndexBody"
  }
</script>

<style scoped>
  .body {
    margin-top: 4rem;
    /*margin-bottom: 1rem;*/
  }
</style>
