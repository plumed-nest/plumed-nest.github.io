**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[pkrvmq0rgcvqdmg:07260] *** Process received signal ***
[pkrvmq0rgcvqdmg:07260] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07260] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb67ec45330]
[pkrvmq0rgcvqdmg:07260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb67ec9eb2c]
[pkrvmq0rgcvqdmg:07260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb67ec4527e]
[pkrvmq0rgcvqdmg:07260] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb67ec288ff]
[pkrvmq0rgcvqdmg:07260] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb67f0a5ff5]
[pkrvmq0rgcvqdmg:07260] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb67f0bb0da]
[pkrvmq0rgcvqdmg:07260] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb67f0a5a55]
[pkrvmq0rgcvqdmg:07260] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb67f0a5a6f]
[pkrvmq0rgcvqdmg:07260] [ 8] plumed(+0x146dd)[0x55a2cf6fe6dd]
[pkrvmq0rgcvqdmg:07260] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb67ec2a1ca]
[pkrvmq0rgcvqdmg:07260] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb67ec2a28b]
[pkrvmq0rgcvqdmg:07260] [11] plumed(+0x15365)[0x55a2cf6ff365]
[pkrvmq0rgcvqdmg:07260] *** End of error message ***
</pre>
{% endraw %}
