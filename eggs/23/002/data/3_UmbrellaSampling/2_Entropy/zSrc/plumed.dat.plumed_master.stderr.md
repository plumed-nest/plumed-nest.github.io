**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33917] *** Process received signal ***
[runnervmmtnos:33917] Signal: Aborted (6)
[runnervmmtnos:33917] Signal code:  (-6)
[runnervmmtnos:33917] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3607845330]
[runnervmmtnos:33917] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f360789eb2c]
[runnervmmtnos:33917] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f360784527e]
[runnervmmtnos:33917] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36078288ff]
[runnervmmtnos:33917] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3607ca5ff5]
[runnervmmtnos:33917] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3607cbb0da]
[runnervmmtnos:33917] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3607ca5a55]
[runnervmmtnos:33917] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3607ca5a6f]
[runnervmmtnos:33917] [ 8] plumed_master(+0x146dd)[0x55b414f826dd]
[runnervmmtnos:33917] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f360782a1ca]
[runnervmmtnos:33917] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f360782a28b]
[runnervmmtnos:33917] [11] plumed_master(+0x15365)[0x55b414f83365]
[runnervmmtnos:33917] *** End of error message ***
</pre>
{% endraw %}
