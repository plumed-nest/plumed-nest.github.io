**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[fv-az1444-322:10783] *** Process received signal ***
[fv-az1444-322:10783] Signal: Aborted (6)
[fv-az1444-322:10783] Signal code:  (-6)
[fv-az1444-322:10783] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f89e3045330]
[fv-az1444-322:10783] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f89e309eb2c]
[fv-az1444-322:10783] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f89e304527e]
[fv-az1444-322:10783] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f89e30288ff]
[fv-az1444-322:10783] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f89e34a5ff5]
[fv-az1444-322:10783] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f89e34bb0da]
[fv-az1444-322:10783] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f89e34a5a55]
[fv-az1444-322:10783] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f89e34a5a6f]
[fv-az1444-322:10783] [ 8] plumed_master(+0x146dd)[0x55b2724c16dd]
[fv-az1444-322:10783] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f89e302a1ca]
[fv-az1444-322:10783] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f89e302a28b]
[fv-az1444-322:10783] [11] plumed_master(+0x15365)[0x55b2724c2365]
[fv-az1444-322:10783] *** End of error message ***
</pre>
{% endraw %}
