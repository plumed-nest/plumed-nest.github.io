**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervm76f27:07088] *** Process received signal ***
[runnervm76f27:07088] Signal: Aborted (6)
[runnervm76f27:07088] Signal code:  (-6)
[runnervm76f27:07088] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e09645330]
[runnervm76f27:07088] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e0969ec0c]
[runnervm76f27:07088] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e0964527e]
[runnervm76f27:07088] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e096288ff]
[runnervm76f27:07088] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e09aa5ff5]
[runnervm76f27:07088] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e09abb0da]
[runnervm76f27:07088] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e09aa5a55]
[runnervm76f27:07088] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e09aa5a6f]
[runnervm76f27:07088] [ 8] plumed_master(+0x146dd)[0x56191d6c26dd]
[runnervm76f27:07088] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e0962a1ca]
[runnervm76f27:07088] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e0962a28b]
[runnervm76f27:07088] [11] plumed_master(+0x15365)[0x56191d6c3365]
[runnervm76f27:07088] *** End of error message ***
</pre>
{% endraw %}
