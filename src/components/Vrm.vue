<template>
  <div class="vrm"></div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import * as THREE from "three";
import { GLTFLoader } from "three/examples/jsm/loaders/GLTFLoader";
import { VRM } from "@pixiv/three-vrm";

@Component
export default class Vrm extends Vue {}
</script>

<style>
</style>
