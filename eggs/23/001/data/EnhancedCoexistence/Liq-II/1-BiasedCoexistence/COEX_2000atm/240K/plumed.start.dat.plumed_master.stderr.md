**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmxyh4eaekms:08682] *** Process received signal ***
[pkrvmxyh4eaekms:08682] Signal: Aborted (6)
[pkrvmxyh4eaekms:08682] Signal code:  (-6)
[pkrvmxyh4eaekms:08682] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff241845330]
[pkrvmxyh4eaekms:08682] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff24189eb2c]
[pkrvmxyh4eaekms:08682] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff24184527e]
[pkrvmxyh4eaekms:08682] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2418288ff]
[pkrvmxyh4eaekms:08682] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff241ca5ff5]
[pkrvmxyh4eaekms:08682] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff241cbb0da]
[pkrvmxyh4eaekms:08682] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff241ca5a55]
[pkrvmxyh4eaekms:08682] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff241ca5a6f]
[pkrvmxyh4eaekms:08682] [ 8] plumed_master(+0x146dd)[0x55aadd97b6dd]
[pkrvmxyh4eaekms:08682] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff24182a1ca]
[pkrvmxyh4eaekms:08682] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff24182a28b]
[pkrvmxyh4eaekms:08682] [11] plumed_master(+0x15365)[0x55aadd97c365]
[pkrvmxyh4eaekms:08682] *** End of error message ***
</pre>
{% endraw %}
