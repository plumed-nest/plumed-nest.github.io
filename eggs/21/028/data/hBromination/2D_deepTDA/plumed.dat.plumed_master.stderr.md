**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmmklqx:07546] *** Process received signal ***
[runnervmmklqx:07546] Signal: Aborted (6)
[runnervmmklqx:07546] Signal code:  (-6)
[runnervmmklqx:07546] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4bcf245330]
[runnervmmklqx:07546] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4bcf29eb2c]
[runnervmmklqx:07546] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4bcf24527e]
[runnervmmklqx:07546] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4bcf2288ff]
[runnervmmklqx:07546] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4bcf6a5ff5]
[runnervmmklqx:07546] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4bcf6bb0da]
[runnervmmklqx:07546] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4bcf6a5a55]
[runnervmmklqx:07546] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4bcf6a5a6f]
[runnervmmklqx:07546] [ 8] plumed_master(+0x146dd)[0x55f9374656dd]
[runnervmmklqx:07546] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4bcf22a1ca]
[runnervmmklqx:07546] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4bcf22a28b]
[runnervmmklqx:07546] [11] plumed_master(+0x15365)[0x55f937466365]
[runnervmmklqx:07546] *** End of error message ***
</pre>
{% endraw %}
