**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervm76f27:07493] *** Process received signal ***
[runnervm76f27:07493] Signal: Aborted (6)
[runnervm76f27:07493] Signal code:  (-6)
[runnervm76f27:07493] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f32c5a45330]
[runnervm76f27:07493] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f32c5a9ec0c]
[runnervm76f27:07493] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f32c5a4527e]
[runnervm76f27:07493] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f32c5a288ff]
[runnervm76f27:07493] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32c5ea5ff5]
[runnervm76f27:07493] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32c5ebb0da]
[runnervm76f27:07493] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32c5ea5a55]
[runnervm76f27:07493] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32c5ea5a6f]
[runnervm76f27:07493] [ 8] plumed(+0x146dd)[0x55eb059536dd]
[runnervm76f27:07493] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f32c5a2a1ca]
[runnervm76f27:07493] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f32c5a2a28b]
[runnervm76f27:07493] [11] plumed(+0x15365)[0x55eb05954365]
[runnervm76f27:07493] *** End of error message ***
</pre>
{% endraw %}
