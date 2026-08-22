**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervm76f27:07126] *** Process received signal ***
[runnervm76f27:07126] Signal: Aborted (6)
[runnervm76f27:07126] Signal code:  (-6)
[runnervm76f27:07126] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f22d7845330]
[runnervm76f27:07126] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f22d789ec0c]
[runnervm76f27:07126] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f22d784527e]
[runnervm76f27:07126] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22d78288ff]
[runnervm76f27:07126] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f22d7ca5ff5]
[runnervm76f27:07126] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f22d7cbb0da]
[runnervm76f27:07126] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f22d7ca5a55]
[runnervm76f27:07126] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f22d7ca5a6f]
[runnervm76f27:07126] [ 8] plumed_master(+0x146dd)[0x560f774006dd]
[runnervm76f27:07126] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f22d782a1ca]
[runnervm76f27:07126] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f22d782a28b]
[runnervm76f27:07126] [11] plumed_master(+0x15365)[0x560f77401365]
[runnervm76f27:07126] *** End of error message ***
</pre>
{% endraw %}
