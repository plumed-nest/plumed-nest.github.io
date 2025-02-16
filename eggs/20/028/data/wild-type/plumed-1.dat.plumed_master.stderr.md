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
[fv-az1781-845:64265] *** Process received signal ***
[fv-az1781-845:64265] Signal: Aborted (6)
[fv-az1781-845:64265] Signal code:  (-6)
[fv-az1781-845:64265] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2db5a45330]
[fv-az1781-845:64265] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2db5a9eb2c]
[fv-az1781-845:64265] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2db5a4527e]
[fv-az1781-845:64265] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2db5a288ff]
[fv-az1781-845:64265] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2db5ea5ff5]
[fv-az1781-845:64265] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2db5ebb0da]
[fv-az1781-845:64265] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2db5ea5a55]
[fv-az1781-845:64265] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2db5ea5a6f]
[fv-az1781-845:64265] [ 8] plumed_master(+0x146dd)[0x5611e978a6dd]
[fv-az1781-845:64265] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2db5a2a1ca]
[fv-az1781-845:64265] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2db5a2a28b]
[fv-az1781-845:64265] [11] plumed_master(+0x15365)[0x5611e978b365]
[fv-az1781-845:64265] *** End of error message ***
</pre>
{% endraw %}
