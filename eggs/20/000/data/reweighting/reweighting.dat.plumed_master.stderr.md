**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:10258] *** Process received signal ***
[runnervm76f27:10258] Signal: Aborted (6)
[runnervm76f27:10258] Signal code:  (-6)
[runnervm76f27:10258] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5adc845330]
[runnervm76f27:10258] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5adc89ec0c]
[runnervm76f27:10258] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5adc84527e]
[runnervm76f27:10258] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5adc8288ff]
[runnervm76f27:10258] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5adcca5ff5]
[runnervm76f27:10258] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5adccbb0da]
[runnervm76f27:10258] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5adcca5a55]
[runnervm76f27:10258] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5adcca5a6f]
[runnervm76f27:10258] [ 8] plumed_master(+0x146dd)[0x564659a7d6dd]
[runnervm76f27:10258] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5adc82a1ca]
[runnervm76f27:10258] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5adc82a28b]
[runnervm76f27:10258] [11] plumed_master(+0x15365)[0x564659a7e365]
[runnervm76f27:10258] *** End of error message ***
</pre>
{% endraw %}
