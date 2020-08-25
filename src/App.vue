<template>
  <div id="app">
    <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3">
      <!-- Content 1 -->

      <div class="bg-dark">
        <div class="flex flex-col justify-between items-center p-10 h-screen">
          <nav class="w-full">
            <ul
              class="flex justify-between text-xs items-center uppercase tracking-widest"
            >
              <li>
                <a href="#" class="text-gray-100 hover:text-gray-500">Home</a>
              </li>
              <li>
                <a href="#" class="text-gray-100 hover:text-gray-500"
                  >Galleries</a
                >
              </li>
              <li>
                <a href="#" class="text-gray-100 hover:text-gray-500">Blog</a>
              </li>
              <li>
                <a href="#" class="text-gray-100 hover:text-gray-500"
                  >Profile</a
                >
              </li>
            </ul>
          </nav>

          <div>
            <h1
              class="text-gray-100 text-6xl tracking-wide font-bold text-left leading-none mb-8"
            >
              Jessica Veranda
            </h1>

            <p class="text-gray-100 text-justify">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit.
              Reiciendis harum modi atque enim doloremque, perferendis est
              repellendus quod consequatur repellat itaque, impedit blanditiis
              quasi eaque aliquam vero possimus voluptatum ullam!
            </p>
          </div>

          <div class="flex justify-start items-start w-full">
            <a href="#"
              ><i
                class="fa fa-facebook-official text-2xl text-gray-100 hover:text-gray-500 mr-4"
                aria-hidden="true"
              ></i
            ></a>

            <a href="#"
              ><i
                class="fa fa-instagram text-2xl text-gray-100 hover:text-gray-500 mr-4"
                aria-hidden="true"
              ></i
            ></a>

            <a href="#"
              ><i
                class="fa fa-twitter-square text-2xl text-gray-100 hover:text-gray-500"
                aria-hidden="true"
              ></i
            ></a>
          </div>
        </div>
      </div>

      <!-- End of content 1 -->

      <!-- Content 2 -->

      <div class="grid grid-rows-3 grid-flow-col h-screen">
        <div class="row-span-2">
          <img
            class="object-center object-cover h-full w-full"
            src="@/assets/images/image1.jpg"
            alt="Jessica Veranda"
          />
        </div>

        <div class="row-span-1 m-16">
          <div class="flex flex-col justify-center h-full">
            <h2 class="text-gray-800 font-bold text-xl mb-3">About Me</h2>

            <p class="text-gray-600 mb-2">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            </p>

            <a href="#" class="text-gray-700 hover:text-gray-800 underline"
              >Read More</a
            >
          </div>
        </div>
      </div>

      <!-- End of content 2 -->

      <!-- Content 3 -->

      <div class="col-span-1 md:col-span-2 xl:col-span-1 h-screen">
        <div class="grid grid-rows-3 grid-flow-col h-screen">
          <div class="row-span-1 m-16">
            <div class="flex flex-col justify-center h-full">
              <h2 class="text-gray-800 font-bold text-xl mb-3">
                Beautiful places of the world
              </h2>

              <p class="text-gray-600 mb-2">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              </p>

              <a href="#" class="text-gray-700 hover:text-gray-800 underline"
                >More photos</a
              >
            </div>
          </div>

          <div class="row-span-2">
            <img
              class="object-center object-cover h-full w-full"
              src="@/assets/images/image2.jpg"
              alt="Jessica Veranda"
            />
          </div>
        </div>
      </div>

      <!-- End of content 3 -->
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>
