<template>
  <div class="home">
    <h1>This is an home page</h1>
    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="" class="d-block w-100" alt="">
        </div>
        <div class="carousel-item">
          <img src="" class="d-block w-100" alt="">
        </div>
        <div class="carousel-item">
          <img src="" class="d-block w-100" alt="">
        </div>
      </div>
      <button class="carousel-control-prev"
              type="button"
              data-bs-target="#carouselExampleControls"
              data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next"
              type="button"
              data-bs-target="#carouselExampleControls"
              data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

    <table class="table">
      <thead>
      <tr>
        <th scope="col">#</th>
        <th scope="col">First</th>
        <th scope="col">Last</th>
        <th scope="col">Handle</th>
      </tr>
      </thead>
      <tbody>
      <tr>
        <th scope="row">1</th>
        <td>Mark</td>
        <td>Otto</td>
        <td>@mdo</td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td>Jacob</td>
        <td>Thornton</td>
        <td>@fat</td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td colspan="2">Larry the Bird</td>
        <td>@twitter</td>
      </tr>
      </tbody>
    </table>

    <div class="mb-3">
      <label for="formFile" class="form-label">Default file input example</label>
      <input class="form-control" type="file" id="formFile">
    </div>
    <div class="mb-3">
      <label for="formFileMultiple" class="form-label">Multiple files input example</label>
      <input class="form-control" type="file" id="formFileMultiple" multiple>
    </div>
    <div class="mb-3">
      <label for="formFileDisabled" class="form-label">Disabled file input example</label>
      <input class="form-control" type="file" id="formFileDisabled" disabled>
    </div>
    <div class="mb-3">
      <label for="formFileSm" class="form-label">Small file input example</label>
      <input class="form-control form-control-sm" id="formFileSm" type="file">
    </div>
    <div>
      <label for="formFileLg" class="form-label">Large file input example</label>
      <input class="form-control form-control-lg" id="formFileLg" type="file">
    </div>

    <div class="card" style="width: 18rem;">
      <img src="" class="card-img-top" alt="">
      <div class="card-body">
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
      </div>
    </div>

  </div>

</template>

<script>

export default {
  name: 'Home',
}
</script>
