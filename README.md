## Hello VuePress!

*Cat.jpg* located in `public` directory

<img :src="$withBase('/cat.jpg')" alt="foo">

_How are you doing?_
> **I'm doing fine, thanks!**

_Great, I was wondering what `49 + 32` is?_
> **{{49 + 32}}**

_Could you repeat that a few times?_

> **Sigh...**
<p v-for="i of 3">{{49 + 32}}</p>
