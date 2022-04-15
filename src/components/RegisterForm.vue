<template>
    <div class="width">
        <h3>Register New User</h3>
      <div class="text-left card_">

          <!-- Where needs to be added  -->
        <form @submit.prevent="" method="POST" id="">
            <div class="d-inline-flex w_full ">
                <div class="mb-3  space_between w_full">
                    <label for="username" class="form-label">Username</label>
                    <input type="text" class="form-control w_full" id="username" >
                </div>
                <div class="mb-3 w_full">
                    <label for="password" class="form-label">Password</label>
                    <input type="password" class="form-control w_full" id="password">
                </div>
            </div>

            <div class="d-inline-flex w_full">
                <div class="mb-3 space_between w_full">
                    <label for="fullname" class="form-label">fullname</label>
                    <input type="text" class="form-control w_full" id="fullname" >
                </div>

                <div class="mb-3 w_full">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control w_full" id="email" >
                </div>
            </div>

               <div class="mb-3 w_full">
                    <label for="location" class="form-label">Location</label>
                    <input type="text" class="form-control" id="location" >
                </div>
            <div class="mb-3 w_full">
                    <label for="Biography" class="form-label">Biography</label>
                    <textarea  class="form-control" id="Biography" ></textarea>
            </div>
            <input type="file" class="btn btn-light" id="photo"  name="photo" > <br/>
          
            <button type="submit" class="btn_ btn-success" >Submit</button>
        </form>
      </div>
    </div>
</template>


<style>
.width{
  width: 36rem;
  padding-right: 0.75rem;
  padding-left: 0.75rem;
  margin-right: auto;
  margin-left: auto;
}
.space_between{
    margin-right: 10px;
}
.w_full{
    width:100%;
}
.btn_{
    padding:4px 24px;
    border: none;
    border-radius: 4px;
}

.card_{
    margin-top:4em;
    padding:1em;
    border-radius: 6px;
    box-shadow: 2px 2px 10px 4px  rgba(0,0,0,.1);
    border: 2px solid transparent;
}

@media screen and (max-width:800px){
  .width{
    width: 100%;
  }
  
}
</style>