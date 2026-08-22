**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervm76f27:09049] *** Process received signal ***
[runnervm76f27:09049] Signal: Aborted (6)
[runnervm76f27:09049] Signal code:  (-6)
[runnervm76f27:09049] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3861a45330]
[runnervm76f27:09049] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3861a9ec0c]
[runnervm76f27:09049] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3861a4527e]
[runnervm76f27:09049] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3861a288ff]
[runnervm76f27:09049] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3861ea5ff5]
[runnervm76f27:09049] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3861ebb0da]
[runnervm76f27:09049] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3861ea5a55]
[runnervm76f27:09049] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3861ea5a6f]
[runnervm76f27:09049] [ 8] plumed_master(+0x146dd)[0x55eb5619c6dd]
[runnervm76f27:09049] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3861a2a1ca]
[runnervm76f27:09049] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3861a2a28b]
[runnervm76f27:09049] [11] plumed_master(+0x15365)[0x55eb5619d365]
[runnervm76f27:09049] *** End of error message ***
</pre>
{% endraw %}
