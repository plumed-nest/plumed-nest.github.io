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
[fv-az1341-704:65386] *** Process received signal ***
[fv-az1341-704:65386] Signal: Aborted (6)
[fv-az1341-704:65386] Signal code:  (-6)
[fv-az1341-704:65386] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f95a0045330]
[fv-az1341-704:65386] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f95a009eb2c]
[fv-az1341-704:65386] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f95a004527e]
[fv-az1341-704:65386] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95a00288ff]
[fv-az1341-704:65386] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95a04a5ff5]
[fv-az1341-704:65386] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95a04bb0da]
[fv-az1341-704:65386] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95a04a5a55]
[fv-az1341-704:65386] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95a04a5a6f]
[fv-az1341-704:65386] [ 8] plumed_master(+0x146dd)[0x56315e9af6dd]
[fv-az1341-704:65386] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f95a002a1ca]
[fv-az1341-704:65386] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f95a002a28b]
[fv-az1341-704:65386] [11] plumed_master(+0x15365)[0x56315e9b0365]
[fv-az1341-704:65386] *** End of error message ***
</pre>
{% endraw %}
