
<template>
  <div>
    <full-page :options="options" id="fullpage">
            <div class="section" style="background-color: #ff5f45;">
                <h3>Section 1</h3>
            </div>
            <div class="section">
              <h3>Section 2</h3>
            </div>
            <div class="section">
                <h3>Section 3</h3>
            </div>
        </full-page>
</div>
</template>

<script>
export default {
data (){
  return {
    options: {
          licenseKey: 'YOUR_KEY_HERE',
          afterLoad: this.afterLoad,
          scrollOverflow: true,
          scrollBar: false,
          menu: '#menu',
          navigation: true,
          anchors: ['page1', 'page2', 'page3'],
          sectionsColor: ['#41b883', '#ff5f45', '#0798ec']
        }
  }
}
}
</script>

