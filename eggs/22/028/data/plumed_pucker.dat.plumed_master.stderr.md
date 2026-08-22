**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervm76f27:06984] *** Process received signal ***
[runnervm76f27:06984] Signal: Aborted (6)
[runnervm76f27:06984] Signal code:  (-6)
[runnervm76f27:06984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7cbbe45330]
[runnervm76f27:06984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7cbbe9ec0c]
[runnervm76f27:06984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7cbbe4527e]
[runnervm76f27:06984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7cbbe288ff]
[runnervm76f27:06984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7cbc2a5ff5]
[runnervm76f27:06984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7cbc2bb0da]
[runnervm76f27:06984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7cbc2a5a55]
[runnervm76f27:06984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7cbc2a5a6f]
[runnervm76f27:06984] [ 8] plumed_master(+0x146dd)[0x55f50fac56dd]
[runnervm76f27:06984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7cbbe2a1ca]
[runnervm76f27:06984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7cbbe2a28b]
[runnervm76f27:06984] [11] plumed_master(+0x15365)[0x55f50fac6365]
[runnervm76f27:06984] *** End of error message ***
</pre>
{% endraw %}
