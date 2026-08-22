**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervm76f27:07509] *** Process received signal ***
[runnervm76f27:07509] Signal: Aborted (6)
[runnervm76f27:07509] Signal code:  (-6)
[runnervm76f27:07509] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f963f245330]
[runnervm76f27:07509] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f963f29ec0c]
[runnervm76f27:07509] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f963f24527e]
[runnervm76f27:07509] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f963f2288ff]
[runnervm76f27:07509] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f963f6a5ff5]
[runnervm76f27:07509] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f963f6bb0da]
[runnervm76f27:07509] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f963f6a5a55]
[runnervm76f27:07509] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f963f6a5a6f]
[runnervm76f27:07509] [ 8] plumed_master(+0x146dd)[0x5561977366dd]
[runnervm76f27:07509] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f963f22a1ca]
[runnervm76f27:07509] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f963f22a28b]
[runnervm76f27:07509] [11] plumed_master(+0x15365)[0x556197737365]
[runnervm76f27:07509] *** End of error message ***
</pre>
{% endraw %}
