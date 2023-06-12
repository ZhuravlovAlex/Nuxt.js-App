<template>
  <section>
    <h1>About page</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro, voluptas.
      Reprehenderit enim fuga, eius nihil itaque officia distinctio, veritatis
      expedita quaerat tempore odio atque in saepe quia dignissimos similique
      earum!
    </p>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eveniet, amet
      alias! Velit error, porro doloremque quod perspiciatis voluptatem nihil
      laborum maxime praesentium sequi aliquid atque, sapiente non vel, suscipit
      dolores?
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
      tempora laboriosam, iusto eos asperiores quo recusandae officia illo?
      Voluptatibus vero voluptates animi alias autem dignissimos perferendis,
      tempore ipsum impedit laborum.
    </p>
  </section>
</template>

<!-- защищаем станицу с помощью middleware -->

<script>
export default {
  middleware: ["auth"],
};
</script>
