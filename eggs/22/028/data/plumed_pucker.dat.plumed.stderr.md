**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmq0rgcvqdmg:08853] *** Process received signal ***
[pkrvmq0rgcvqdmg:08853] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08853] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08853] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3e13245330]
[pkrvmq0rgcvqdmg:08853] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3e1329eb2c]
[pkrvmq0rgcvqdmg:08853] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3e1324527e]
[pkrvmq0rgcvqdmg:08853] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3e132288ff]
[pkrvmq0rgcvqdmg:08853] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3e136a5ff5]
[pkrvmq0rgcvqdmg:08853] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3e136bb0da]
[pkrvmq0rgcvqdmg:08853] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3e136a5a55]
[pkrvmq0rgcvqdmg:08853] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3e136a5a6f]
[pkrvmq0rgcvqdmg:08853] [ 8] plumed(+0x146dd)[0x55ff848de6dd]
[pkrvmq0rgcvqdmg:08853] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3e1322a1ca]
[pkrvmq0rgcvqdmg:08853] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3e1322a28b]
[pkrvmq0rgcvqdmg:08853] [11] plumed(+0x15365)[0x55ff848df365]
[pkrvmq0rgcvqdmg:08853] *** End of error message ***
</pre>
{% endraw %}
