# Helper
this is helper tools


## 替换掉所有的 html标签，得到Html标签中的内容
<pre><code>
let s='<a href="/account/gy4dkmjzhege">gy4dkmjzhege</a> bought <span class="white--text">3666 bytes</span> RAM for <a href="/account/woeosqianbao">woeosqianbao</a>';
 let dd=s.replace(/<\/?.+?>/g,"");
 console.log(dd);
 let dds=dd.replace(/ /g,"");//dds为得到后的内容
 console.log(dds);
 </code></pre>
