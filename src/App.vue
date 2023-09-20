<script setup lang="ts">
</script>

<template>
  <main>
    <div class="hero min-h-screen" style="background-image: url(https://i.imgur.com/0YmfR6T.jpg);">
      <div class="hero-overlay bg-opacity-50 bg-slate-950"></div>
      <div class="hero-content text-center bg-slate-950 bg-opacity-10 text-primary-content">
        <div class="max-w-md">
          <h1 class="mb-5 text-5xl font-bold">Introducing iFruit</h1>
          <p class="mb-5 text-xl">Augmenting Realities, Connecting Futures.</p>
          <button class="btn btn-primary" onclick="window.location.href='/ifruit/#order-now';">Buy Now</button>
        </div>
      </div>
    </div>
    <div id="order-now" class="hero min-h-screen" style="background-image: url(https://i.imgur.com/0YmfR6T.jpg);">
      <div class="hero-overlay bg-opacity-50 bg-slate-950"></div>
      <div class="hero-content flex-col lg:flex-row-reverse bg-slate-950 bg-opacity-10">
        <div class="text-center lg:text-left">
          <h1 class="text-5xl font-bold text-primary-content">Order now!</h1>
        </div>
        <div class="card flex-shrink-0 w-full max-w-sm shadow-2xl bg-base-100">
          <div class="card-body">
            <div class="form-control">
              <label class="label">
                <span class="label-text">Email</span>
              </label>
              <input type="text" placeholder="email" class="input input-bordered" />
            </div>
            <div class="form-control">
              <label class="label">
                <span class="label-text">Credit Card Number</span>
              </label>
              <input type="text" placeholder="xxxx-xxxx-xxxx-xxxx" class="input input-bordered" />
            </div>
            <div class="form-control mt-6">
              <button class="btn btn-primary">Order</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped></style>
