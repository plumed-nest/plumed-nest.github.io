**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:158) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[pkrvmpptgkbjq6m:12279] *** Process received signal ***
[pkrvmpptgkbjq6m:12279] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12279] Signal code:  (-6)
[pkrvmpptgkbjq6m:12279] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6ce1c45330]
[pkrvmpptgkbjq6m:12279] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6ce1c9eb2c]
[pkrvmpptgkbjq6m:12279] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6ce1c4527e]
[pkrvmpptgkbjq6m:12279] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6ce1c288ff]
[pkrvmpptgkbjq6m:12279] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6ce20a5ff5]
[pkrvmpptgkbjq6m:12279] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6ce20bb0da]
[pkrvmpptgkbjq6m:12279] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6ce20a5a55]
[pkrvmpptgkbjq6m:12279] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6ce20a5a6f]
[pkrvmpptgkbjq6m:12279] [ 8] plumed_master(+0x146dd)[0x55a1e07436dd]
[pkrvmpptgkbjq6m:12279] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6ce1c2a1ca]
[pkrvmpptgkbjq6m:12279] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6ce1c2a28b]
[pkrvmpptgkbjq6m:12279] [11] plumed_master(+0x15365)[0x55a1e0744365]
[pkrvmpptgkbjq6m:12279] *** End of error message ***
</pre>
{% endraw %}
