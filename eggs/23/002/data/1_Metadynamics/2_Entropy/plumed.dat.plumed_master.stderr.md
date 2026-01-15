**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33660] *** Process received signal ***
[runnervmmtnos:33660] Signal: Aborted (6)
[runnervmmtnos:33660] Signal code:  (-6)
[runnervmmtnos:33660] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0cd7245330]
[runnervmmtnos:33660] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0cd729eb2c]
[runnervmmtnos:33660] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0cd724527e]
[runnervmmtnos:33660] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0cd72288ff]
[runnervmmtnos:33660] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0cd76a5ff5]
[runnervmmtnos:33660] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0cd76bb0da]
[runnervmmtnos:33660] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0cd76a5a55]
[runnervmmtnos:33660] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0cd76a5a6f]
[runnervmmtnos:33660] [ 8] plumed_master(+0x146dd)[0x55de52a846dd]
[runnervmmtnos:33660] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0cd722a1ca]
[runnervmmtnos:33660] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0cd722a28b]
[runnervmmtnos:33660] [11] plumed_master(+0x15365)[0x55de52a85365]
[runnervmmtnos:33660] *** End of error message ***
</pre>
{% endraw %}
