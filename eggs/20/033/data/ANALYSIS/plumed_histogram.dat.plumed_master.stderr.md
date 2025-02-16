**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @30 : keyword ARG is compulsory for this action
[fv-az1939-440:65784] *** Process received signal ***
[fv-az1939-440:65784] Signal: Aborted (6)
[fv-az1939-440:65784] Signal code:  (-6)
[fv-az1939-440:65784] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1ab1a45330]
[fv-az1939-440:65784] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1ab1a9eb2c]
[fv-az1939-440:65784] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1ab1a4527e]
[fv-az1939-440:65784] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1ab1a288ff]
[fv-az1939-440:65784] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ab1ea5ff5]
[fv-az1939-440:65784] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ab1ebb0da]
[fv-az1939-440:65784] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ab1ea5a55]
[fv-az1939-440:65784] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ab1ea5a6f]
[fv-az1939-440:65784] [ 8] plumed_master(+0x146dd)[0x561a975d96dd]
[fv-az1939-440:65784] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1ab1a2a1ca]
[fv-az1939-440:65784] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1ab1a2a28b]
[fv-az1939-440:65784] [11] plumed_master(+0x15365)[0x561a975da365]
[fv-az1939-440:65784] *** End of error message ***
</pre>
{% endraw %}
