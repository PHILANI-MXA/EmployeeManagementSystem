<template>
  <div class="home container min-h-100">
    <h4>Employees</h4>
    <table class="table">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">PersonID</th>
          <th scope="col">Firstname</th>
          <th scope="col">Lastname</th>
          <th scope="col">DateOfbirth</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>1020</td>
          <td>Mark</td>
          <td>Otto</td>
          <td>1975-04-02</td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>1030</td>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>1990-08-28</td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td>1040</td>
          <td>Larry</td>
          <td>the Bird</td>
          <td>1986-04-20</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
