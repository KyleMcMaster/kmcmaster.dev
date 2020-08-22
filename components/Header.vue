<template>
  <header>
    <nav
      class="navbar justify-content-end"
      role="navigation"
      aria-label="main navigation"
    >
      <div>
        <a
          :href="linkedin"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          <span class="icon"><fa :icon="['fab', 'linkedin']"/></span>
        </a>
        <a
          :href="github"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          <span class="icon"><fa :icon="['fab', 'github']"/></span>
        </a>
      </div>
    </nav>
  </header>
</template>
<script>
export default {
  data(){
    return {
      github: "https://github.com/kylemcmaster",
      linkedin: "https://www.linkedin.com/in/kylerobertmcmaster"
    }
  }
}
</script>
