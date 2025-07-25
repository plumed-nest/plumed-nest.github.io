**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:158) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[pkrvmpptgkbjq6m:12330] *** Process received signal ***
[pkrvmpptgkbjq6m:12330] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12330] Signal code:  (-6)
[pkrvmpptgkbjq6m:12330] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7effd9445330]
[pkrvmpptgkbjq6m:12330] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7effd949eb2c]
[pkrvmpptgkbjq6m:12330] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7effd944527e]
[pkrvmpptgkbjq6m:12330] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7effd94288ff]
[pkrvmpptgkbjq6m:12330] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7effd98a5ff5]
[pkrvmpptgkbjq6m:12330] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7effd98bb0da]
[pkrvmpptgkbjq6m:12330] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7effd98a5a55]
[pkrvmpptgkbjq6m:12330] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7effd98a5a6f]
[pkrvmpptgkbjq6m:12330] [ 8] plumed_master(+0x146dd)[0x559000e146dd]
[pkrvmpptgkbjq6m:12330] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7effd942a1ca]
[pkrvmpptgkbjq6m:12330] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7effd942a28b]
[pkrvmpptgkbjq6m:12330] [11] plumed_master(+0x15365)[0x559000e15365]
[pkrvmpptgkbjq6m:12330] *** End of error message ***
</pre>
{% endraw %}
