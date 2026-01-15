**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:172) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervmi13qx:36947] *** Process received signal ***
[runnervmi13qx:36947] Signal: Aborted (6)
[runnervmi13qx:36947] Signal code:  (-6)
[runnervmi13qx:36947] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4d0845330]
[runnervmi13qx:36947] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4d089eb2c]
[runnervmi13qx:36947] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4d084527e]
[runnervmi13qx:36947] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4d08288ff]
[runnervmi13qx:36947] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4d0ca5ff5]
[runnervmi13qx:36947] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4d0cbb0da]
[runnervmi13qx:36947] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4d0ca5a55]
[runnervmi13qx:36947] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4d0ca5a6f]
[runnervmi13qx:36947] [ 8] plumed_master(+0x146dd)[0x55ed3d1ec6dd]
[runnervmi13qx:36947] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4d082a1ca]
[runnervmi13qx:36947] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4d082a28b]
[runnervmi13qx:36947] [11] plumed_master(+0x15365)[0x55ed3d1ed365]
[runnervmi13qx:36947] *** End of error message ***
</pre>
{% endraw %}
