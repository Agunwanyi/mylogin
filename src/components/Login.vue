<template>
    <div class="login">
        <h1 class="text-center mt-2 text-light">USER LOGIN</h1>
        <div class="form-group d-flex justify-content-center mt-5">
          <label for=""><i class="fa fa-user-o use " aria-hidden="true"></i></label>
          <input type="text" class="form-control-file box" name="" id="" placeholder="Username">
        </div>
        <div class="form-group d-flex justify-content-center mt-4">
          <label for=""><i class="fa fa-key use" aria-hidden="true"></i></label>
          <input type="text" class="form-control-file box" name="" id="" placeholder="Password">
        </div>
        <button class="enter mt-5">Login</button>
    </div>
</template>
<script>
export default {
    setup() {
        
    },
}
</script>
<style scoped>
.login{
    width: 30%;
    height: 25rem;
    margin-left: 30rem;
    margin-top: 5rem;
}
.box{
    width: 60%;
    height: 3rem;
    border-radius: 1.5rem;
    position: relative;
    border: none;
    background-color: rgba(248, 245, 245, 0.712);
}
.use{
    font-size: 2rem;
    position: absolute;
    margin-left: 16rem;
    z-index: 1;
    height: 3rem;
    width: 3rem;
    border-radius: 1.5rem;
    background-color: #ffff;
    text-align: center;
}
.enter{
    width: 64%;
    height: 3rem;
    border-radius: 1.5rem;
    margin-left: 6rem;
}
</style>