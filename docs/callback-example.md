[//]: # (# Call Back Examples)

[//]: # ()
[//]: # ([vue-signature-pad]&#40;https://github.com/neighborhood999/vue-signature-pad&#41; use [szimek/signature_pad]&#40;https://github.com/szimek/signature_pad&#41; default setting as `options`, feel free custom you wanted options. In [v1.1]&#40;https://github.com/neighborhood999/vue-signature-pad/releases/tag/1.1.0&#41; add `onBegin` and `onEnd` event callback:)

[//]: # ()
[//]: # (```html)

[//]: # (<template>)

[//]: # (  <div id="app">)

[//]: # (    <VueSignaturePad)

[//]: # (      width="500px")

[//]: # (      height="500px")

[//]: # (      ref="signaturePad")

[//]: # (      :options="{ onBegin, onEnd }")

[//]: # (    />)

[//]: # (  </div>)

[//]: # (</template>)

[//]: # (<script>)

[//]: # (export default {)

[//]: # (  methods: {)

[//]: # (    onBegin&#40;&#41; {)

[//]: # (      console.log&#40;'=== Begin ==='&#41;;)

[//]: # (    },)

[//]: # (    onEnd&#40;&#41; {)

[//]: # (      console.log&#40;'=== End ==='&#41;;)

[//]: # (    })

[//]: # (  })

[//]: # (};)

[//]: # (</script>)

[//]: # (```)
