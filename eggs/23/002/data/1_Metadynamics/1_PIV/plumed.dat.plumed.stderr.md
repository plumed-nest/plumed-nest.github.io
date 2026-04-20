**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmeorf1:06543] *** Process received signal ***
[runnervmeorf1:06543] Signal: Aborted (6)
[runnervmeorf1:06543] Signal code:  (-6)
[runnervmeorf1:06543] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd446045330]
[runnervmeorf1:06543] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd44609eb2c]
[runnervmeorf1:06543] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd44604527e]
[runnervmeorf1:06543] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4460288ff]
[runnervmeorf1:06543] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4464a5ff5]
[runnervmeorf1:06543] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4464bb0da]
[runnervmeorf1:06543] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4464a5a55]
[runnervmeorf1:06543] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4464a5a6f]
[runnervmeorf1:06543] [ 8] plumed(+0x146dd)[0x55a5da6776dd]
[runnervmeorf1:06543] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd44602a1ca]
[runnervmeorf1:06543] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd44602a28b]
[runnervmeorf1:06543] [11] plumed(+0x15365)[0x55a5da678365]
[runnervmeorf1:06543] *** End of error message ***
</pre>
{% endraw %}
