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
[fv-az789-879:68053] *** Process received signal ***
[fv-az789-879:68053] Signal: Aborted (6)
[fv-az789-879:68053] Signal code:  (-6)
[fv-az789-879:68053] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f385fc45330]
[fv-az789-879:68053] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f385fc9eb2c]
[fv-az789-879:68053] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f385fc4527e]
[fv-az789-879:68053] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f385fc288ff]
[fv-az789-879:68053] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f38600a5ff5]
[fv-az789-879:68053] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f38600bb0da]
[fv-az789-879:68053] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f38600a5a55]
[fv-az789-879:68053] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f38600a5a6f]
[fv-az789-879:68053] [ 8] plumed_master(+0x146dd)[0x55a03d4216dd]
[fv-az789-879:68053] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f385fc2a1ca]
[fv-az789-879:68053] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f385fc2a28b]
[fv-az789-879:68053] [11] plumed_master(+0x15365)[0x55a03d422365]
[fv-az789-879:68053] *** End of error message ***
</pre>
{% endraw %}
