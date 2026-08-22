**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s31 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:10542] *** Process received signal ***
[runnervm76f27:10542] Signal: Aborted (6)
[runnervm76f27:10542] Signal code:  (-6)
[runnervm76f27:10542] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9246845330]
[runnervm76f27:10542] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f924689ec0c]
[runnervm76f27:10542] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f924684527e]
[runnervm76f27:10542] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f92468288ff]
[runnervm76f27:10542] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9246ca5ff5]
[runnervm76f27:10542] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9246cbb0da]
[runnervm76f27:10542] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9246ca5a55]
[runnervm76f27:10542] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9246ca5a6f]
[runnervm76f27:10542] [ 8] plumed_master(+0x146dd)[0x55d502e0d6dd]
[runnervm76f27:10542] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f924682a1ca]
[runnervm76f27:10542] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f924682a28b]
[runnervm76f27:10542] [11] plumed_master(+0x15365)[0x55d502e0e365]
[runnervm76f27:10542] *** End of error message ***
</pre>
{% endraw %}
