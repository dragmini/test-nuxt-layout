<template>
    <article>
        <header class="entry-header">
            <h1 class="entry-title"><a href="blog-single.html" rel="bookmark">Somewhere in time</a></h1>
            <div class="entry-meta">
                <span class="posted-on"><time class="entry-date published">April 12, 2016</time></span>						
                <span class="comments-link"><a href="#">Leave a comment</a></span>
            </div>
            <div class="entry-thumbnail">						
                <img src="http://s3.amazonaws.com/caymandemo/wp-content/uploads/sites/10/2015/09/30160348/sep4.jpg" alt="">
            </div>
        </header>
        <div class="entry-summary">
            <p>
                When Mary Lennox was sent to Manor to live with her uncle everybody said she was the most disagreeablelooking child ever seen. It was true, too. She had a little thin face and a little thin body, thin light hair and a sour expression. Her hair was yellow, and her face was yellow because she <a class="more-link" href="blog-single.html">Read more</a>
            </p>
        </div>
        <footer class="entry-footer">
            <span class="cat-links">
            Posted in <a href="#" rel="category tag">audio</a>, <a href="#" rel="category tag">embed</a>, <a href="#" rel="category tag">media</a>
            </span>
        </footer>
    </article>
</template>

<script setup lang="ts">
import { BlogCardProp } from '../types/blog.interface';

const props = defineProps<BlogCardProp>()

</script>