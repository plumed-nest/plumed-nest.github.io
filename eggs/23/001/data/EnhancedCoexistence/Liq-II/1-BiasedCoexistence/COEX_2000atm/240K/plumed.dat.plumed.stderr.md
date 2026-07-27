**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[runnervmvrwv9:06740] *** Process received signal ***
[runnervmvrwv9:06740] Signal: Aborted (6)
[runnervmvrwv9:06740] Signal code:  (-6)
[runnervmvrwv9:06740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd0ab845330]
[runnervmvrwv9:06740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd0ab89eb2c]
[runnervmvrwv9:06740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd0ab84527e]
[runnervmvrwv9:06740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd0ab8288ff]
[runnervmvrwv9:06740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd0abca5ff5]
[runnervmvrwv9:06740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd0abcbb0da]
[runnervmvrwv9:06740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd0abca5a55]
[runnervmvrwv9:06740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd0abca5a6f]
[runnervmvrwv9:06740] [ 8] plumed(+0x146dd)[0x55f78edaa6dd]
[runnervmvrwv9:06740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd0ab82a1ca]
[runnervmvrwv9:06740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd0ab82a28b]
[runnervmvrwv9:06740] [11] plumed(+0x15365)[0x55f78edab365]
[runnervmvrwv9:06740] *** End of error message ***
</pre>
{% endraw %}
