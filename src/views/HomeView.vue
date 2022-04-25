<template>
  <div class="home">
    <h1>Home</h1>
    <p>This is the Home page</p>
  </div>
</template>

<script lang="ts">
import { ref } from "vue";

export default {
  name: "HomeView",
  components: {
    // ... components use here <PostList />
  },
  props: ["props-name-here"],
  setup(props) {
    const posts = ref([
      {
        id: 1,
        title: "Como hacer una ssr con Vue",
        description:
          "Incididunt nostrud aliquip aliquip sunt commodo ullamco fugiat excepteur. Ut laboris cillum veniam dolor magna eu. Reprehenderit adipisicing voluptate enim sit Lorem irure in consectetur duis amet velit officia. Tempor irure cillum nostrud do eiusmod minim nostrud ullamco irure ad. Nisi sit duis proident enim laborum labore culpa proident labore nulla fugiat. Deserunt nisi exercitation magna minim voluptate ea. Sit ipsum ex exercitation dolore nisi ullamco laborum anim duis reprehenderit voluptate ipsum reprehenderit.Commodo consectetur laboris officia magna sit Lorem nulla pariatur pariatur Lorem adipisicing deserunt pariatur. Est incididunt nisi laborum aliqua nisi elit consectetur incididunt ut eu. Cupidatat laboris aute dolor sit. Consequat aute veniam reprehenderit veniam aliqua cupidatat anim in deserunt occaecat officia nisi ullamco. Elit deserunt irure eiusmod Lorem quis. Est deserunt non ad adipisicing eu ex nostrud irure quis consectetur fugiat.",
        image: "https://picsum.photos/id/237/200/300",
        tags: ["vue", "ssr", "learning", "typescript"],
      },
      {
        id: 2,
        title: "Como hacer una ssr con Vue",
        description:
          "Incididunt nostrud aliquip aliquip sunt commodo ullamco fugiat excepteur. Ut laboris cillum veniam dolor magna eu. Reprehenderit adipisicing voluptate enim sit Lorem irure in consectetur duis amet velit officia. Tempor irure cillum nostrud do eiusmod minim nostrud ullamco irure ad. Nisi sit duis proident enim laborum labore culpa proident labore nulla fugiat. Deserunt nisi exercitation magna minim voluptate ea. Sit ipsum ex exercitation dolore nisi ullamco laborum anim duis reprehenderit voluptate ipsum reprehenderit.Commodo consectetur laboris officia magna sit Lorem nulla pariatur pariatur Lorem adipisicing deserunt pariatur. Est incididunt nisi laborum aliqua nisi elit consectetur incididunt ut eu. Cupidatat laboris aute dolor sit. Consequat aute veniam reprehenderit veniam aliqua cupidatat anim in deserunt occaecat officia nisi ullamco. Elit deserunt irure eiusmod Lorem quis. Est deserunt non ad adipisicing eu ex nostrud irure quis consectetur fugiat.",
        image: "https://picsum.photos/id/237/200/300",
        tags: ["react", "typescript"],
      },
      {
        id: 3,
        title: "Como hacer una ssr con Vue",
        description:
          "Incididunt nostrud aliquip aliquip sunt commodo ullamco fugiat excepteur. Ut laboris cillum veniam dolor magna eu. Reprehenderit adipisicing voluptate enim sit Lorem irure in consectetur duis amet velit officia. Tempor irure cillum nostrud do eiusmod minim nostrud ullamco irure ad. Nisi sit duis proident enim laborum labore culpa proident labore nulla fugiat. Deserunt nisi exercitation magna minim voluptate ea. Sit ipsum ex exercitation dolore nisi ullamco laborum anim duis reprehenderit voluptate ipsum reprehenderit.Commodo consectetur laboris officia magna sit Lorem nulla pariatur pariatur Lorem adipisicing deserunt pariatur. Est incididunt nisi laborum aliqua nisi elit consectetur incididunt ut eu. Cupidatat laboris aute dolor sit. Consequat aute veniam reprehenderit veniam aliqua cupidatat anim in deserunt occaecat officia nisi ullamco. Elit deserunt irure eiusmod Lorem quis. Est deserunt non ad adipisicing eu ex nostrud irure quis consectetur fugiat.",
        image: "https://picsum.photos/id/237/200/300",
        tags: ["angular", "clean code", "testing", "typescript"],
      },
    ]);

    return { posts };
  },
};
</script>
