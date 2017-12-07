<template>
    <div id = "banner" class="carousel-inner">
        <div  v-for=" (item,index) in items " :class="{ item :true , active: index === 0 }">
            <a v-bind:href="['http://wufazhuce.com/one/'+item.Id]"><img class="fp-one-imagen" v-bind:src="['http://image.wufazhuce.com/'+item.Uuid]"  alt="" />
            </a> 
            <div class="fp-one-imagen-footer">
                {{item.footer}}                        </div>
            <div class="fp-one-cita-wrapper">
                <div class="fp-one-titulo-pubdate">
                    <p class="titulo">{{item.titulo}}</p>
                    <p class="dom">{{item.dom}}</p>
                    <p class="may">{{item.may}}</p>
                </div>
                <div class="fp-one-cita">
                <a v-bind:href="['http://wufazhuce.com/one/'+item.Id]">{{item.words}}</a>    </div>
                <div class="clearfix"></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'banner',
  data: function () {
  return {
          items:[
          {titulo:"VOL.1870", dom:"19", may:"Nov 2017", Id:"1899", Uuid:"FhjVnzPUCEwCzDqXv5PTL06VM3Zj", footer:"插画",  words:"凡事都得耐烦去做，忍了痛对你生活去努力。你应当用力量固执着你的希望向前去奋斗，到力尽气竭为止。我们是在同一命运下竭着力量来同生活抗拒的人，看了为可怕的时间所捏碎我们的天真与青春。"},
          {titulo:"VOL.1870", dom:"19", may:"Nov 2017", Id:"1899", Uuid:"FhjVnzPUCEwCzDqXv5PTL06VM3Zj", footer:"插画",  words:"凡事都得耐烦去做，忍了痛对你生活去努力。你应当用力量固执着你的希望向前去奋斗，到力尽气竭为止。我们是在同一命运下竭着力量来同生活抗拒的人，看了为可怕的时间所捏碎我们的天真与青春。"},
          {titulo:"VOL.1870", dom:"19", may:"Nov 2017", Id:"1899", Uuid:"FhjVnzPUCEwCzDqXv5PTL06VM3Zj", footer:"插画",  words:"凡事都得耐烦去做，忍了痛对你生活去努力。你应当用力量固执着你的希望向前去奋斗，到力尽气竭为止。我们是在同一命运下竭着力量来同生活抗拒的人，看了为可怕的时间所捏碎我们的天真与青春。"}
          ]
  		}
	}
}
</script>

<style type="text/css">
	

</style>