**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmeorf1:06851] *** Process received signal ***
[runnervmeorf1:06851] Signal: Aborted (6)
[runnervmeorf1:06851] Signal code:  (-6)
[runnervmeorf1:06851] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd11de45330]
[runnervmeorf1:06851] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd11de9eb2c]
[runnervmeorf1:06851] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd11de4527e]
[runnervmeorf1:06851] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd11de288ff]
[runnervmeorf1:06851] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd11e2a5ff5]
[runnervmeorf1:06851] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd11e2bb0da]
[runnervmeorf1:06851] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd11e2a5a55]
[runnervmeorf1:06851] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd11e2a5a6f]
[runnervmeorf1:06851] [ 8] plumed(+0x146dd)[0x55b102bdd6dd]
[runnervmeorf1:06851] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd11de2a1ca]
[runnervmeorf1:06851] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd11de2a28b]
[runnervmeorf1:06851] [11] plumed(+0x15365)[0x55b102bde365]
[runnervmeorf1:06851] *** End of error message ***
</pre>
{% endraw %}
