<template>
    <div>
      <navigation></navigation>
        <!-- <hero></hero> -->

        <!-- <inputs></inputs> -->
        <!-- <custom-controls></custom-controls> -->
        
        <javascript-components></javascript-components>
        <!-- <basic-elements></basic-elements> -->
        <!-- <icons></icons>
        <examples></examples>
        <download-section></download-section>
        <carousel></carousel>  -->
    </div>
</template>
<script>
import Hero from "./components/Hero";
import BasicElements from "./components/BasicElements";
import Inputs from "./components/Inputs";
import CustomControls from "./components/CustomControls";
import Navigation from "./components/Navigation";
import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";
import Icons from "./components/Icons";
import Examples from "./components/Examples";
import DownloadSection from "./components/DownloadSection";

// todo.add()


export default {
  name: "components",
  components: {
    Hero,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    Icons,
    Examples,
    DownloadSection
  }
};
</script>
