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
[pkrvmxyh4eaekms:08198] *** Process received signal ***
[pkrvmxyh4eaekms:08198] Signal: Aborted (6)
[pkrvmxyh4eaekms:08198] Signal code:  (-6)
[pkrvmxyh4eaekms:08198] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8835c45330]
[pkrvmxyh4eaekms:08198] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8835c9eb2c]
[pkrvmxyh4eaekms:08198] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8835c4527e]
[pkrvmxyh4eaekms:08198] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8835c288ff]
[pkrvmxyh4eaekms:08198] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88360a5ff5]
[pkrvmxyh4eaekms:08198] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88360bb0da]
[pkrvmxyh4eaekms:08198] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88360a5a55]
[pkrvmxyh4eaekms:08198] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88360a5a6f]
[pkrvmxyh4eaekms:08198] [ 8] plumed(+0x146dd)[0x5646c14a96dd]
[pkrvmxyh4eaekms:08198] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8835c2a1ca]
[pkrvmxyh4eaekms:08198] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8835c2a28b]
[pkrvmxyh4eaekms:08198] [11] plumed(+0x15365)[0x5646c14aa365]
[pkrvmxyh4eaekms:08198] *** End of error message ***
</pre>
{% endraw %}
