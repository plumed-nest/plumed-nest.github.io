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
[pkrvmxyh4eaekms:08146] *** Process received signal ***
[pkrvmxyh4eaekms:08146] Signal: Aborted (6)
[pkrvmxyh4eaekms:08146] Signal code:  (-6)
[pkrvmxyh4eaekms:08146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8862645330]
[pkrvmxyh4eaekms:08146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f886269eb2c]
[pkrvmxyh4eaekms:08146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f886264527e]
[pkrvmxyh4eaekms:08146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88626288ff]
[pkrvmxyh4eaekms:08146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8862aa5ff5]
[pkrvmxyh4eaekms:08146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8862abb0da]
[pkrvmxyh4eaekms:08146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8862aa5a55]
[pkrvmxyh4eaekms:08146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8862aa5a6f]
[pkrvmxyh4eaekms:08146] [ 8] plumed(+0x146dd)[0x55c44e1296dd]
[pkrvmxyh4eaekms:08146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f886262a1ca]
[pkrvmxyh4eaekms:08146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f886262a28b]
[pkrvmxyh4eaekms:08146] [11] plumed(+0x15365)[0x55c44e12a365]
[pkrvmxyh4eaekms:08146] *** End of error message ***
</pre>
{% endraw %}
