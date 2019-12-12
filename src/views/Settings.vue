<template>
<div>
  <div class="row">
    <div class="col">
      <h1 class="text-center mb-5">Change password</h1>
    </div>
  </div>
  <div class="row">
    <div class="col"></div>
    <div class="col">
      <form @submit.prevent="changepw">
        <div class="form-group">
          <label for="confirmPasswordField">Choose new password</label>
          <input v-model="newpassword" type="password" class="form-control" id="confirmPasswordField" placeholder="New password">
        </div>
        <button type="submit" class="btn btn-primary mt-5">Submit</button>
      </form>
    </div>
    <div class="col"></div>
  </div>
</div>
</template>

<script>
export default {
  data () {
    return {
      newpassword: '',

    }
  },
  methods: {
    changepw () {
            firebase.auth().currentUser.updatePassword(this.newpassword).then(function(){

                // Success

            }).catch(function(err){
              console.log(error);
            });
    }
  }
}
</script>