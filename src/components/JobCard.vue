<template>
  <div>
    <b-col>
          <b-card
            :title="name"
            img-src="https://picsum.photos/600/300/?image=25"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem;"
            class="mb-2"
            footer="Welecom !"
          >
            <b-card-text>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis quia voluptatem beatae praesentium, animi, vel sed laudantium tenetur repellendus architecto illo reprehenderit, commodi sapiente possimus quod quam modi consequuntur cumque.
            </b-card-text>

            <b-button variant="primary">Apply</b-button>
          </b-card>
        </b-col>
        </div>
</template>

<script>
export default {
  props:["name"]

};
</script>

<style lang="scss" scroped>

</style>