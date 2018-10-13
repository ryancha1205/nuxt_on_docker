<template>
  <section class="post-list">
    <PostPreview id="1" thumbnail="https://www.visioncritical.com/wp-content/uploads/2015/12/tech-companies-resources-950x700.jpg" title="hello there!" previewText="This is my first post!" />
    <PostPreview id="2" thumbnail="https://www.visioncritical.com/wp-content/uploads/2015/12/tech-companies-resources-950x700.jpg" title="good" previewText="good job" />
  </section>
</template>

<script>
import PostPreview from "@/components/Posts/PostPreview";
export default {
  components: {
    PostPreview
  }
};
</script>
<style>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>

