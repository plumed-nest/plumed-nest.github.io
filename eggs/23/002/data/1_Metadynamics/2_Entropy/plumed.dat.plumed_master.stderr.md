**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmklqx:06433] *** Process received signal ***
[runnervmmklqx:06433] Signal: Aborted (6)
[runnervmmklqx:06433] Signal code:  (-6)
[runnervmmklqx:06433] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f136a245330]
[runnervmmklqx:06433] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f136a29eb2c]
[runnervmmklqx:06433] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f136a24527e]
[runnervmmklqx:06433] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f136a2288ff]
[runnervmmklqx:06433] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f136a6a5ff5]
[runnervmmklqx:06433] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f136a6bb0da]
[runnervmmklqx:06433] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f136a6a5a55]
[runnervmmklqx:06433] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f136a6a5a6f]
[runnervmmklqx:06433] [ 8] plumed_master(+0x146dd)[0x556a4e8956dd]
[runnervmmklqx:06433] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f136a22a1ca]
[runnervmmklqx:06433] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f136a22a28b]
[runnervmmklqx:06433] [11] plumed_master(+0x15365)[0x556a4e896365]
[runnervmmklqx:06433] *** End of error message ***
</pre>
{% endraw %}
