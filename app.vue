<template>
  <UContainer class="py-6">
    <header>
      <div class="flex flex-col gap-2 md:flex-row md:items-center">
        <UAvatar
          src="/muylogo.png"
          size="3xl"
          :ui="{
            size: {
              '3xl': 'h-42 w-42',
            },
          }" />

        <div class="flex flex-col gap-2 items-start">
          <div
            class="flex flex-col md:flex-row md:items-center md:justify-center md:gap-2">
            <div class="flex items-center justify-start gap-2">
              <p class="font-semibold text-xl text-gray-200"
                >muyinteresante_es</p
              >
              <UIcon
                name="i-heroicons-check-circle-16-solid"
                class="h-6 w-6 text-blue-500" />
            </div>
            <p class="font-semibold text-xl text-gray-500">Muy Interesante</p>
          </div>

          <div
            class="flex flex-col md:flex-row md:gap-4 md:items-center md:justify-center">
            <div class="flex items-center justify-start gap-2">
              <p class="font-semibold text-lg text-gray-200">14</p>
              <p class="font-semibold text-gray-400">Sigiuendo</p>
            </div>
            <div class="flex items-center justify-start gap-2">
              <p class="font-semibold text-lg text-gray-200">297.1K</p>
              <p class="font-semibold text-gray-400">Seguidores</p>
            </div>
            <div class="flex items-center justify-start gap-2">
              <p class="font-semibold text-lg text-gray-200">321.9K</p>
              <p class="font-semibold text-gray-400">Me guesta</p>
            </div>
          </div>

          <p class="font-medium text-lg text-gray-400"
            >Cuenta oficial de Muy Interesante</p
          >

          <div class="flex gap-1 items-center justify-start">
            <UIcon
              name="i-heroicons-link-20-solid"
              class="h-4 w-4 text-primary" />
            <ULink
              to="/"
              active-class="text-red-400"
              inactive-class="text-primary-500 hover:text-red-700"
              >mtr.bio/muyinteresante</ULink
            >
          </div>

          <div class="flex items-center justify-center gap-1">
            <UButton label="Seguir" size="sm" />
            <UButton label="Mensaje" size="sm" variant="soft" />
            <UButton
              icon="i-solar-multiple-forward-right-bold"
              size="sm"
              variant="soft" />
            <UButton icon="i-solar-menu-dots-bold" size="sm" variant="soft" />
          </div>
        </div>
      </div>
    </header>
  </UContainer>
</template>

<style>
body {
  background-color: black;
  color: white;
}
</style>
