**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[runnervmkj6or:08843] *** Process received signal ***
[runnervmkj6or:08843] Signal: Aborted (6)
[runnervmkj6or:08843] Signal code:  (-6)
[runnervmkj6or:08843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0df4245330]
[runnervmkj6or:08843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0df429eb2c]
[runnervmkj6or:08843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0df424527e]
[runnervmkj6or:08843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0df42288ff]
[runnervmkj6or:08843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0df46a5ff5]
[runnervmkj6or:08843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0df46bb0da]
[runnervmkj6or:08843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0df46a5a55]
[runnervmkj6or:08843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0df46a5a6f]
[runnervmkj6or:08843] [ 8] plumed(+0x146dd)[0x557b78e916dd]
[runnervmkj6or:08843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0df422a1ca]
[runnervmkj6or:08843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0df422a28b]
[runnervmkj6or:08843] [11] plumed(+0x15365)[0x557b78e92365]
[runnervmkj6or:08843] *** End of error message ***
</pre>
{% endraw %}
