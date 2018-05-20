<template>
  <section>
    <h1>{{ title }}</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris vel lobortis eros. Mauris eget velit mattis, viverra ligula vitae, rhoncus augue. Maecenas quis condimentum eros. Donec vitae magna sed justo cursus tempor. Mauris sit amet nisl tempor, aliquam urna id, rutrum felis. Vestibulum vehicula ipsum in nisi bibendum elementum vel eu erat. Phasellus elit quam, feugiat hendrerit eleifend nec, lacinia at odio. Etiam eu imperdiet nisi, in consequat diam. Fusce cursus luctus euismod. Nam rhoncus porta congue. Etiam vel cursus turpis. Sed sem neque, vestibulum eget lacinia a, dapibus non urna. Phasellus mattis nisl vel pharetra malesuada. Praesent ultrices eleifend tempus. Proin sit amet felis nec ex sagittis malesuada non id ante.</p>
    <p>Curabitur lacinia luctus varius. Nullam justo est, bibendum a commodo non, blandit sit amet ligula. Suspendisse convallis laoreet cursus. Proin sollicitudin metus molestie, auctor orci vitae, commodo ligula. Maecenas quis nulla et ipsum sodales maximus vitae molestie lacus. Nunc sodales nisl nisl, a molestie tellus tristique vitae. Etiam sit amet eros neque.</p>
    <p>Duis varius in felis ac egestas. Curabitur congue non risus quis bibendum. Proin vel sagittis augue. Integer vestibulum turpis enim, et condimentum urna auctor at. Curabitur eu ex pretium, volutpat purus vitae, hendrerit nisl. Aenean a dui quis ante pharetra facilisis. Aliquam consectetur, nulla ut gravida dictum, enim ex tempor ligula, luctus facilisis nisl sem vel nisl. Fusce porttitor, sapien non scelerisque commodo, mi leo blandit orci, sed commodo risus leo sit amet justo. Suspendisse congue felis tempus, tincidunt lorem ut, congue ipsum. Curabitur quis accumsan elit. Sed maximus volutpat ipsum. Etiam vulputate ornare egestas. Vestibulum ipsum metus, fermentum sit amet diam vitae, efficitur maximus leo. Mauris et tempor turpis. Duis eu arcu ligula. Donec at maximus leo.</p>
    <p>In et justo felis. Morbi neque lorem, aliquet non pellentesque sed, congue sodales massa. In dictum bibendum nunc eget vestibulum. Phasellus vitae nunc nibh. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam finibus placerat nisl a venenatis. Cras eget scelerisque urna. Curabitur aliquam metus varius, placerat arcu at, aliquam justo. Cras a libero tempor, suscipit nisl ut, pellentesque risus. Nunc a nulla dictum, ultrices quam sed, accumsan lectus. Etiam nisi libero, hendrerit eu velit sit amet, suscipit suscipit augue. In hac habitasse platea dictumst. Nulla ac lectus velit. Praesent pellentesque laoreet diam, sit amet laoreet erat viverra ut. </p>
  </section>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
    }
  },
  data() {
    return {

    }
  }
}
</script>

<style scoped>
  h1 {
    color: black;
    text-align: center;
    font-size: 40px;
  }

  p {
    max-width: 800px;
    text-align: justify;
    margin: 50px auto;
    line-height: 1.6;
  }

</style>
