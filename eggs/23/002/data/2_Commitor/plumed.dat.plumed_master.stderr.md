**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmeorf1:06765] *** Process received signal ***
[runnervmeorf1:06765] Signal: Aborted (6)
[runnervmeorf1:06765] Signal code:  (-6)
[runnervmeorf1:06765] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff17d845330]
[runnervmeorf1:06765] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff17d89eb2c]
[runnervmeorf1:06765] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff17d84527e]
[runnervmeorf1:06765] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff17d8288ff]
[runnervmeorf1:06765] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff17dca5ff5]
[runnervmeorf1:06765] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff17dcbb0da]
[runnervmeorf1:06765] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff17dca5a55]
[runnervmeorf1:06765] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff17dca5a6f]
[runnervmeorf1:06765] [ 8] plumed_master(+0x146dd)[0x55f9ba0296dd]
[runnervmeorf1:06765] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff17d82a1ca]
[runnervmeorf1:06765] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff17d82a28b]
[runnervmeorf1:06765] [11] plumed_master(+0x15365)[0x55f9ba02a365]
[runnervmeorf1:06765] *** End of error message ***
</pre>
{% endraw %}
