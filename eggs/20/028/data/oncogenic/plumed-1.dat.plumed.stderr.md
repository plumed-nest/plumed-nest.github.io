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
[fv-az1693-957:66836] *** Process received signal ***
[fv-az1693-957:66836] Signal: Aborted (6)
[fv-az1693-957:66836] Signal code:  (-6)
[fv-az1693-957:66836] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f03cf645330]
[fv-az1693-957:66836] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f03cf69eb2c]
[fv-az1693-957:66836] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f03cf64527e]
[fv-az1693-957:66836] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03cf6288ff]
[fv-az1693-957:66836] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03cfaa5ff5]
[fv-az1693-957:66836] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03cfabb0da]
[fv-az1693-957:66836] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03cfaa5a55]
[fv-az1693-957:66836] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03cfaa5a6f]
[fv-az1693-957:66836] [ 8] plumed(+0x146dd)[0x561ea02c56dd]
[fv-az1693-957:66836] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f03cf62a1ca]
[fv-az1693-957:66836] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f03cf62a28b]
[fv-az1693-957:66836] [11] plumed(+0x15365)[0x561ea02c6365]
[fv-az1693-957:66836] *** End of error message ***
</pre>
{% endraw %}
