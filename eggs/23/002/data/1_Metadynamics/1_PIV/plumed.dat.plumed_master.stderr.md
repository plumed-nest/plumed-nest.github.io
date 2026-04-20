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
[runnervmeorf1:06559] *** Process received signal ***
[runnervmeorf1:06559] Signal: Aborted (6)
[runnervmeorf1:06559] Signal code:  (-6)
[runnervmeorf1:06559] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6f9a445330]
[runnervmeorf1:06559] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6f9a49eb2c]
[runnervmeorf1:06559] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6f9a44527e]
[runnervmeorf1:06559] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6f9a4288ff]
[runnervmeorf1:06559] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6f9a8a5ff5]
[runnervmeorf1:06559] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6f9a8bb0da]
[runnervmeorf1:06559] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6f9a8a5a55]
[runnervmeorf1:06559] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6f9a8a5a6f]
[runnervmeorf1:06559] [ 8] plumed_master(+0x146dd)[0x56035720c6dd]
[runnervmeorf1:06559] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6f9a42a1ca]
[runnervmeorf1:06559] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6f9a42a28b]
[runnervmeorf1:06559] [11] plumed_master(+0x15365)[0x56035720d365]
[runnervmeorf1:06559] *** End of error message ***
</pre>
{% endraw %}
