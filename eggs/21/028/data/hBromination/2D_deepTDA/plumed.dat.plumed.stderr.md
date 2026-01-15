**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmi13qx:35469] *** Process received signal ***
[runnervmi13qx:35469] Signal: Aborted (6)
[runnervmi13qx:35469] Signal code:  (-6)
[runnervmi13qx:35469] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcc0a645330]
[runnervmi13qx:35469] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcc0a69eb2c]
[runnervmi13qx:35469] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcc0a64527e]
[runnervmi13qx:35469] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcc0a6288ff]
[runnervmi13qx:35469] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcc0aaa5ff5]
[runnervmi13qx:35469] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcc0aabb0da]
[runnervmi13qx:35469] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcc0aaa5a55]
[runnervmi13qx:35469] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcc0aaa5a6f]
[runnervmi13qx:35469] [ 8] plumed(+0x146dd)[0x55b3ce5726dd]
[runnervmi13qx:35469] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcc0a62a1ca]
[runnervmi13qx:35469] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcc0a62a28b]
[runnervmi13qx:35469] [11] plumed(+0x15365)[0x55b3ce573365]
[runnervmi13qx:35469] *** End of error message ***
</pre>
{% endraw %}
