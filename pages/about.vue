<template>
<div class="container">
<h1 class="font-weight-bold text-primary">About vinjokes</h1>
<p>This is a web application licenced under MIT licencing Board to render the most corny jokes from vincent khamala on the web. This application
  is built for fun to vincents fans. We are not liable to any misuse of this application in whichever way.
 misuse of the contents or piracy of this content is absolutely prohibited.
  </p>

<hr class="dotted">

<h1 class="h">Stay at home have fun stay safe with vinjokes app.</h1>

  <hr class="dotted">
   <h1 class="h">#AvoidCoronaVirus_Infections</h1>
   <hr class="dotted">

   <h1 class="h text-underlined">One Love For Us All. Thanks</h1>
</div>
</template>

<script>
export default {
head() {
    return {
        title: 'About the app',
        meta: [
            {
                hid:'description',
                name:'description',
                content:'The best place for vincents corny jokes'
            }
        ]

    }
}
};
</script>

<style>
.container{
  border-color: blueviolet;
}

.dotted {
    padding: 1rem;
    border: 1px dotted #ccc;
    margin: 1rem 0;
}

.h {
    padding: 1rem;
    font-weight: 700;
    justify-content: center;
    font-style: italic;
    font-kerning: auto;
    text-align: center;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    margin: 1rem 0;

}

</style>
