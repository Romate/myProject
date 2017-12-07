<template>
    <div class="col-md-4">
        <div class="row">
            <div class="col-md-12">
                <div class="fp-one-articulo"><!--文章，和问题的访问链接不同-->
                    <h4>
                    
                            ONE
                            文章
                    </h4>
                    <div  class="corriente"><!--封成一个组件-->
                        <p class="one-titulo">
                            {{titulo}}                        </p>
                        <p class="one-articulo-titulo">
                            <a v-bind:href="['http://wufazhuce.com/article/'+Id]">
                                {{words}}                            <small>- </small>
                            </a>
                        </p>
                    </div>

                    <ul class="list-unstyled pasado">
                        <li v-for="item in items">
                            <span class="text-muted">{{item.muted}}</span>
                            <a href="['http://wufazhuce.com/article/'+item.Id]">
                                {{item.words}}}                               <small>- {{item.author}}</small>
                            </a>
                        </li>
                    </ul>
                </div>
               <div class="fp-one-cuestion">
                    <h4>
                            ONE
                            问题
                    </h4>
                    <div class="corriente">
                        <p class="one-titulo">
                            VOL.1870                        </p>
                        <p class="one-cuestion-titulo">
                            <a href="http://wufazhuce.com/question/1920">
                                年轻而贫穷的那段岁月，该如何度过？                            </a>
                        </p>
                    </div>
                    <ul class="list-unstyled pasado">
                                                <li>
                            <span class="text-muted">VOL.1869</span>
                            <a href="http://wufazhuce.com/question/1919">
                                当我在写一本爱情小说的时候，我在想些什么？                    </a>
                        </li>
                                                <li>
                            <span class="text-muted">VOL.1868</span>
                            <a href="http://wufazhuce.com/question/1916">
                                凭什么要求世界善待混吃等死的你？                              </a>
                        </li>
                                                <li>
                            <span class="text-muted">VOL.1867</span>
                            <a href="http://wufazhuce.com/question/1918">
                                你收到过哪些只有惊没有喜的“惊喜”？                            </a>
                        </li>
                                                <li>
                            <span class="text-muted">VOL.1866</span>
                            <a href="http://wufazhuce.com/question/1917">
                                为什么越优秀的人，越难觉得快乐？                              </a>
                        </li>
                                                <li>
                            <span class="text-muted">VOL.1866</span>
                            <a href="http://wufazhuce.com/question/1917">
                                为什么越优秀的人，越难觉得快乐？                              </a>
                        </li>
                                                <li>
                            <span class="text-muted">VOL.1866</span>
                            <a href="http://wufazhuce.com/question/1917">
                                为什么越优秀的人，越难觉得快乐？                              </a>
                        </li>

                                            </ul>
                </div>
                
            </div>
            
        </div>
    </div>
</template>
<script>
    export default{
        name:'test',
        data: function(){
            return {
                title:"文章",
                titulo:"VOL.1870",
                Id:2913,
                words:"当我们在谈论爱情时我们在鬼扯什么",
                items:[
                    {muted:"VOL.1869",Id:2017,words:"当我们在谈论爱情时我们在鬼扯什么",author:"王传博"},
                    {muted:"VOL.1869",Id:2017,words:"当我们在谈论爱情时我们在鬼扯什么",author:"王传博"},
                    {muted:"VOL.1869",Id:2017,words:"当我们在谈论爱情时我们在鬼扯什么",author:"王传博"},
                    {muted:"VOL.1869",Id:2017,words:"当我们在谈论爱情时我们在鬼扯什么",author:"王传博"},
                    {muted:"VOL.1869",Id:2017,words:"当我们在谈论爱情时我们在鬼扯什么",author:"王传博"},
                    {muted:"VOL.1869",Id:2017,words:"当我们在谈论爱情时我们在鬼扯什么",author:"王传博"},
                    {muted:"VOL.1869",Id:2017,words:"当我们在谈论爱情时我们在鬼扯什么",author:"王传博"},
                    ]
                }    
            }
        }
</script>

<style>
    

</style>