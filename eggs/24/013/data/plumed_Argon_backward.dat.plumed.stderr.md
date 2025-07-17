**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmq0rgcvqdmg:06889] *** Process received signal ***
[pkrvmq0rgcvqdmg:06889] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06889] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06889] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4049645330]
[pkrvmq0rgcvqdmg:06889] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f404969eb2c]
[pkrvmq0rgcvqdmg:06889] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f404964527e]
[pkrvmq0rgcvqdmg:06889] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40496288ff]
[pkrvmq0rgcvqdmg:06889] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4049aa5ff5]
[pkrvmq0rgcvqdmg:06889] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4049abb0da]
[pkrvmq0rgcvqdmg:06889] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4049aa5a55]
[pkrvmq0rgcvqdmg:06889] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4049aa5a6f]
[pkrvmq0rgcvqdmg:06889] [ 8] plumed(+0x146dd)[0x55ee629956dd]
[pkrvmq0rgcvqdmg:06889] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f404962a1ca]
[pkrvmq0rgcvqdmg:06889] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f404962a28b]
[pkrvmq0rgcvqdmg:06889] [11] plumed(+0x15365)[0x55ee62996365]
[pkrvmq0rgcvqdmg:06889] *** End of error message ***
</pre>
{% endraw %}
