<template>
  <NuxtExampleLayout example="queries/where" repo="nuxt/content-next">
    <template #icon>
      Nuxt/content
    </template>
    <header>
      <nav>
        <ul>
          <li>
            <NuxtLink to="/">
              Home
            </NuxtLink>
          </li>
          <li>
            <NuxtLink to="/blog-post">
              Blog post
            </NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">
              About
            </NuxtLink>
          </li>
        </ul>
      </nav>
    </header>
    <NuxtPage />
  </NuxtExampleLayout>
</template>