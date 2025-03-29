**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[fv-az789-879:68001] *** Process received signal ***
[fv-az789-879:68001] Signal: Aborted (6)
[fv-az789-879:68001] Signal code:  (-6)
[fv-az789-879:68001] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d49245330]
[fv-az789-879:68001] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d4929eb2c]
[fv-az789-879:68001] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d4924527e]
[fv-az789-879:68001] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d492288ff]
[fv-az789-879:68001] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d496a5ff5]
[fv-az789-879:68001] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d496bb0da]
[fv-az789-879:68001] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d496a5a55]
[fv-az789-879:68001] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d496a5a6f]
[fv-az789-879:68001] [ 8] plumed_master(+0x146dd)[0x55b0bd4606dd]
[fv-az789-879:68001] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d4922a1ca]
[fv-az789-879:68001] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d4922a28b]
[fv-az789-879:68001] [11] plumed_master(+0x15365)[0x55b0bd461365]
[fv-az789-879:68001] *** End of error message ***
</pre>
{% endraw %}
