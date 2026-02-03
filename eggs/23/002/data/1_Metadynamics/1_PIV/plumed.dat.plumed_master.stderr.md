**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmkj6or:06369] *** Process received signal ***
[runnervmkj6or:06369] Signal: Aborted (6)
[runnervmkj6or:06369] Signal code:  (-6)
[runnervmkj6or:06369] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7eff0a445330]
[runnervmkj6or:06369] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7eff0a49eb2c]
[runnervmkj6or:06369] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7eff0a44527e]
[runnervmkj6or:06369] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7eff0a4288ff]
[runnervmkj6or:06369] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7eff0a8a5ff5]
[runnervmkj6or:06369] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7eff0a8bb0da]
[runnervmkj6or:06369] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7eff0a8a5a55]
[runnervmkj6or:06369] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7eff0a8a5a6f]
[runnervmkj6or:06369] [ 8] plumed_master(+0x146dd)[0x564d7cec46dd]
[runnervmkj6or:06369] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7eff0a42a1ca]
[runnervmkj6or:06369] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7eff0a42a28b]
[runnervmkj6or:06369] [11] plumed_master(+0x15365)[0x564d7cec5365]
[runnervmkj6or:06369] *** End of error message ***
</pre>
{% endraw %}
