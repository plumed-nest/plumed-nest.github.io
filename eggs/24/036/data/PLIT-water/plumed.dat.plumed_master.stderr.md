**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmi13qx:33458] *** Process received signal ***
[runnervmi13qx:33458] Signal: Aborted (6)
[runnervmi13qx:33458] Signal code:  (-6)
[runnervmi13qx:33458] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feeb1645330]
[runnervmi13qx:33458] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feeb169eb2c]
[runnervmi13qx:33458] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feeb164527e]
[runnervmi13qx:33458] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feeb16288ff]
[runnervmi13qx:33458] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feeb1aa5ff5]
[runnervmi13qx:33458] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feeb1abb0da]
[runnervmi13qx:33458] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feeb1aa5a55]
[runnervmi13qx:33458] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feeb1aa5a6f]
[runnervmi13qx:33458] [ 8] plumed_master(+0x146dd)[0x559a312386dd]
[runnervmi13qx:33458] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feeb162a1ca]
[runnervmi13qx:33458] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feeb162a28b]
[runnervmi13qx:33458] [11] plumed_master(+0x15365)[0x559a31239365]
[runnervmi13qx:33458] *** End of error message ***
</pre>
{% endraw %}
