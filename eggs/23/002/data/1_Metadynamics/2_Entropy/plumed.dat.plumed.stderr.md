**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33644] *** Process received signal ***
[runnervmmtnos:33644] Signal: Aborted (6)
[runnervmmtnos:33644] Signal code:  (-6)
[runnervmmtnos:33644] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0515845330]
[runnervmmtnos:33644] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f051589eb2c]
[runnervmmtnos:33644] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f051584527e]
[runnervmmtnos:33644] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05158288ff]
[runnervmmtnos:33644] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0515ca5ff5]
[runnervmmtnos:33644] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0515cbb0da]
[runnervmmtnos:33644] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0515ca5a55]
[runnervmmtnos:33644] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0515ca5a6f]
[runnervmmtnos:33644] [ 8] plumed(+0x146dd)[0x5596daa976dd]
[runnervmmtnos:33644] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f051582a1ca]
[runnervmmtnos:33644] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f051582a28b]
[runnervmmtnos:33644] [11] plumed(+0x15365)[0x5596daa98365]
[runnervmmtnos:33644] *** End of error message ***
</pre>
{% endraw %}
