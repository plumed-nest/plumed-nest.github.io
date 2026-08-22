**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervm76f27:07559] *** Process received signal ***
[runnervm76f27:07559] Signal: Aborted (6)
[runnervm76f27:07559] Signal code:  (-6)
[runnervm76f27:07559] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6977045330]
[runnervm76f27:07559] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f697709ec0c]
[runnervm76f27:07559] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f697704527e]
[runnervm76f27:07559] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f69770288ff]
[runnervm76f27:07559] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69774a5ff5]
[runnervm76f27:07559] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69774bb0da]
[runnervm76f27:07559] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69774a5a55]
[runnervm76f27:07559] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69774a5a6f]
[runnervm76f27:07559] [ 8] plumed_master(+0x146dd)[0x555c314056dd]
[runnervm76f27:07559] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f697702a1ca]
[runnervm76f27:07559] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f697702a28b]
[runnervm76f27:07559] [11] plumed_master(+0x15365)[0x555c31406365]
[runnervm76f27:07559] *** End of error message ***
</pre>
{% endraw %}
