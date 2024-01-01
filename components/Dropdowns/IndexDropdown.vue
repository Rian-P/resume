<template>
  <div>
    <a
      class="hover:text-blueGray-500 text-blueGray-700 px-3 py-2 flex items-center text-xs uppercase font-bold"
      href="#pablo"
      ref="btnDropdownRef"
      v-on:click="toggleDropdown($event)"
    >
      Sosial Media
    </a>
    <div
      ref="popoverDropdownRef"
      class="bg-white text-base z-50 float-left py-2 list-none text-left rounded shadow-lg min-w-48"
      :class="{ hidden: !dropdownPopoverShow, block: dropdownPopoverShow }"
    >
      <a
        class="text-sm pt-2 pb-0 px-4 block w-full whitespace-nowrap bg-transparent text-blueGray-400"
        :href="getSocialMediaLink('instagram')"
      >
        Instagram
      </a>
      <a
        :href="getSocialMediaLink('linkedin')"
        target="_blank"
        class="text-sm py-2 px-4 font-normal block w-full whitespace-nowrap bg-transparent text-blueGray-700"
      >
        LinkedIn
      </a>
    </div>
  </div>
</template>

<script>
import { createPopper } from "@popperjs/core";

export default {
  data() {
    return {
      dropdownPopoverShow: false,
    };
  },
  methods: {
    toggleDropdown: function (event) {
      event.preventDefault();
      this.dropdownPopoverShow = !this.dropdownPopoverShow;

      if (this.dropdownPopoverShow) {
        createPopper(this.$refs.btnDropdownRef, this.$refs.popoverDropdownRef, {
          placement: "bottom-start",
        });
      }
    },
    getSocialMediaLink(platform) {
      switch (platform) {
        case 'instagram':
          // Replace with your Instagram link
          return "https://www.instagram.com/ryan_pratama06?igsh=OGQ5ZDc2ODk2ZA==";
        case 'linkedin':
          // Replace with your LinkedIn link
          return "https://www.linkedin.com/in/rian-pratama-737bb5224/";
          default:
          return "";
      }
    },
  },
};
</script>
