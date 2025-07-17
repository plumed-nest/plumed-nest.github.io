**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:06600] *** Process received signal ***
[pkrvmq0rgcvqdmg:06600] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06600] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06600] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4de9e45330]
[pkrvmq0rgcvqdmg:06600] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4de9e9eb2c]
[pkrvmq0rgcvqdmg:06600] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4de9e4527e]
[pkrvmq0rgcvqdmg:06600] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4de9e288ff]
[pkrvmq0rgcvqdmg:06600] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4dea2a5ff5]
[pkrvmq0rgcvqdmg:06600] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4dea2bb0da]
[pkrvmq0rgcvqdmg:06600] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4dea2a5a55]
[pkrvmq0rgcvqdmg:06600] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4dea2a5a6f]
[pkrvmq0rgcvqdmg:06600] [ 8] plumed_master(+0x146dd)[0x5586cb30f6dd]
[pkrvmq0rgcvqdmg:06600] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4de9e2a1ca]
[pkrvmq0rgcvqdmg:06600] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4de9e2a28b]
[pkrvmq0rgcvqdmg:06600] [11] plumed_master(+0x15365)[0x5586cb310365]
[pkrvmq0rgcvqdmg:06600] *** End of error message ***
</pre>
{% endraw %}
