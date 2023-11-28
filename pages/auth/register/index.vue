<template>
  <div class="w-full bg-base-200">
    <div class="flex flex-col items-center justify-center px-6 py-8 mx-auto md:h-screen lg:py-0">
      <div class="w-full max-w-sm shadow-2xl card bg-base-100 shrink-0">
        <form class="card-body">
          <div class="form-control">
            <label class="label">
              <span class="label-text">Email</span>
            </label>
            <input type="email" placeholder="email" class="input input-bordered" required />
          </div>
          <div class="form-control">
            <label class="label">
              <span class="label-text">Password</span>
            </label>
            <input type="password" placeholder="password" class="input input-bordered" required />
          </div>
          <div class="form-control">
            <label class="label">
              <span class="label-text">Confirm Password</span>
            </label>
            <input type="password" placeholder="password" class="input input-bordered" required />
          </div>
          <div class="mt-6 form-control">
            <button class="btn btn-primary">Get Started</button>
          </div>
          <div>
            <label class="flex label">
              <p class="text-sm">Already have an account?
                <a class="text-sm text-primary label-text-alt link">
                <NuxtLink to="login">Log in</NuxtLink>
              </a>
            </p>
            </label>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style>

</style>