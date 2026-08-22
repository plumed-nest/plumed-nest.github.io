**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervm76f27:04786] *** Process received signal ***
[runnervm76f27:04786] Signal: Aborted (6)
[runnervm76f27:04786] Signal code:  (-6)
[runnervm76f27:04786] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5792e45330]
[runnervm76f27:04786] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5792e9ec0c]
[runnervm76f27:04786] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5792e4527e]
[runnervm76f27:04786] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5792e288ff]
[runnervm76f27:04786] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f57932a5ff5]
[runnervm76f27:04786] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f57932bb0da]
[runnervm76f27:04786] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f57932a5a55]
[runnervm76f27:04786] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f57932a5a6f]
[runnervm76f27:04786] [ 8] plumed_master(+0x146dd)[0x5609e01a76dd]
[runnervm76f27:04786] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5792e2a1ca]
[runnervm76f27:04786] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5792e2a28b]
[runnervm76f27:04786] [11] plumed_master(+0x15365)[0x5609e01a8365]
[runnervm76f27:04786] *** End of error message ***
</pre>
{% endraw %}
