**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmklqx:06572] *** Process received signal ***
[runnervmmklqx:06572] Signal: Aborted (6)
[runnervmmklqx:06572] Signal code:  (-6)
[runnervmmklqx:06572] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5372445330]
[runnervmmklqx:06572] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f537249eb2c]
[runnervmmklqx:06572] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f537244527e]
[runnervmmklqx:06572] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53724288ff]
[runnervmmklqx:06572] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53728a5ff5]
[runnervmmklqx:06572] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53728bb0da]
[runnervmmklqx:06572] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53728a5a55]
[runnervmmklqx:06572] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53728a5a6f]
[runnervmmklqx:06572] [ 8] plumed(+0x146dd)[0x55c81fed76dd]
[runnervmmklqx:06572] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f537242a1ca]
[runnervmmklqx:06572] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f537242a28b]
[runnervmmklqx:06572] [11] plumed(+0x15365)[0x55c81fed8365]
[runnervmmklqx:06572] *** End of error message ***
</pre>
{% endraw %}
