**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33864] *** Process received signal ***
[runnervmmtnos:33864] Signal: Aborted (6)
[runnervmmtnos:33864] Signal code:  (-6)
[runnervmmtnos:33864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f9d245330]
[runnervmmtnos:33864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f9d29eb2c]
[runnervmmtnos:33864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f9d24527e]
[runnervmmtnos:33864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f9d2288ff]
[runnervmmtnos:33864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f9d6a5ff5]
[runnervmmtnos:33864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f9d6bb0da]
[runnervmmtnos:33864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f9d6a5a55]
[runnervmmtnos:33864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f9d6a5a6f]
[runnervmmtnos:33864] [ 8] plumed_master(+0x146dd)[0x5616289626dd]
[runnervmmtnos:33864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f9d22a1ca]
[runnervmmtnos:33864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f9d22a28b]
[runnervmmtnos:33864] [11] plumed_master(+0x15365)[0x561628963365]
[runnervmmtnos:33864] *** End of error message ***
</pre>
{% endraw %}
