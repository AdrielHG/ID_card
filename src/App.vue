<script>
export default{
  data(){
    return {
      schoolName: "TecMilenio",
      ID: "4536",
      studentName: "Jorge",
      className: "Software"
    }
  }
}

</script>

<template>

<div class="container">
  <div class="card mx-auto my-3" style="max-width: 500px; border-radius: 10px;">
  <div class="card-body">

    <div class="row align-items-center justify-content-center text-center mb-3">
      <div class="col-12 col-md-3">
        <img src="" alt="logo" class="img-fluid" style="max-height: 50px;">
      </div>
      <div class="col-12 col-md-8">
        <h1 class="h5 mb-0"><span>{{ schoolName }}</span></h1>
      </div>
    </div>


    <div class="row justify-content-center text-center">
      <div class="col-12 col-md-4">
        <img src="" alt="profile pic">
      </div>
      <div class="col-12 col-md-8 text-left mt-3 mt-md-0">
        <p class="mb-1"><strong>ID:</strong> <span>{{ ID }}</span></p>
        <p class="mb-1"><strong>Student Name:</strong> <span>{{ studentName }}</span></p>
        <p class="mb-0"><strong>Class Name:</strong> <span>{{ className }}</span></p>
      </div>
    </div>
  </div>
</div>

  

  <div class="row justify-content-center">
    <div class="col-12 col-md-5">
  
      <label for="" class="form-label">School Name</label>
      <input type="text" class="form-control mb-3" v-model="schoolName">
  
      <label for="" class="form-label">ID</label>
      <input type="text" class="form-control mb-3" v-model="ID">
  
      <label for="" class="form-label">Student Name</label>
      <input type="text" class="form-control mb-3" v-model="studentName">
  
      <label for="" class="form-label">Class Name</label>
      <input type="text" class="form-control mb-3" v-model="className">
  
    </div>
  </div>

</div>


</template>

<style scoped>

</style>