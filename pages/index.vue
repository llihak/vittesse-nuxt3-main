<template>
  <div>
    <!-- <Nue /> -->
    <!-- <Logos mb-6 /> -->
    <h1 class="text-red-800 text-4xl">
      Tailwind or unocss ???
    </h1>
    <Golden />
    <hr>
    <img src="/man-at-the-peak-3200-1981_j85wzj_c_scale,w_1400.webp" alt="climber">
    <Suspense>
      <!-- <PageView /> -->
      <template #fallback>
        <div op50 italic>
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>
    <!-- <InputEntry /> -->
  </div>
</template>
