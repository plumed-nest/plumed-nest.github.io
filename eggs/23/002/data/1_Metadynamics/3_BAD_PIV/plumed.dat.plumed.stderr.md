**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmxyh4eaekms:08250] *** Process received signal ***
[pkrvmxyh4eaekms:08250] Signal: Aborted (6)
[pkrvmxyh4eaekms:08250] Signal code:  (-6)
[pkrvmxyh4eaekms:08250] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf17445330]
[pkrvmxyh4eaekms:08250] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf1749eb2c]
[pkrvmxyh4eaekms:08250] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf1744527e]
[pkrvmxyh4eaekms:08250] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf174288ff]
[pkrvmxyh4eaekms:08250] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf178a5ff5]
[pkrvmxyh4eaekms:08250] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf178bb0da]
[pkrvmxyh4eaekms:08250] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf178a5a55]
[pkrvmxyh4eaekms:08250] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf178a5a6f]
[pkrvmxyh4eaekms:08250] [ 8] plumed(+0x146dd)[0x5621613186dd]
[pkrvmxyh4eaekms:08250] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf1742a1ca]
[pkrvmxyh4eaekms:08250] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf1742a28b]
[pkrvmxyh4eaekms:08250] [11] plumed(+0x15365)[0x562161319365]
[pkrvmxyh4eaekms:08250] *** End of error message ***
</pre>
{% endraw %}
